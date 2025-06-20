```
0
```
# Software Requirements Specification

## Campus Ride-Sharing Platform With

## Parking System Integration

#### CSE6224 Software Requirements Engineering (TT2L)

#### Group Name:

#### Halin Roychana A/P I Roi 1211108961

#### Noor Azwani Binti Shamsudin 1211109188

#### Nur Aqilah Tan 241UC2407T

#### Farhana Adnin Binti Ahmad Effendi 242UC2451X

#### Date: 25 MAY 2025


## CONTENTS



- 1 Introduction......................................................................................................................
   - 1.1 Purpose....................................................................................................................
   - 1.2 Scope........................................................................................................................
   - 1.3 Product overview......................................................................................................
      - 1.3.1 Product Perspective.........................................................................................
         - 1.3.1.1 System Interfaces...................................................................................
         - 1.3.1.2 User Interfaces........................................................................................
      - 1.3.2 Product Functions..........................................................................................
         - 1.3.2.1 User......................................................................................................
            - 1.3.2.1.1 Login Credentials........................................................................
            - 1.3.2.1.2 Fill in required informations.........................................................
            - 1.3.2.1.3 Creating Carpool group...............................................................
            - 1.3.2.1.4 Joining Carpool group.................................................................
            - 1.3.2.1.5 Reserve Parking Spot.................................................................
            - 1.3.2.1.6 Make Payment............................................................................
            - 1.3.2.1.7 Leave Feedback.........................................................................
         - 1.3.2.2 Admin....................................................................................................
            - 1.3.2.2.1 Update & Store Users’ Data.........................................................
            - 1.3.2.2.2 Review Carpool Request.............................................................
            - 1.3.2.2.3 Validate Ride Details....................................................................
            - 1.3.2.2.4 Approve/Reject Carpools Request...............................................
            - 1.3.2.2.5 Receive Parking Approval............................................................
            - 1.3.2.2.6 Update & Store Booking Data into Database...............................
            - 1.3.2.2.7 Review & Store Comments or Feedbacks...................................
         - 1.3.2.3 System Administration..........................................................................
            - 1.3.2.3.1 Update Status to Users................................................................
            - 1.3.2.3.2 Retrieves Availability from Database...........................................
            - 1.3.2.3.3 Display Lists of Slots to Users.....................................................
            - 1.3.2.3.4 Calculate Total Cost.....................................................................
            - 1.3.2.3.5 Verify Payments...........................................................................
            - 1.3.2.3.6 Notify User with Invoice...............................................................
            - 1.3.2.3.7 Monitor Backend Logs.................................................................
         - 1.3.2.4 System Monitor.....................................................................................
            - 1.3.2.4.1 Monitor Parking Data Feed..........................................................
            - 1.3.2.4.2 Confirm & Update Available Slots................................................
            - 1.3.2.4.3 Receive User’s Parking Booking..................................................
            - 1.3.2.4.4 Review Parking Booking..............................................................
            - 1.3.2.4.5 Approve Parking Booking............................................................
            - 1.3.2.4.6 Update Data of Parking Reserved...............................................
      - 1.3.3 User Characteristic........................................................................................
      - 1.3.4 Limitations......................................................................................................
   - 1.4 Definitions...............................................................................................................
- 2 References.....................................................................................................................
- 3 Requirements.................................................................................................................
   - 3.1 Functions................................................................................................................
      - 3.1.1 User...............................................................................................................
         - 3.1.1.1 Login Credentials..................................................................................
         - 3.1.1.2 Fill in Required Information...................................................................
         - 3.1.1.3 Create Carpool Group...........................................................................
         - 3.1.1.4 Join Carpool Group...............................................................................
         - 3.1.1.5 Reserve Parking Spot...........................................................................
         - 3.1.1.6 Make Payment......................................................................................
         - 3.1.1.2 Leave Feedback...................................................................................
      - 3.1.2 Admin.............................................................................................................
         - 3.1.2.1 Update & Store Users’ Data..................................................................
         - 3.1.2.2 Review Carpool Request......................................................................
         - 3.1.2.3 Validate Ride Details.............................................................................
         - 3.1.2.4 Approve/Reject Carpools Request........................................................
         - 3.1.2.5 Receive Parking Approval.....................................................................
         - 3.1.2.6 Update & Store Booking Data into Database........................................
         - 3.1.2.7 Review & Store Comments or Feedback..............................................
      - 3.1.3 System Admin................................................................................................
         - 3.1.3.1 Update Status to Users.........................................................................
         - 3.1.3.2 Retrieve Availability...............................................................................
         - 3.1.3.3 Display Slot...........................................................................................
         - 3.1.3.4 Calculate Total Cost..............................................................................
         - 3.1.3.5 Verified Payment...................................................................................
         - 3.1.3.6 Notify User with Invoice........................................................................
         - 3.1.3.7 Monitor Backend Log............................................................................
      - 3.1.4 System Monitor..............................................................................................
         - 3.1.4.1 Monitor Parking Data Feed...................................................................
         - 3.1.4.2 Confirm & Update Available Slots.........................................................
         - 3.1.4.3 Receive User’s Parking Booking..........................................................
         - 3.1.4.4 Review Parking Booking.......................................................................
         - 3.1.4.5 Approve Parking Booking.....................................................................
         - 3.1.4.6 Update Data of Parking Reserved........................................................
   - 3.2 Performance requirements.....................................................................................
      - 3.2.1 User...............................................................................................................
      - 3.2.2 Admin.............................................................................................................
      - 3.2.3 System Admin................................................................................................
      - 3.2.4 System Monitor..............................................................................................
   - 3.3 Usability Requirements...........................................................................................
   - 3.4 Interface Requirements..........................................................................................
      - 3.4.1 External Interface...........................................................................................
         - 3.4.1.1 System Interface...................................................................................
            - 3.4.1.2.1 General Layout............................................................................
            - 3.4.1.2.2 Interfaces per Role.......................................................................
         - 3.4.1.3 Hardware Interface...............................................................................
         - 3.4.1.4 Software Interface.................................................................................
         - 3.4.1.5 Communication Interface......................................................................
   - 3.5 Logical Database Requirements.............................................................................
   - 3.6 Design Constraints.............................................................................................................
      - 3.6.1 User Interface Constraints.............................................................................
      - 3.6.2 Hardware Constraints....................................................................................
      - 3.6.3 Software Constraints.....................................................................................
      - 3.6.4 Communication Constraints...........................................................................
      - 3.6.5 Data Management Constraints......................................................................
      - 3.6.6 Memory Constraints.......................................................................................
      - 3.6.7 Operational Constraints.................................................................................
   - 3.7 Software System Attributes....................................................................................
      - 3.7.1 Reliability.......................................................................................................
      - 3.7.2 Availability......................................................................................................
      - 3.7.3 Security..........................................................................................................
      - 3.7.4 Maintainability................................................................................................
      - 3.7.5 Portability.......................................................................................................
   - 3.8 Supporting Information...........................................................................................
      - 3.8.1 Campus Ride-Sharing Platform Survey form.................................................
      - 3.8.2 Brainstorming.................................................................................................
      - 3.8.3 Existing System.............................................................................................
   - 3.9 Apportioning of Requirements................................................................................
   - 3.10 Specified Requirements........................................................................................
- 4 Verification.....................................................................................................................
   - 4.1 Verification Approach..............................................................................................
   - 4.2 Verification Criteria................................................................................................
- 5 Appendices..................................................................................................................
   - 5.1 Assumptions and Dependencies..........................................................................
      - 5.1.1 Assumptions................................................................................................
      - 5.1.2 Dependencies..............................................................................................
   - 5.2 Acronyms and Abbreviations................................................................................


## 1 Introduction......................................................................................................................

### 1.1 Purpose....................................................................................................................

The goal of the Campus Ride-Sharing Platform with Parking System Integration is to give
MMU employees and students a centralized, effective way to manage parking and ride-sharing. This
system works by requiring users to either start or join a carpool group before they can book a parking
space on campus as one of the ways on how the platform encourages carpooling.
The goals of this integrated system are to lessen traffic jams, make the best use of the few
parking spots available, and promote eco-friendly transportation. Only from a single platform users
can organize carpool arrangements, monitor real-time parking availability, make reservations and
payments, and securely log in using their university credentials. The system promotes campus
sustainability goals, improves user convenience, and streamlines administrative procedures associated
with campus transportation by fusing ride-sharing coordination with intelligent parking features.

### 1.2 Scope........................................................................................................................

This system will handle booking, approval, and tracking of campus carpool and parking
reservations. It allows authenticated university members the capability to create or join carpool
groups, and only upon carpool approval, parking spot reservation by real-time availability in
designated campus zones, are enabled only after carpool approval.


Key Features:

● Secure Authentication: University ID login ensures access is limited to authorized members.

● Flexible Carpooling: Enables users to create new carpool groups or join existing ones, with

approval workflows managed by group leaders and system administrators.

● Real-time Parking Management: Displays live parking availability in designated campus
zones, allowing approved carpools to make reservations.

● Comprehensive Administration: Provides an admin panel for efficient management of
requests and proactive system monitoring.

● Enhanced User Experience: Incorporates notifications and feedback mechanisms for quality
tracking and continuous improvement.

The website is limited to the campus community and does not support third-party or off-campus
services.


### 1.3 Product overview......................................................................................................

The Campus Ride-Sharing Platform with Parking System Integration is a secure web
application that is designed to serve the university community, including students, faculty, and staff.
The platform encourages green transportation by allowing users to create or join carpooling groups,
reducing single-occupancy vehicle trips to campus. Once a carpool has been approved, users can
reserve parking spots depending on real-time parking capacity within designated campus areas. The
system uses university digital ID authentication to provide access to the service by authenticated users
only. It also supports an admin dashboard for handling ride and parking requests, approving requests,
and monitoring system activity. The users are also informed about booking statuses and can provide
feedback after completing their rides. By combining carpool coordination and parking management,
this website will streamline campus traffic flow, optimize parking capacity, and promote more
sustainable commuting behavior.


#### 1.3.1 Product Perspective.........................................................................................

With the capability to reserve parking spaces, the Campus Ride-Sharing Platform provides a
centralized application for university employees and students to arrange rides. Because of its modular
design and service-oriented framework, the system may be integrated in real time with other
subsystems including administrative tools, payment gateways, and parking availability tracking.By
allowing users to plan their routes and handle hybrid travel (e.g., drive part way and then book a ride),
the platform improves campus mobility. For dependable data handling and seamless operation, the
system depends on administrative supervision, backend monitoring, and real-time synchronization.
The platform consists of four key roles:

**1. Users**

    ○ Login Credentials
    ○ Fills In Required Informations
    ○ Creating Carpool Group
    ○ Joining Carpool Group
    ○ Reserve Parking Spot
    ○ Make Payments
    ○ Leaves Feedback

**2. Admin**

    ○ Update And Store Users Data
    ○ Review Carpool Request
    ○ Validates Ride Details
    ○ Approves/Reject Carpools
    ○ Receive Parking Approval From System Monitor
    ○ Update And Store Data Of Bookings Into Database
    ○ Reviews Comment/Feedback

**3. System Administration**

    ○ Update status to users
    ○ Retrieves availability
    ○ Displays list of spots to User
    ○ Calculates total cost (ride + parking)
    ○ verified payment
    ○ Notify User with Invoice
    ○ Monitors backend logs for error

**4. System Monitor**

    ○ Monitors Parking Data Feed
    ○ Confirm & Update Available Slots
    ○ Receives Notification Of Parking Reserve
    ○ Review Parking Reserve
    ○ Approves Parking Reserve
    ○ Update Data Of Parking Reservation


_Figure 1.3.1: Context Diagram of Campus Ride Sharing Platform_


##### 1.3.1.1 System Interfaces...................................................................................

For the Ride-Sharing Platform to function properly, it communicates with a number of
internal and external systems. These interfaces preserve system operation and guarantee appropriate
module-to-module communication.

| Interface                     | Description                                                                                                                                                               | Purpose                                                                                                |
| :---------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------------------- |
| **University Authentication System** | The platform will integrate with the university’s Single Sign-On (SSO) or student/staff login portal to authenticate users based on their University ID                     | Ensures that only verified MMU students and staff can access and use the platform.                      |
| **Centralised Database System**      | Stores data related to user profile, carpool group information, parking slots, bookings and feedback                                                                       | Enable persistent data storage, retrieval and management of platform-related activities                 |
| **User Browser**              | The platform provides a user-friendly and responsive web interface where users can log in, view parking availability, manage carpools, and make bookings.                  | Facilitates interaction between users and the system.                                                   |
| **Web-based Admin Dashboard** | A secure panel for administrators to view and manage carpool requests, monitor parking lot usage, approve/reject bookings, and handle feedback                            | Enables efficient system management and oversight.                                                      |
| **Notification System**       | Send updates to user regarding carpool status, parking reservation confirmation and feedback request                                                                      | Keeps users informed about their interactions with the system in real-time.                             |

_Figure 1.3.1.1: Table of System Interface for Ride-Sharing Platform_


##### 1.3.1.2 User Interfaces........................................................................................

**Table 1.3.1.2** shows the user interface elements for the Campus Ride-Sharing Platform and
shows all the main screens for a user to interact with. Each interface is explained regarding its
purpose on the platform, the required input fields, the primary button or action a user can take,
and the feedback from the system after a user takes action. This helps demonstrate that the design
and interfaces honor user needs and follow the system expected behavior.

| Interface Name          | Description                                                                 | Input                                         | Button/Action       | System Feedback                                                                 |
| :---------------------- | :-------------------------------------------------------------------------- | :-------------------------------------------- | :------------------ | :------------------------------------------------------------------------------ |
| **Login Page**          | Allows user to log in using university credentials                           | Email/Username, Password                      | Log In              | Error on invalid login; redirect on success.                                    |
| **User Profile**        | Allows user to complete or update personal and vehicle info.                | Name, Contact, Vehicle Info, Preferences      | Save / Update       | “Profile Updated” message or validation errors.                                 |
| **Create Carpool Group**| Interface to create a new carpool ride.                                      | Ride Time, Route, Max Capacity, Vehicle Details| Submit Ride         | Confirmation of request submission or error alert.                              |
| **Join Carpool Group**  | Lets users search and request to join an active group.                       | Search Filters (Location, Time), Group List   | Join Group          | “Request Sent” or “Group Full” notifications.                                   |
| **Reserve Parking Spot**| Displays available spots and lets user make a reservation.                   | Date, Time Slot, Location                     | Reserve Parking     | “Parking Reserved” confirmation or “Slot Unavailable.”                          |
| **Make Payment**        | Interface to pay for ride/parking fees.                                      | Card Details / FPX / Payment Method           | Pay Now             | “Payment Successful” or “Payment Failed.”                                       |
| **Leave Feedback**      | Interface to submit feedback for past rides.                                 | Rating (1–5), Comment                         | Submit Feedback     | “Feedback Submitted” or error message.                                          |
| **Dashboard / Home Page**| Main navigation panel after login; quick links to all modules. Displays user name, carpool & parking status updates. | - | Navigation Tabs (Profile, Book, Feedback, etc.)                   | Displays user name, carpool & parking status updates. |
| **Notification Popups** | Small alerts on booking, approval, and feedback responses.                  | -                                             | Close / View More   | Real-time updates (e.g., “Your carpool is approved.”)                           |

_Table 1.3.1.2: User Interfaces for Ride-Sharing Platform_


#### 1.3.2 Product Functions..........................................................................................

```
Figure 1.3.2: Use Case Diagram of Campus Ride Sharing Platform
```

##### 1.3.2.1 User......................................................................................................

###### 1.3.2.1.1 Login Credentials........................................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Login with Credentials                                                                              |
| **Version**           | 1                                                                                                   |
| **Description**       | Allows users to securely log in with registry email/username & password to use the features of the platform. |
| **Primary Actor**     | User                                                                                                |
| **Precondition**      | ● Users are registered on the platform<br>● System is operational                                    |
| **Postcondition**     | ● User is authenticated and directed to the dashboard/home page                                     |
| **Main Success Scenario** | 1. User clicks on the log in page<br>2. User enters log in credentials<br>3. User clicks on the Log In button<br>4. System checks credentials<br>5. User is logged in and gets directed to home page |
| **Alternative Scenario** | ● Characters are incorrect: system indicates an error message<br>● User account is inactive; system indicates this to the user |

_Table 1.3.2.1.1: Login Credentials_


###### 1.3.2.1.2 Fill in required informations.........................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Fill in required information                                                                        |
| **Version**           | 1                                                                                                   |
| **Description**       | User completes or modifies their profile with personal and ride-related preferences                 |
| **Primary Actor**     | User                                                                                                |
| **Precondition**      | User has logged into the system                                                                     |
| **Postcondition**     | User's information was saved into the system for personalization and operational purposes           |
| **Main Success Scenario** | 1. Users navigate to their profile settings<br>2. User completes required fields (name, contact information, car information, preferences)<br>3. User submits the form<br>4. System validates and saves the information |
| **Alternative Scenario** | ● If the user has not filled out the fields: system messages user to fill out the fields<br>● If the data is in wrong format: system tells user to correct the data |

_Table 1.3.2.1.2: Fill in required informations_

###### 1.3.2.1.3 Creating Carpool group...............................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Create Carpool Group                                                                                |
| **Version**           | 1                                                                                                   |
| **Description**       | Allows a user to create a new carpool group and provide ride information, such as time, route, and capacity. |
| **Primary Actor**     | User                                                                                                |
| **Precondition**      | ● User is logged in<br>● User profile contains verified vehicle details                             |
| **Postcondition**     | Carpool group request is submitted for admin approval                                               |
| **Main Success Scenario** | 1. User navigates to "Create Carpool Group"<br>2. User enters ride information<br>3. User submits the form<br>4. System validates data and submits request to admin for review |
| **Alternative Scenario** | ● If required data is missing: system prompts user to complete<br>● If submission fails: system shows error message |

_Table 1.3.2.1.3: Creating Carpool group_


###### 1.3.2.1.4 Joining Carpool group.................................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Joining Carpool Group                                                                               |
| **Version**           | 1                                                                                                   |
| **Description**       | Allows a user to search available carpool groups and join based on preferences and availability      |
| **Primary Actor**     | User                                                                                                |
| **Precondition**      | ● User is logged in<br>● At least 1 active group exists in the system                               |
| **Postcondition**     | User is added to the selected carpool group                                                         |
| **Main Success Scenario** | 1. User browses available carpool groups<br>2. User selects group and requests to join<br>3. System checks seat availability<br>4. System confirms request and adds user to group |
| **Alternative Scenario** | ● If no seats available: system provides notification<br>● If joining fails: error message displayed |

_Table 1.3.2.1.4: Joining Carpool group_


###### 1.3.2.1.5 Reserve Parking Spot.................................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Reserve Parking Spot                                                                                |
| **Version**           | 1                                                                                                   |
| **Description**       | Allows the user to reserve a parking spot for a scheduled ride                                      |
| **Primary Actor**     | User                                                                                                |
| **Precondition**      | User is part of an approved carpool                                                                 |
| **Postcondition**     | Parking spot reserved and persisted to the system                                                   |
| **Main Success Scenario** | 1. User accesses parking reservation module<br>2. User selects location and time<br>3. System checks availability<br>4. User confirms reservation<br>5. System updates reservation and notifies user |
| **Alternative Scenario** | ● If no available slots: module displays "Not Available"<br>● If booking fails: module displays error message |

_Table 1.3.2.1.5: Reserve Parking Spot_

###### 1.3.2.1.6 Make Payment............................................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Make Payment                                                                                        |
| **Version**           | 1                                                                                                   |
| **Description**       | Allows the user to pay for services (e.g., parking or carpooling fees) using supported payment methods |
| **Primary Actor**     | User                                                                                                |
| **Precondition**      | ● User is logged in<br>● Payment is owed                                                           |
| **Postcondition**     | Payment is processed and recorded                                                                   |
| **Main Success Scenario** | 1. User navigates to payment section<br>2. User selects payment method<br>3. User inputs payment information<br>4. User confirms payment<br>5. System processes payment and generates confirmation |
| **Alternative Scenario** | ● If payment fails: system logs error and notifies user<br>● If input invalid: user prompted to re-enter |

_Table 1.3.2.1.6: Make Payment_

###### 1.3.2.1.7 Leave Feedback.........................................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Leave Feedback                                                                                      |
| **Version**           | 1                                                                                                   |
| **Description**       | Users can leave feedback or rate their carpool experience                                           |
| **Primary Actor**     | User                                                                                                |
| **Precondition**      | User has completed a carpool ride                                                                   |
| **Postcondition**     | Feedback is stored and made available to admins/relevant users                                      |
| **Main Success Scenario** | 1. User navigates to feedback section<br>2. User selects specific ride<br>3. User completes feedback form/rating<br>4. User submits feedback<br>5. System saves feedback |
| **Alternative Scenario** | ● If form incomplete: system requires completion<br>● If submission fails: system notifies user     |

_Table 1.3.2.1.7: Leave Feedback_

##### 1.3.2.2 Admin....................................................................................................

###### 1.3.2.2.1 Update & Store Users’ Data.........................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Update & Store Users' Data                                                                          |
| **Version**           | 1                                                                                                   |
| **Description**       | Admin updates and stores user-related data (profile info, carpool history, preferences) to maintain accurate data for efficient platform management |
| **Primary Actor**     | Admin                                                                                               |
| **Precondition**      | ● Admin is authenticated<br>● Access to user data management module granted                         |
| **Postcondition**     | ● Users' data updated in database<br>● Data retrievable accurately by system/relevant actors        |
| **Main Success Scenario** | 1. Admin logs into system<br>2. Admin navigates to user data management<br>3. Admin selects user profile<br>4. Admin edits fields (name, email, contact, car details)<br>5. Admin submits changes<br>6. System updates database<br>7. Confirmation message shown |
| **Alternative Scenario** | ● If user profile doesn't exist: system displays error<br>● If data validation fails: system prompts correction<br>● If database update fails: system logs error and notifies admin |

_Table 1.3.2.2.1: Update & Store Users’ Data_

###### 1.3.2.2.2 Review Carpool Request.............................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Review Carpool Request                                                                              |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Allows Admin to review carpool group creation requests, evaluating ride details (driver info, time, location, capacity) to ensure platform compliance |
| **Primary Actor**     | Admin                                                                                               |
| **Precondition**      | ● Admin logged in with access to carpool management<br>● At least one carpool request submitted     |
| **Postcondition**     | Request either approved (becomes active) or rejected with reason recorded                           |
| **Main Success Scenario** | 1. Admin logs into system<br>2. Admin navigates to carpool management<br>3. Admin views pending requests<br>4. Admin selects and reviews ride details<br>5. Admin verifies information accuracy/completeness<br>6. Admin approves request<br>7. System updates status and notifies requester |
| **Alternative Scenario** | ● If details incomplete/invalid: Admin rejects with reason → system notifies requester<br>● If status update fails: error shown and logged |

_Table 1.3.2.2.2: Review Carpool Request_

###### 1.3.2.2.3 Validate Ride Details....................................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Validate Ride Details                                                                               |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Admin validates ride details submitted for carpool creation/update, ensuring compliance with platform policies (driver credentials, pickup/drop-off points, schedule, capacity) |
| **Primary Actor**     | Admin                                                                                               |
| **Precondition**      | Ride details submitted by user and pending validation                                               |
| **Postcondition**     | Ride details either validated (ready for approval) or flagged for correction                        |
| **Main Success Scenario** | 1. Admin logs into system<br>2. Admin navigates to pending ride submissions<br>3. Admin selects ride<br>4. Admin verifies completeness and compliance (license validity, schedule appropriateness)<br>5. Admin marks as "validated"<br>6. System updates status and notifies parties |
| **Alternative Scenario** | ● If details missing/invalid: Admin marks as "invalid" with correction notes → system notifies user to revise/resubmit |

_Table 1.3.2.2.3: Validate Ride Details_

###### 1.3.2.2.4 Approve/Reject Carpools Request...............................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Approve/Reject Carpools Request                                                                     |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Admin approves or rejects validated carpool requests. Approval activates carpool for joining; rejection prevents listing with reason stored. |
| **Primary Actor**     | Admin                                                                                               |
| **Precondition**      | ● Admin logged into system<br>● Ride details already validated                                      |
| **Postcondition**     | Request either approved (published) or rejected (with reason stored)                                |
| **Main Success Scenario** | 1. Admin logs into system<br>2. Admin navigates to validated requests<br>3. Admin selects request<br>4. Admin reviews final information<br>5. Admin selects "Approve" or "Reject"<br>6. If approved: system activates carpool and notifies requester<br>7. If rejected: system stores reason and notifies requester |
| **Alternative Scenario** | ● If additional info needed: Admin puts request on hold → contacts requester<br>● If status update fails: system logs error → displays message → admin retries/reports |

_Table 1.3.2.2.4: Approve/Reject Carpool Request_

###### 1.3.2.2.5 Receive Parking Approval............................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Receive Parking Approval                                                                            |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Admin receives parking approval status from System Monitor, then records and updates booking data for tracking/reporting |
| **Primary Actor**     | Admin                                                                                               |
| **Precondition**      | ● System Monitor has approved parking booking<br>● Admin logged in with booking management access   |
| **Postcondition**     | Parking booking status updated in system and stored in database                                     |
| **Main Success Scenario** | 1. Admin logs into system<br>2. Admin navigates to parking approvals<br>3. Admin views approved bookings list<br>4. Admin verifies booking details<br>5. Admin confirms receipt and updates status<br>6. System logs update and sends user confirmation |
| **Alternative Scenario** | ● If approval not received: Admin waits or requests update from System Monitor<br>● If status update fails: error logged → admin notified → admin retries/escalates |

_Table 1.3.2.2.5: Receive Parking Approval_

###### 1.3.2.2.6 Update & Store Booking Data into Database...............................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Update & Store Booking Data into Database                                                           |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Admin inputs and stores finalized booking data after carpool and parking approvals, maintaining complete records for reporting, tracking, and confirmation |
| **Primary Actor**     | Admin                                                                                               |
| **Precondition**      | ● Carpool request approved by Admin<br>● Parking reservation approved by System Monitor             |
| **Postcondition**     | Booking data stored in database                                                                     |
| **Main Success Scenario** | 1. Admin logs into system<br>2. Admin navigates to booking management<br>3. Admin verifies both approvals are complete<br>4. Admin enters booking details (user info, ride info, parking slot, timing, cost)<br>5. Admin submits data<br>6. System stores data → sends user confirmation |
| **Alternative Scenario** | ● If approvals incomplete: system blocks progress → displays notification<br>● If submission fails: system displays error → logs issue → admin retries/contacts support |

_Table 1.3.2.2.6: Update & Store Data Booking into Database_

###### 1.3.2.2.7 Review & Store Comments or Feedbacks...................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Review & Store Comments or Feedbacks                                                                |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Admin reviews user feedback about ride-sharing/parking experiences and stores relevant feedback for future reference, analysis, or improvement |
| **Primary Actor**     | Admin                                                                                               |
| **Precondition**      | Users have submitted feedback through the system                                                    |
| **Postcondition**     | Feedback reviewed and either stored in database or flagged for further action                       |
| **Main Success Scenario** | 1. Admin logs into system<br>2. Admin accesses feedback management module<br>3. Admin views new/unprocessed feedback<br>4. Admin reviews submissions for relevance/quality<br>5. Admin stores valid/constructive feedback<br>6. Admin flags feedback needing follow-up<br>7. System updates status to "Stored" or "Flagged" |
| **Alternative Scenario** | ● If feedback contains inappropriate/abusive content: Admin flags and escalates to System Administration/moderation team |

_Table 1.3.2.2.7: Review & Store Comments or Feedbacks_

##### 1.3.2.3 System Administration..........................................................................

###### 1.3.2.3.1 Update Status to Users................................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Update Status to Users                                                                              |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Updates booking/system status to users after verification (e.g., payment confirmation, carpool approval) |
| **Primary Actor**     | System Administration                                                                               |
| **Precondition**      | Status update exists and requires notification                                                      |
| **Postcondition**     | User notified of updated status                                                                     |
| **Main Success Scenario** | 1. System Administration accesses user management panel<br>2. Receives database updates from Admin/System Monitor<br>3. Reviews "pending notification sending" queue<br>4. Selects relevant booking/user<br>5. Updates status<br>6. System sends notification to user |
| **Alternative Scenario** | ● If database error occurs: notification process halts → error logged<br>● If status update fails: system retries or alerts technical team |

_Table 1.3.2.3.1: Update Status to Users_

###### 1.3.2.3.2 Retrieves Availability from Database...........................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Retrieves Availability from Database                                                                |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Retrieves real-time parking slot data from database to ensure accurate status display                |
| **Primary Actor**     | System Administration                                                                               |
| **Precondition**      | ● System logged in<br>● Database operational                                                        |
| **Postcondition**     | Parking availability retrieved and ready for display to users                                       |
| **Main Success Scenario** | 1. Admin accesses parking availability module<br>2. System queries database<br>3. Current availability retrieved<br>4. Data displayed to end users |
| **Alternative Scenario** | ● If database timeout/failure occurs: system returns error → logs incident<br>● If retrieval fails: system displays cached data or maintenance message |

_Table 1.3.2.3.2: Retrieves Availability from Database_

###### 1.3.2.3.3 Display Lists of Slots to Users.....................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Display List of Slots to User                                                                       |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Ensures the platform displays an up-to-date list of available parking slots                          |
| **Primary Actor**     | System Administration                                                                               |
| **Precondition**      | User requests parking slot information                                                              |
| **Postcondition**     | User views updated list of available slots for reservation                                          |
| **Main Success Scenario** | 1. Admin verifies slot data retrieval<br>2. System displays available parking slots to users<br>3. Users interact with list to make bookings |
| **Alternative Scenario** | ● If display fails: system shows error message or maintenance notification<br>● If outdated list shown: system triggers data refresh or alerts technical team |

_Table 1.3.2.3.3: Display List of Slot to User_

###### 1.3.2.3.4 Calculate Total Cost.....................................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Calculate Total Cost                                                                                |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Reviews and verifies correct cost calculation for reservations based on duration, slot type, and carpooling status |
| **Primary Actor**     | System Administration                                                                               |
| **Precondition**      | ● User submits booking details<br>● Pricing scheme available in system                              |
| **Postcondition**     | Total cost calculated and presented to user for payment                                             |
| **Main Success Scenario** | 1. Admin verifies rate rules configuration<br>2. System calculates cost based on input parameters<br>3. Final cost displayed to user |
| **Alternative Scenario** | ● If pricing rules outdated/missing: system defaults to standard rate or shows error<br>● Admin corrects rates → triggers recalculation |

_Table 1.3.2.3.4: Calculate Total Cost_

###### 1.3.2.3.5 Verify Payments...........................................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Verify Payments                                                                                     |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Verifies user payment information by cross-checking with payment gateway to confirm successful transactions |
| **Primary Actor**     | System Administration                                                                               |
| **Precondition**      | ● Payment made by user<br>● System Admin authenticated                                             |
| **Postcondition**     | ● Payment verified and logged<br>● Status marked as "Paid"                                         |
| **Main Success Scenario** | 1. System Admin accesses payment verification<br>2. System cross-checks transaction with gateway<br>3. Valid payment confirmed<br>4. Booking marked as paid |
| **Alternative Scenario** | ● If payment mismatch/failure: system admin contacts user for resubmission → system logs failed verification |

_Table 1.3.2.3.5: Verify Payments_

###### 1.3.2.3.6 Notify User with Invoice...............................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Notify User with Invoice                                                                            |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Sends confirmation messages to users after successful actions (booking, payment, approval)           |
| **Primary Actor**     | System Administration                                                                               |
| **Precondition**      | Successful booking completed                                                                        |
| **Postcondition**     | User receives confirmation notification via platform, email, or SMS                                 |
| **Main Success Scenario** | 1. System receives booking approval update<br>2. System Administration validates data<br>3. System triggers confirmation message<br>4. User receives and views notification |
| **Alternative Scenario** | ● If notification fails: system retries sending<br>● If persistent failure: message stored in logs → admin notified |

_Table 1.3.2.3.6: Notify User with Invoice_

###### 1.3.2.3.7 Monitor Backend Logs.................................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Monitor Backend Logs                                                                                |
| **Version**           | 1.0                                                                                                 |
| **Description**       | Monitors system logs for performance, error tracking, and audit purposes                            |
| **Primary Actor**     | System Administration                                                                               |
| **Precondition**      | ● System admin logged in with required permissions<br>● System generates logs regularly             |
| **Postcondition**     | ● Logs reviewed for errors, performance metrics, and suspicious activity<br>● Actions taken recorded |
| **Main Success Scenario** | 1. Admin opens log monitoring module<br>2. Views logs using filters (date, action type)<br>3. Identifies issues or verifies normal operation<br>4. Takes corrective action if needed |
| **Alternative Scenario** | ● If log module fails: temporary logs accessed manually<br>● If persistent failure: system alerts technical team for maintenance |

_Table 1.3.2.3.7: Monitor Backend Logs_

##### 1.3.2.4 System Monitor.....................................................................................

###### 1.3.2.4.1 Monitor Parking Data Feed..........................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Monitor Parking Data Feed                                                                           |
| **Version**           | 1.0                                                                                                 |
| **Description**       | System Monitor constantly monitors real-time parking data feed to refresh system with up-to-date slot availability |
| **Primary Actor**     | System Monitor                                                                                      |
| **Precondition**      | Parking system online and interfaced with slot sensors or manual input sources                      |
| **Postcondition**     | System updated with latest parking slot details showing accurate availability for users             |
| **Main Success Scenario** | 1. System Monitor initiates parking data feed scan<br>2. System receives real-time data from sensors/input sources<br>3. System processes data and calculates available slots<br>4. Updated availability stored in database<br>5. Updated data reflected in user interface |
| **Alternative Scenario** | ● If data feed unavailable: system logs issue → retries after interval<br>● If retries fail: alert sent to system administrator for manual intervention |

_Table 1.3.2.4.1 Monitor Parking Data Feed_

###### 1.3.2.4.2 Confirm & Update Available Slots................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Confirm & Update Available Slots                                                                    |
| **Version**           | 1.0                                                                                                 |
| **Description**       | System Monitor confirms parking slot count and updates system to reflect latest availability based on real-time data or user actions |
| **Primary Actor**     | System Monitor                                                                                      |
| **Precondition**      | Real-time parking data feed active and database accessible for updates                              |
| **Postcondition**     | System reflects most accurate number of available parking slots for reservation                     |
| **Main Success Scenario** | 1. System Monitor receives new parking occupancy data<br>2. Confirms data accuracy (checks against current records)<br>3. Calculates available parking slots<br>4. Updates database with new count<br>5. Availability refreshed on user interface |
| **Alternative Scenario** | ● If data inconsistency detected: system flags entry for review → logs issue → notifies administrator<br>● Falls back to last known good data until resolved |

_Table 1.3.2.4.2 Confirm & Update Available Slots_

###### 1.3.2.4.3 Receive User’s Parking Booking..................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Receive User's Parking Booking                                                                      |
| **Version**           | 1.0                                                                                                 |
| **Description**       | System Monitor receives parking reservation requests after carpool approval and payment verification |
| **Primary Actor**     | System Monitor                                                                                      |
| **Precondition**      | ● User authenticated<br>● Carpool group approved<br>● Payment verified (if required)                |
| **Postcondition**     | Parking reservation request received and queued for review/processing                               |
| **Main Success Scenario** | 1. User submits parking reservation<br>2. System Monitor receives request<br>3. Booking details logged (user ID, time, zone)<br>4. Triggers "Review Parking Booking" use case<br>5. Notifies admin/responsible process for approval |
| **Alternative Scenario** | ● If request has missing/invalid data: system rejects request → user notified to resubmit with correct information |

_Table 1.3.2.4.3 Receive User’s Parking Booking_

###### 1.3.2.4.4 Review Parking Booking..............................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Review Parking Booking                                                                              |
| **Version**           | 1.0                                                                                                 |
| **Description**       | System Monitor examines user parking reservation details before approval or rejection decision       |
| **Primary Actor**     | System Monitor                                                                                      |
| **Precondition**      | ● Valid parking reservation request received<br>● Parking data feed and slot availability up-to-date |
| **Postcondition**     | Booking request approved or marked for rejection based on availability and policy rules             |
| **Main Success Scenario** | 1. System Monitor retrieves reservation request<br>2. Compares request against real-time parking availability<br>3. Validates timing, location, and user eligibility<br>4. Marks request as ready for approval<br>5. Notifies "Approve Parking Booking" process |
| **Alternative Scenario** | ● If slot taken or data outdated: system flags request as failed → user notified to choose another slot or retry later |

_Table 1.3.2.4.4 Review Parking Booking_

###### 1.3.2.4.5 Approve Parking Booking............................................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Approve Parking Booking                                                                            |
| **Version**           | 1.0                                                                                                 |
| **Description**       | System Monitor confirms and finalizes user parking reservations by approving them and triggering system updates |
| **Primary Actor**     | System Monitor                                                                                      |
| **Precondition**      | ● Parking booking request reviewed and validated<br>● Parking slot available                        |
| **Postcondition**     | ● Slot reserved for user<br>● System availability updated<br>● Relevant parties notified            |
| **Main Success Scenario** | 1. System Monitor selects reviewed booking<br>2. Confirms details validity and slot availability<br>3. Approves request<br>4. Updates system to mark slot reserved<br>5. Sends confirmation to user, admin, and system components |
| **Alternative Scenario** | ● If slot unavailable during approval: system aborts process → user notified to make new reservation |

_Table 1.3.2.4.5 Approve Parking Booking_

###### 1.3.2.4.6 Update Data of Parking Reserved...............................................

| Field                 | Value                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------- |
| **Use Case Name**     | Update Data of Parking Reserved                                                                     |
| **Version**           | 1.0                                                                                                 |
| **Description**       | System Monitor updates internal database to reflect successful parking reservation, ensuring availability data accuracy |
| **Primary Actor**     | System Monitor                                                                                      |
| **Precondition**      | Parking booking approved by System Monitor                                                          |
| **Postcondition**     | ● Reserved slot marked unavailable in system<br>● Booking details recorded in database              |
| **Main Success Scenario** | 1. System Monitor receives confirmed approval<br>2. Accesses current parking data<br>3. Updates slot status to "Reserved"<br>4. Logs reservation details (user, time, location)<br>5. Syncs updated data across all relevant modules |
| **Alternative Scenario** | ● If database update fails: system logs error → notifies System Administrator<br>● User informed of failure and prompted to retry reservation |

_Table 1.3.2.4.6 Update Data of Parking Reserved_

#### 1.3.3 User Characteristic........................................................................................

The Campus Ride-Sharing and Parking Reservation System target user groups may differ
based on the deployment context. However, some of the common user characteristics that may
influence usability problems are as follows:

1. User (Students, Faculty, Staff):
    I. Users shall log in using their university credentials.
II. Users shall fill in required personal and ride-related information.
III. Users shall create a new carpool group when initiating a ride.
IV. Users shall join an existing carpool group upon invitation or acceptance.
V. Users shall reserve a parking spot once their carpool is approved.
VI. Users shall make parking payments through the system.
VII. Users shall leave feedback or ratings based on their experience.

2. Admin:
    I. Admin shall update and store users' personal and carpool data.
II. Admin shall review all new carpool creation and join requests.
III. Admin shall validate carpool ride details such as participants and schedules.
IV. Admin shall approve or reject carpool group requests.
V. Admin shall receive parking approval notifications from the system monitor.
VI. Admin shall update and store final booking data in the system database.
VII. Admin shall review user feedback and comments for quality assurance.

3. System Administration:
    I. System Administration shall update booking or status notifications to users.
II. System Administration shall retrieve parking availability from the system database.
III. System Administration shall display a list of available parking slots to users.
IV. System Administration shall calculate the total cost including ride and parking.
V. System Administration shall verify payment transactions.
VI. System Administration shall send booking confirmation notifications via system and email.
VII. System Admin shall monitor backend logs and handle technical errors.

4. System Monitor:
    I. System Monitor shall monitor real-time parking data feeds.
II. System Monitor shall update available parking slot information.


III. System Monitor shall confirm the current parking count.
IV. System Monitor shall receive parking reservation requests from users.
V. System Monitor shall auto-approve valid parking reservations.
VI. System Monitor shall update reserved parking data in the database.


#### 1.3.4 Limitations......................................................................................................

● Dependency on Real-Time Data:
The system relies heavily on real-time parking availability data. Any delay or
inconsistency in this data may affect booking accuracy.

● Limited Feedback Moderation:
Comments flagged as inappropriate are only reviewed manually by the System
Monitor. There is no automated filtering or AI moderation for user-submitted content.

● Platform scope:
The system is only accessible to users with valid university IDs. it does not support
external user or guest login.

● Dependant on Internet Connectivity:
Users must have internet access to use the platform. Offline functionality does not
support the system.

● Manual Approval:
Carpool group approval may require manual invention by the admins, possibly
introducing delay


### 1.4 Definitions...............................................................................................................

**Table 1.4** shows the core definitions that are used throughout the Campus Ride-Sharing
Platform with Parking System Integration. These definitions provide clarity on the actors and
components of the system as well as terms used for user interaction, systems administration, parking
management and back-end. To facilitate a cohesive understanding of the terms used herein will help
ensure that the reader applies the same interpretation to the overall requirements and functionality
described in this document.

| Term                   | Definition                                                                                                                          |
| :--------------------- | :---------------------------------------------------------------------------------------------------------------------------------- |
| **User**               | A student, staff, or faculty member of MMU who utilizes the platform to form/join carpools or reserve parking spots                   |
| **Admin**              | The user role responsible for adding user information, checking/approving carpool requests, and modifying reservations                   |
| **System Monitor**     | Assesses real-time parking spot availability, collects/maintains parking data, and approves parking reservations                     |
| **System Administrator** | Supervises back-end actions to update reservation status, approve/deny payments, and send confirmations                           |
| **Carpool Group**      | A group created by users to carpool together to/from campus; requires confirmation before use                                         |
| **Parking Reservation** | A Confirmed reservation for campus parking, available only to confirmed carpool members                                             |
| **Feedback**           | Comments or ratings from users based on their carpool and reservation experience                                                    |
| **Authentication System** | The university login system that verifies users with MMU credentials                                                                  |
| **Dashboard**          | The administrative web interface for managing requests, monitoring system activities, and reviewing feedback                             |
| **Real-time Parking Feed** | A live feed showing location and availability of parking spots across campus areas                                                  |
| **Payment Gateway**    | A third-party system integrated into the platform to process user payments for services                                               |
| **Notification System** | A component that sends system alerts, updates, and confirmations to users via email or platform                                     |

**_Table 1.4_** _: Key Terms and Definitions for the Campus Ride-Sharing Platform_


## 2 References.....................................................................................................................

This Document is prepared in reference to the following documents:

1. KDK College of Engineering. _SE Unit 2: Software Engineering – Requirements Engineering_.
    https://kdkce.edu.in/writereaddata/fckimagefile/SE%20Unit%202.pdf
2. D. Sachan, “Software Engineering | Requirement Engineering,” _Scaler Topics_ , Sep. 20, 2023.
    https://www.scaler.com/topics/requirements-engineering-in-software-engineering/
3. _IEEE Recommended Practice for Software Requirements Specifications (IEEE Std 830-1998)._
    Institute of Electrical and Electronics Engineers, 1998.
    https://anyflip.com/pncyn/vebt/basic
4. GeeksforGeeks, "Software Engineering – Requirements Engineering Process."
    https://www.geeksforgeeks.org/software-engineering-requirements-engineering-process/


## 3 Requirements.................................................................................................................

### 3.1 Functions................................................................................................................

#### 3.1.1 User...............................................................................................................

##### 3.1.1.1 Login Credentials..................................................................................

```
Figure 3.1.1.1: Sequence Diagram (Login Credentials)
```

##### 3.1.1.2 Fill in Required Information...................................................................

_Figure 3.1.1.2: Sequence Diagram (Fill in Required Information)_


##### 3.1.1.3 Create Carpool Group...........................................................................

_Figure 3.1.1.3: Sequence Diagram (Create Carpool Group)_


##### 3.1.1.4 Join Carpool Group...............................................................................

_Figure 3.1.1.4: Sequence Diagram (Join Carpool Group)_


##### 3.1.1.5 Reserve Parking Spot...........................................................................

_Figure 3.1.1.5: Sequence Diagram (Reserve Parking Spot)_


##### 3.1.1.6 Make Payment......................................................................................

```
Figure 3.1.1.6: Sequence Diagram (Make Payment)
```

##### 3.1.1.2 Leave Feedback...................................................................................

```
Figure 3.1.1.2: Sequence Diagram (Leave Feedback)
```

#### 3.1.2 Admin.............................................................................................................

##### 3.1.2.1 Update & Store Users’ Data..................................................................

```
Figure 3.1.2.1: Update & Store Users’ Data Sequence Diagram
```

##### 3.1.2.2 Review Carpool Request......................................................................

_Figure 3.1.2.2: Review Carpool Request Data Sequence Diagram_


##### 3.1.2.3 Validate Ride Details.............................................................................

_Figure 3.1.2.3: Validate Ride Details Sequence Diagram_


##### 3.1.2.4 Approve/Reject Carpools Request........................................................

_Figure 3.1.2.4: Approve/Reject Carpool Request Sequence Diagram_


##### 3.1.2.5 Receive Parking Approval.....................................................................

_Figure 3.1.2.5: Receive Parking Approval Sequence Diagram_


##### 3.1.2.6 Update & Store Booking Data into Database........................................

_Figure 3.1.2.6: Update & Store Booking Data into Database Sequence Diagram_


##### 3.1.2.7 Review & Store Comments or Feedback..............................................

_Figure 3.1.2.7: Review & Store Comments or Feedbacks Sequence Diagram_


#### 3.1.3 System Admin................................................................................................

##### 3.1.3.1 Update Status to Users.........................................................................

```
Figure 3.1.3.1: Update Status to Users Sequence Diagram
```

##### 3.1.3.2 Retrieve Availability...............................................................................

```
Figure 3.1.3.2: Retrieve Availability Sequence Diagram
```

##### 3.1.3.3 Display Slot...........................................................................................

```
Figure 3.1.3.3: Display Slot Sequence Diagram
```

##### 3.1.3.4 Calculate Total Cost..............................................................................

```
Figure 3.1.3.4: Calculate Total Cost Sequence Diagram
```

##### 3.1.3.5 Verified Payment...................................................................................

```
Figure 3.1.3.5: Verified Payment Sequence Diagram
```

##### 3.1.3.6 Notify User with Invoice........................................................................

```
Figure 3.1.3.6: Notify User with Invoice Sequence Diagram
```

##### 3.1.3.7 Monitor Backend Log............................................................................

```
Figure 3.1.3.7: Monitor Backend Log Sequence Diagram
```

#### 3.1.4 System Monitor..............................................................................................

##### 3.1.4.1 Monitor Parking Data Feed...................................................................

```
Figure 3.1.4.1: Monitor Parking Data Feed Sequence Diagram
```
##### 3.1.4.2 Confirm & Update Available Slots.........................................................

_Figure 3.1.4.2: Confirm & Update Available Slots Sequence Diagram_


##### 3.1.4.3 Receive User’s Parking Booking..........................................................

```
Figure 3.1.4.3: Receive User’s Parking Booking Sequence Diagram
```
##### 3.1.4.4 Review Parking Booking.......................................................................

```
Figure 3.1.4.4: Review Parking Booking Sequence Diagram
```

##### 3.1.4.5 Approve Parking Booking.....................................................................

```
Figure 3.1.4.5: Approve Parking Booking Sequence Diagram
```
##### 3.1.4.6 Update Data of Parking Reserved........................................................

```
Figure 3.1.4.6: Update Data of Parking Reserved Sequence Diagram
```

### 3.2 Performance requirements.....................................................................................

#### 3.2.1 User...............................................................................................................

| Performance Req No. | Description                                                                                                |
| :------------------ | :--------------------------------------------------------------------------------------------------------- |
| **PR1**             | The system must authenticate users and load the dashboard within<br>2 seconds after successful login.        |
| **PR2**             | Users must be able to fill and submit their personal and ride-related<br>information with confirmation received within 3 seconds. |
| **PR3**             | Users must be able to create a carpool group, and the request<br>should be submitted and acknowledged by the system within 4<br>seconds. |
| **PR4**             | When joining a carpool group, the system should check for<br>availability and respond within 3 seconds.     |
| **PR5**             | Users must be able to view and reserve available parking slots, and<br>get confirmation within 3 seconds.   |
| **PR6**             | Payment processing should be completed and confirmation shown<br>to the user within 5 seconds.              |
| **PR7**             | Feedback submitted by the user should be stored and confirmation<br>displayed within 2 seconds.             |

_Table 3.2.1: Performance Requirement for User_


#### 3.2.2 Admin.............................................................................................................

| Performance Req No. | Description                                                                                                |
| :------------------ | :--------------------------------------------------------------------------------------------------------- |
| **PR8**             | The admin is able to update and store users’ data such as name,<br>contact information, and status.         |
| **PR9**             | The admin can review user-submitted carpool requests, including<br>the requester's details, the date, time, and pickup and drop-off<br>locations. |
| **PR10**            | The admin is able to validate ride details submitted by users,<br>ensuring the information is complete and accurate before approval. |
| **PR11**            | The admin is able to approve or reject carpool requests based on the<br>submitted ride details.             |
| **PR12**            | The admin is able to receive and view parking approval requests for<br>users linked to carpool bookings.     |
| **PR13**            | The admin is able to update booking details and store them securely<br>in the database.                     |
| **PR14**            | The admin is able to review user comments or feedback and store<br>them in the system for future reference.  |

_Table 3.2.2 : Performance Requirement for Admin_


#### 3.2.3 System Admin................................................................................................

| Performance Req No. | Description                                                                                                |
| :------------------ | :--------------------------------------------------------------------------------------------------------- |
| **PR15**            | The system must allow the System Admin to update a user's status<br>(e.g., booking, payment, approval) and send notifications within 2<br>seconds of initiating the action |
| **PR16**            | Real-time slot availability data must be retrieved and displayed to<br>the System Admin within 1 second of request, assuming a<br>responsive database. |
| **PR17**            | Users must be able to see the displayed list of slots updated by the<br>System Admin within 2 seconds of availability confirmation |
| **PR18**            | The system must calculate the total cost of a booking based on<br>parameters (e.g., time, slot type, carpooling status) within 1 second<br>of receiving user inputs. |
| **PR19**            | Payment verification must be completed within 2 seconds, including<br>cross-checking with the payment gateway. |
| **PR20**            | The system must send booking confirmations or invoices via email<br>or platform notifications to users within 1 second of validation |
| **PR21**            | System logs must be accessible to the System Admin with filter<br>features (by date, action, type) within 3 seconds, even under high<br>load. |

_Table 3.2.3 : Performance Requirement for System Administration_


#### 3.2.4 System Monitor..............................................................................................

| Performance Req No. | Description                                                                                                |
| :------------------ | :--------------------------------------------------------------------------------------------------------- |
| **PR22**            | The System Monitor must receive, process, and validate incoming<br>parking data feeds within 1 second of input. |
| **PR23**            | The System Monitor needs to detect significant data changes and<br>verify updates internally within 2 seconds. |
| **PR24**            | The System Monitor must approve or reject parking booking<br>requests after validation within 1 second of review completion. |
| **PR25**            | The System Monitor must update the Parking Database with slot<br>availability changes within 1 second of verification. |
| **PR26**            | Notifications for exceptional events (i.e., parking full, sensor faults)<br>must be delivered to the System Administrator within 1 second of<br>event detection. |
| **PR27**            | For concurrent streams of data from up to X parking zones, the<br>System Monitor must complete processing and updating the<br>databases within 2 seconds for each area. |

_Table 3.2.4 : Performance Requirement for System Monitor_


### 3.3 Usability Requirements...........................................................................................

The system shall be user-friendly and easy to navigate for all types of users, including admins,
users, and system monitors. All buttons, fields, and menus should have clear labels and instructions,
and the interface should be simple and easy to use. To guarantee usability across platforms, the system
needs to be responsive and available on desktop and mobile devices. After completing tasks like
making requests, altering data, or getting approvals, users ought to get prompt response or
confirmation messages. The system should minimize human input by providing features like
dropdown menus and auto-fill where appropriate in order to lessen user effort. When mistakes occur,
the system must provide concise, informative notifications together with easy-to-follow instructions
on how to fix the problem. Additionally, the interface should follow basic accessibility standards to
support users with different needs, and overall system response time should not exceed 2 seconds to
ensure a smooth and efficient user experience.


### 3.4 Interface Requirements..........................................................................................

#### 3.4.1 External Interface...........................................................................................

This section defines the engagement of the system with external world entities, including
other software systems, users, hardware, and communication interface. This defines how the system
interacts with external services such as authentication systems and sensor networks, how the users
engage the system via different devices, and how data sharing is managed to deliver security,
accuracy, and reliability. All these interfaces are essential to facilitate seamless integration and
effective functioning of the system in its environment.

##### 3.4.1.1 System Interface...................................................................................

The system will interact with several other systems to provide smooth functionality. It will be
integrated into MMU's centralized authentication system to authenticate user credentials and provide
secure access to the system. The system will communicate with the Parking Management System
through well-documented APIs, providing real-time sharing of parking availability, booking status,
and updates. The system will also be integrated with digital identification verification services for user
identification validation during the ride-sharing and parking reservation operations. Cloud messaging
services will be utilized to offer timely notices and alerts to users and managers. The interfaces will be
in harmony with standard communication protocols and data forms to facilitate secure and strong data

#### transfer to all connected elements.

#### 3.4.1.2 User Interface

The system shall provide an intuitive and responsive interface accessible through both
desktop and mobile browsers. The interface will vary slightly depending on the role (User, Admin,
System Admin, System Monitor), ensuring role-based access and operations.

###### 3.4.1.2.1 General Layout............................................................................

```
● The main layout will include a dashboard , navigation panel , main content area , and notifications section.
● Consistent color themes and clear typography will be used for readability.
● Responsive design will adjust layout and components according to screen size.
```

###### 3.4.1.2.2 Interfaces per Role.......................................................................

**User Interface**

● **Login/Register Page** – Standard fields for authentication.

● **Dashboard** – Displays current ride bookings, payment status, notifications.

● **Carpool Module** – Form for creating/joining carpools, viewing carpool status.

● **Parking Slot Booking** – Real-time availability map and reservation form.

● **Payment Page** – Displays booking summary and allows secure payment.

● **Feedback Form** – Allows users to submit ratings and comments.

**Admin Interface**

● **Login Page** – Admin authentication.

● **User Management** – Table view with update/edit capabilities.

● **Carpool Review Page** – View carpool request details, approve/reject.

● **Booking Update Module** – Edit booking data, view logs.

● **Feedback Viewer** – Sorted user feedback with filtering.

**System Admin Interface**

● **Dashboard** – Summary of system operations and alerts.

● **Status Update Panel** – Allows editing and notifying booking/payment statuses.

● **Parking Slot Viewer** – Displays current availability and controls updates.

● **Cost Calculator Tool** – Display of calculated booking cost.

● **Payment Verification** – Secure connection to payment gateway and transaction log.

● **Invoice Notification System** – Sends and views notification records.

● **System Log Monitor** – Filterable logs by date, status, or module.

**System Monitor Interface**

● **Live Feed Dashboard** – Monitors real-time data from parking zones.

● **Anomaly Detection Alerts** – Notification section for faults or full lots.

● **Database Update Panel** – Displays most recent updates to slot data.


##### 3.4.1.3 Hardware Interface...............................................................................

The Campus Ride-Sharing Platform will operate on standard user devices such as desktops,
laptops, and smartphones with internet access and modern browsers. The system’s backend will be
hosted on a secure server infrastructure with at least an 8-core CPU, 16 GB RAM, SSD storage, and a
stable network interface to support real-time processing and database access. For parking
management, the system will integrate with IoT-based parking sensors installed at physical parking
zones, capable of detecting vehicle presence using ultrasonic or infrared technology. These sensors
will transmit real-time data to the system monitor via Wi-Fi or LTE protocols. Additionally, the
system will interface with external notification services such as email and SMS gateways for
delivering confirmations and alerts to users and administrators.

##### 3.4.1.4 Software Interface.................................................................................

Table 3.4.1.4 **s** hows the software interfaces through which the users can make use of the
platform. These interfaces facilitate the communication between the user interface, backend systems,
authentication services, and third-party tools like payment gateways and notification services. They
make sure everything is interacting appropriately across different parts.

| Interface Name               | Description                                                                                                |
| :--------------------------- | :--------------------------------------------------------------------------------------------------------- |
| **Web Frontend**             | The system provides a responsive web-based user interface built with<br>HTML5, CSS3, JavaScript, and frameworks like Bootstrap or React. |
| **Backend Server**           | Handles logic and data processing. Built on PHP, Node.js, or Python<br>frameworks. Communicates with the database and API layers. |
| **MMU Authentication System**| Integrates with MMU's Single Sign-On (SSO) or OAuth2<br>authentication system to verify user credentials securely. |
| **Parking Management API**   | Interfaces with the real-time parking availability system to fetch data<br>and confirm reservations. |
| **RESTful API Layer**        | All actions such as ride creation, joining, profile updates, and booking<br>are handled via RESTful APIs using JSON over HTTPS. |
| **Payment Gateway API**      | Supports secure transactions via FPX, Stripe, or other PCI-compliant<br>APIs. Processes parking and ride payments. |
| **Notification Service**     | Connects to cloud messaging services or SMTP for email/SMS alerts<br>about booking confirmations, ride status, or feedback requests. |
| **Validation & Error Handling** | Both client-side (JavaScript) and server-side (backend scripts)<br>validation ensure clean, accurate data input and error messages for<br>user guidance. |

_Table 3.4.1.4: Software Interface Requirements for User_


##### 3.4.1.5 Communication Interface......................................................................

Table 3.4.1.5 defines the communication interfaces that handle the data transfer between the
user and internal/external systems. These comprise secure protocols, API communications, session
management, and messaging services for facilitating real-time updates, confirmations, and
notifications necessary for an error-free user experience.

| Interface Name                   | Description                                                                                                |
| :------------------------------- | :--------------------------------------------------------------------------------------------------------- |
| **HTTPS Protocol**               | All user-to-server communications use HTTPS encryption to protect<br>sensitive data like credentials and payment info. |
| **MMU Authentication API**       | Facilitates login and logout requests through a secure OAuth2 or<br>SAML-based Single Sign-On (SSO) service. |
| **RESTful Communication API**    | User actions are sent via RESTful API endpoints using JSON. These<br>include login, profile updates, bookings, and feedback submissions. |
| **SMTP/Email API**               | The platform communicates via email for confirmations, feedback<br>requests, and announcements using an SMTP or email API service. |
| **Cloud Messaging (e.g., Firebase)** | Enables real-time notifications (e.g., booking status, chat requests) to be<br>sent directly to user devices or browsers. |
| **Payment Gateway Channel**      | Secure payment data is sent to a third-party provider, and responses<br>(success/failure) are received and processed immediately. |
| **Session Tokens/Cookies**       | User sessions are managed using encrypted tokens or cookies to track<br>activity securely during active periods. |
| **Error & Status Feedback Protocol** | In case of failed communication (e.g., timeouts, denied requests), the<br>system returns detailed status codes and messages for user and<br>debugging. |

_Table 3.4.1.5: Communication Interface Requirements for User_


### 3.5 Logical Database Requirements.............................................................................

```
Figure 3.5: Logical Database Requirements (Class Diagram)
```

The UML class diagram for the Campus Ride-Sharing Platform With Parking System Integration models the core entities and relationships required
for a seamless ride-sharing experience with mandatory parking reservations. At the foundation lies the abstract class UserAccount, which is inherited by four
concrete user roles: User, Admin, SystemAdmin, and SystemMonitor. Each User can create or join multiple CarpoolGroups, submit CarpoolRequests, and
make Bookings for rides. Every Booking is tightly coupled with a ParkingReservation and a Payment, forming a composition relationship since these entities
cannot exist independently once a booking is made. The ParkingReservation is linked to a ParkingSpot, ensuring that a specific location is secured.

Payments are processed through the Payment class and result in the generation of an Invoice. Users can also provide Feedback after each completed
ride, and each Booking is associated with one such feedback entry. Additionally, Notifications are sent to users regarding system updates, carpool approvals,
and reminders, reflecting a one-to-many association between UserAccount and Notification. Admin manages approvals for carpool requests and parking
reservations, while the SystemAdmin oversees platform-level verifications and payment audits. The SystemMonitor continuously observes Transactions and
user activities to ensure transparency and integrity. Dependencies are modeled between classes like Admin and CarpoolRequest, and between Booking and
CarpoolGroup, signifying temporary usage without strong ownership.


### 3.6 Design Constraints.............................................................................................................

#### 3.6.1 User Interface Constraints.............................................................................

```
● The system should be designed in such a way that focuses on the user's needs and preferences first. It should be easily accessible by all users including users with disabilities.
● The system should have consistent design elements like colors, typography and layout helps users to navigate properly and also enhances the system authority.
● The system should focus on delivering real value to users by making tasks easier, more efficient, or more enjoyable. The design's advantages ought to be obvious, significant, and consistent with user expectations.
```
#### 3.6.2 Hardware Constraints....................................................................................

The system should operate on general-purpose hardware devices without requiring specialized
or high-end infrastructure. The following are the hardware constraints:

1. Client-Side Devices

● The system should be available on typical user devices such as:

    ○ Smartphones and Tablets (iOS and Android)
    ○ Laptops and Desktops (Windows, macOS, or Linux)

● They ought to support a modern web browser and constant internet connectivity.

● Minimum device requirements:

    ○ 2 GB RAM
    ○ Dual-core processor
    ○ 720p screen resolution

2. Server Infrastructure

● The backend infrastructure will be run on a centralized server or cloud environment with a
    minimum:

       ○ Quad-core CPU (2.4 GHz and above)
       ○ 16 GB RAM
       ○ 100 GB SSD storage
       ○ Reliable internet connection with 1 Gbps bandwidth

● Secure access through HTTPS is required of the server and should provide continuous uptime
for 24/7 availability.

3. Administrative Terminals

● Admins and system monitors will connect to the system using standard office desktop or
    laptop computers.

● Recommended specs:

    ○ Minimum 4 GB RAM
    ○ Full HD (1920×1080) screen
    ○ Wired or wireless internet connection

#### 3.6.3 Software Constraints.....................................................................................

The system must follow specific software-specific limitations and dependencies for the sake
of compatibility, maintainability, and security:

● Operating System Compatibility: The server environment must be able to host Linux (Ubuntu
20.04 or later) or Windows Server 2019/2022 for backend deployment.

● Database System: The platform will utilize PostgreSQL or MySQL as the relational database
system. Limitations include schema compatibility, ACID compliance, and secure user
authentication support.

● Browser Compatibility: Front-end must be compatible with the latest major versions of
popular browsers (Chrome, Firefox, Safari, Edge) and mobile-access responsive design.

● Third-party Integrations: Integrations to MMU's Central Authentication System, Parking
Management APIs, and cloud messaging services must follow their respective SDKs,
endpoints, and security protocols.

● Development Frameworks:
```
I. Backend: Django or Express.js (final stack dependent).

II. Frontend: React.js or Vue.js.

III. All frameworks and libraries must be properly maintained and must use the MIT,
Apache 2.0, or GPL licenses.
```
● Security Standards: The system must use OWASP Top 10 security standards to prevent SQL
injection, XSS, and CSRF attacks.


#### 3.6.4 Communication Constraints...........................................................................

The system must enable secure connection between users and the server by implementing
HTTPS protocols. Internally, RESTful APIs with JSON formatting will be used to standardize
communication across components such as System Admin, Monitor, and Payment Gateway. Real-time
status updates must be transmitted with a latency of no more than one second. In the event of message
delivery problems (e.g., email or notification difficulties), the system must contain a retry mechanism
to ensure vital messages are received.

#### 3.6.5 Data Management Constraints......................................................................

The system will use a centralized relational database, such as MySQL or PostgreSQL, with
ACID compliance to ensure data consistency. All system records, including bookings, payments, and
logs, must be time stamped and kept safe. To avoid data loss, automated database backups will be
performed on a daily basis. Access to sensitive data will be restricted using role-based access control
(RBAC), and all communications and failures will be recorded in a separate module for monitoring
and debugging.

#### 3.6.6 Memory Constraints.......................................................................................

Memory limitations describe limits relating to how much data can be stored or processed by a
system/user via their runtime. Memory limitations will help manage the performance of devices via
student and staff use.

● The client-side application (browser) should run efficiently utilizing only 512 MB of available
system memory to support low-end student laptops or mobile devices.

● Caching commonly used information (such as user profile, carpool list, parking slot status) on
the frontend, using the browser's local/session storage, should limit caching of any single item
to 10 MB to maintain storage within each browser's memory limitations.

● Backend operations, for each user (such as login session, form submission, booking update)
must be memory allocated no more than 256 MB for each request on the server every user
consumes in a request must stay within 256 MB of memory allocation.

● For any uploaded files (for example, profile picture or documents if we allow this in a future
iteration) should have a restriction in size to 5 MB each file.


#### 3.6.7 Operational Constraints.................................................................................

Operational constraints establish the parameters in which the user side of the platform must be
able to operate effectively and reliably.

● The system must be available via modern web browsers (the latest versions of Chrome,
Firefox, Safari, or Edge), with JavaScript enabled.

● A user must have internet access (minimum 1 Mbps) at the time of the interaction for
successful interaction with real-time modules, including parking availability and chat.

● The system must be available 24 hours a day, 7 days a week, with reception windows (if
available) in place, and must notify users through email or on-site message at a minimum of
24 hours before any closure.

● The system must allow for multiple users to log in from different devices at the same time,
but restrict duplicate actions (e.g. booking) from multiple different sessions of the same user
account to avoid conflict.

● Sessions will timeout after 15 minutes of inactivity, but all user accounts must receive a
warning before they timeout and they must re-authenticate to access user accounts, for
security reasons.


### 3.7 Software System Attributes....................................................................................

#### 3.7.1 Reliability.......................................................................................................

The system shall operate consistently and perform its intended functions under defined
conditions without failure. It should be able to seamlessly recover from unforeseen problems and
manage several user requests without crashing. To guarantee system dependability, regular
testing—including unit, integration, and system testing—must be carried out. If something goes
wrong, the system should record it and alert the administrator so that it may be fixed right away.

#### 3.7.2 Availability......................................................................................................

The system will be accessible around-the-clock with the exception of planned maintenance
times. It should be built to reduce downtime and guarantee consumers' constant access. The system
must preserve user data integrity and deliver the proper messages in the event of a server or network
failure. Implementing system monitoring tools will guarantee high availability and prompt problem
identification.

#### 3.7.3 Security..........................................................................................................

The system prioritizes security by utilizing MMU's centralized authentication for secure and
role-based logins and access control to restrict functions based on roles. Data transmissions are
protected by HTTPS, and sensitive data are securely stored using encryption. Input validation helps to
avoid attacks such as SQL injection, XSS, and CSRF. The platform is also integrated with MMU's
digital ID verification systems for user authentication. Activity logs and real-time alerts enable
monitoring and quick response to suspicious activities, ensuring compliance with data protection
regulations like PDPA.


#### 3.7.4 Maintainability................................................................................................

The system will be created with maintainability in mind, ensuring that future changes,
enhancements, and bug repairs may be completed effectively. It will employ a modular architecture in
which each component (such as the booking system, notification service, payment gateway, and user
administration) is loosely connected and well-documented. This enables developers to isolate and
resolve bugs without disrupting other modules.

Consistent naming conventions, extensive inline documentation, and devotion to best
procedures (e.g., SOLID principles) shall be observed across the project. A version control system
(Git) will be utilized for tracking source code modifications and enable rollbacks to stable versions as
needed. Logs will be centralized and available to administrators, allowing for more effective
troubleshooting and performance monitoring. Configuration parameters (such as database credentials
and API keys) will be saved independently from the code to allow for easy updates without requiring
code modifications. Maintenance processes and apprised schedules will be detailed for administrators.

#### 3.7.5 Portability.......................................................................................................

The system should be able to run across platforms and environments with little changes. The
system should operate on any OS (windows – linux) that they choose and a variety of web browsers
(chrome, firefox, edge, etc.). The application should have the ability to transition to a different
platform in the future (mobile, cloud, etc). Documentation and modular code should allow for easy
migration and reconfiguration to facilitate reuse and lessen the effort to "move" the system to a new
environment.


### 3.8 Supporting Information...........................................................................................

#### 3.8.1 Campus Ride-Sharing Platform Survey form.................................................

As part of the data collection process for the Campus Ride-Sharing Platform with Parking
System Integration project, a survey consisting of eight questions was distributed to university
students to better understand their commuting habits. A total of **20 respondents** participated in the
survey.

Figure 3.8.1.1 shows one of the key questions asked was, _"How often do you drive to
campus?"_ The responses showed a diverse range of driving frequencies. Notably, **6 out of 20
respondents (30%) drive to campus daily** , while **5 respondents (25%) drive a few times a week**.
Additionally, **4 respondents (20%) drive once a week** , whereas **5 respondents (25%) rarely or
never drive to campus**. These findings suggest that a significant portion of the campus population
does commute by car regularly, highlighting the relevance and potential impact of a ride-sharing
platform integrated with parking management, particularly for those who travel frequently and may
benefit from more organized and efficient parking and carpooling options.
_Figure 3.8.1.1: Result of How Often Do You Drive to Campus Survey_


Figure 3.8.1.2 shows the current commuting methods of 20 respondents. **45%** use **personal
vehicles** , making it the most common option. **Public transportation** is used by **20%** , followed by
**ride-hailing apps** like Grab ( **15%** ). **Carpooling** and **walking/biking** are the least common, each with
**10%**. These results highlight a strong dependence on private vehicles, indicating the potential benefit
of a campus ride-sharing and parking system.

_Figure 3.8.1.2: Result of What is Your Current Method of Commuting to Campus Survey_
Figure 3.1.8.3 illustrates user satisfaction with current campus parking availability, based on a
scale of 1 (very satisfied) to 5 (very dissatisfied). Out of 20 respondents, **35% rated 5** , showing
strong dissatisfaction. **35% rated 3** as neutral response, **15% rated 4** indicating moderate
dissatisfaction, while only **15% rated 1 or 2** , reflecting moderate satisfaction. These results suggest
that most users are unhappy with the current parking situation, supporting the need for a
better-managed parking and ride-sharing system.
_Figure 3.8.1.3: Result of How Satisfied Are You With The Current Availability of Parking Spaces in
Campus Survey_


Figure 3.8.1.4 illustrates the respondents’ likelihood of using the university’s parking
reservation system that requires mandatory carpooling. Based on the responses from 20 individuals,
**50%** indicated they are very likely to use the system, reflecting strong interest in the proposed
solution. Meanwhile, **25%** of respondents remained neutral, and **10%** reported being somewhat likely
to use it. On the other hand, **15%** expressed that they are very unlikely to adopt the system. Overall,
the data suggests a generally positive outlook, with the majority of participants showing a willingness
to engage with a carpool-based parking reservation approach.

_Figure 3.8.1.4: Result of How Likely Are You to Use The University’s Parking Reservation System
That Requires Mandatory Carpooling Survey_

Figure 3.8.1.5 illustrates the incentives that would motivate the respondents to carpool. In 20
people's responses, "Saving on parking fees" and "Parking spots available only for carpools" were the
strongest incentives with 14 respondents (70%) and 13 respondents (65%) respectively. Followed
closely by 13 respondents (65%), the "Convenience of ride-sharing" was an incentive. "Environmental
concerns" and "Social interaction" were also important drivers, both of which were captured by 12
participants (60%). As a whole, the findings suggest that financial incentives and specialist
infrastructure, with convenience and social/environmental factors, are essential drivers for the take-up
of carpooling amongst the study group.

_Figure 3.8.1.5: Result of What factors would encourage you to participate in carpooling_

Figure 3.8.1.6 illustrates the opinions of the respondents in regard to the need to form or join a
carpool group before being allowed to reserve a parking spot. Out of 20 answers collected, there was a
wide variety of opinions, with the majority of individual opinions held by only one of the respondents,
representing 5% of all respondents. The most frequently observed individual opinion was "Mmu
student" and was recorded by 2 respondents (10%). The other miscellaneous 5% of the responses
were "Reduces congestion.", "Good initiative", "Have fees", "I do think that it could help in
optimizing the parking space", "Must be mmu students", "Sounds fair", "Very good", and one that was
an opinion concerning promoting sustainability and utilization of parking space to its best. The
diversity and scattered nature of the above answers indicate that there is no common opinion on
making the compulsory carpooling condition mandatory for booking parking space.

_Figure 3.8.1.6: Result of What do you think about the requirement to form or join a carpool group
before being allowed to reserved parking spot_


Figure 3.8.1.7 illustrates the issues respondents anticipate when having to use a ride-sharing
system. Out of 20 responses, a number of potential issues were enumerated, running the gamut from
logistical to interpersonal, safety, and technical concerns. Respondents suggested some locations
would lack sufficient choices for ride-sharing, which could compromise dependence upon the system
when necessary, and also mentioned the necessity of coping with others. Safety-related issues were
brought up as significant concerns, where users may feel uneasy or insecure with strangers and the
threat of "Sexual Assault" was even brought up in so many words. Logistical concerns included
"Scheduling Conflicts," where the riders might have different pickup times or be stuck waiting, and
general "Reliability" issues like cancellations of drivers or passengers at the last minute. Furthermore,
"Technical Glitches" like app bugs, GPS failures, or booking errors were also expected as disruptions
to the experience, and the system was viewed as potentially time-consuming. Overall, the responses
indicate that users anticipate a broad range of issues, from functional operation difficulties to critical
safety and comfort issues, when considering the use of a ride-sharing system

_Figure 3.8.1.7: Result of What challenges do you foresee when using ride sharing system_


Figure 3.8.1.9 presents the features that would significantly increase respondents' likelihood
of using a parking reservation system with ride-sharing, as stated by 20 responses. The top feature was
"Real-time availability updates," chosen by 16 respondents (80%), followed by an "Easy-to-use
mobile app," the "Ability to choose carpool riders," and "Integration with class schedules" as equally
important, each chosen by 14 respondents (70%). In addition, "Guaranteed parking spots for
carpoolers" was wished for by 13 individuals (65%), and "Incentives (e.g., discount, reward points)"
were wished for by 11 individuals (55%). In total, the data indicate that transparency, simplicity of
use, freedom over carpooling plans, and assured parking benefits are core to motivating use of such a
system.

_Figure 3.8.1.8: Result of What features would make you more likely to use a parking reservation
system with ride-sharing_


#### 3.8.2 Brainstorming.................................................................................................

Brainstorming meetings for the Campus Ride-Sharing Platform were held with a diverse
group of participants, including students (possible users), system administrators, admin and system
monitoring staff. These sessions sought to identify major areas in current campus transportation,
desirable features, and potential improvements towards parking and carpool services.

During brainstorming, participants highlighted:

● The need for a real-time parking slot display system.

● A simple way for users to create or join carpool groups.

● Automated cost calculation for rides based on duration and group size.

● Instant notifications and invoice delivery post-booking or payment.

● Admin-side monitoring tools for logs, availability, and approvals.

#### Benefits & Limitation

**Benefits:**

● **Better Parking Use**

Live updates g the amount of available space bald lot limits dangerous driving, angry
frustration, and overuse of space.

● **Cost and Resource Sharing**

Carpooling not only reduces costs to the individual, it services the greater good of our
environment.

● **Simplified Communication**

Instant notifications and invoices inform users of parked cars and receiver hybrid
business communication.

● **Monitor Tools for Admins**

Monitor tools for admins provide important info on the hybrid infrastructure and
fixed systems, while also having the ability to clarify issues easily while enforcing
app rules fairly.


● **Building an Ideal Community**

Carpooling helps build cooperation and connection between students and staff.
They're a part of your higher education system building, or a useful slant to your
scheme.

**Limitation:

● User Engagement**

It is important for the system to depend on user engagement, most importantly for
carpooling.

**● Scheduling Conflicts**

Scheduling conflicts are challenges users will experience when trying to arrange ride
times with those they are meeting, limiting pool viability.

**● Privacy/Safety Concerns**

Accepting rides from unknown individuals may lead to personal safety friction or
issues of comfort.

**● Technology Access**

Users may be unfamiliar with devices or applications, or may also lack most access to
the web, leading to challenges on the platform.

**● Technical Issues/Errors**

Technical issues may occur at various times affecting notifications, payments, or
bookings, which only leads to distrust.


#### 3.8.3 Existing System.............................................................................................

The dashboard in the YourParkingSpace system provides a broad view for users operating
parking bookings across the UK. With this dashboard, users can view real-time availability of parking
spaces, upcoming bookings, and parking history in selected timeframes. The interface also gives
access to user accounts, payment summaries, as well as personalized recommendations from favorite
parking spots. A sidebar menu allows drivers to transition smoothly from the whole
process—searching and reserving a space, managing vehicle data, and looking at history—to a
complete end-to-end parking experience.

_Figure 3.8.3.1: User Dashboard

Figure 3.8.3.2: User Registration Form_


_Figure 3.8.3.3: Parking Cost Calculator

Figure 3.8.3.4: Notifications Steps_


### 3.9 Apportioning of Requirements................................................................................

**1. User Module**

    ● Requirement 1: The system must authenticate users and load the dashboard within 2 seconds after successful login.
    ● Requirement 2: Users must be able to fill and submit their personal and ride-related information with confirmation received within 3 seconds.
    ● Requirement 3: Users must be able to create a carpool group, and the request should be submitted and acknowledged by the system within 4 seconds.
    ● Requirement 4: When joining a carpool group, the system should check for availability and respond within 3 seconds.
    ● Requirement 5: Users must be able to view and reserve available parking slots, and get confirmation within 3 seconds.
    ● Requirement 6: Payment processing should be completed and confirmation shown to the user within 5 seconds.
    ● Requirement 7: Feedback submitted by the user should be stored and confirmation displayed within 2 seconds.

**2. Admin Module**

    ● Requirement 1: Able to update and store users’ data such as name, contact information, and status.
    ● Requirement 2: Can review user-submitted carpool requests, including requester details, date, time, pickup, and drop-off locations.
    ● Requirement 3: Able to validate ride details submitted by users to ensure completeness and accuracy before approval.
    ● Requirement 4: Able to approve or reject carpool requests based on submitted ride details.
    ● Requirement 5: Able to receive and view parking approval requests linked to carpool bookings.
    ● Requirement 6: Able to update booking details and securely store them in the database.
    ● Requirement 7: Able to review user comments or feedback and store them for future reference.


**3. System Administration**

    ● Requirement 1: Able to update a user's status (booking, payment, approval) and trigger notifications within 2 seconds of initiating the action.
    ● Requirement 2: Able to retrieve and view real-time slot availability data within 1 second of request, assuming a responsive database.
    ● Requirement 3: Ensure that users see the updated list of slots within 2 seconds after availability is confirmed.
    ● Requirement 4: System must calculate the total cost of a booking (based on parameters like time, slot type, carpooling status) within 1 second of receiving inputs.
    ● Requirement 5: Payment verification must be completed within 2 seconds, including cross-checking with the payment gateway.
    ● Requirement 6: System must send booking confirmations or invoices via email or platform notifications to users within 1 second of validation.
    ● Requirement 7 Able to access system logs with filter features (by date, action, type) within 3 seconds, even under high load.

**4. System Monitor**

    ● Requirement 1: Must receive, process, and validate incoming parking data feeds within 1 second of input.
    ● Requirement 2: Must detect significant data changes and verify updates internally within 2 seconds.
    ● Requirement 3: Must update the Parking Database with slot availability changes within 1 second of verification.
    ● Requirement 4: Must deliver notifications for exceptional events (parking full, sensor faults) to the System Administrator within 1 second of event detection.
    ● Requirement 5: Must process concurrent data streams from up to X parking zones and update the databases within 2 seconds per zone.


### 3.10 Specified Requirements........................................................................................

This section describes the specific functional requirements and non-functional requirements for the
Campus Ride-Sharing Platform with Parking System Integration. These requirements will establish
the basis for the development of the system and make sure that all stakeholders have a shared, clear
understanding of what the system has to do.

**Functional Requirements:**

**1. User Account Management**

● Users will be able to register, log in, and modify their profile using MMU credentials.

● The system will validate a user’s identity using the University's SSO system.

**2. Carpool**

● Users will be able to create a carpool group, by entering the route, time, and vehicle.

● Users will be able to search and join an existing carpool, subject to spot availability.

● Administrators must approve or reject carpool requests before they are deemed active.

**3. Parking Reservation**

● Only users belonging to an approved carpool group will be able to reserve parking spots.

● Parking slots availability must be shown in real time, and updated in real time.

**4. Payment Integration**

● The system must support online payment for all parking and carpool related fees via FPX or equivalent.

● Payment status must be verified and recorded prior to confirmation of booking.

**5. Feedback and Notifications**

● Users will be able to submit feedback and assess their ride experiences.

● The system will send notifications for requests, updates, and confirmations in real-time.


**Non-Functional Requirements:**

**1. Performance**

● The primary functionality for the system (login, booking, payment) will perform in <2–5 seconds.

● The system will be able to accommodate many users simultaneously with no reduction in service.

**2. Security**

● All data will be sent securely using HTTPS.

● Role-based Access Control (RBAC) will be provided for each user type.

**3. Usability**

● The system will be easy to use and provide a fully responsive UI for desktop and mobile devices.

● Users will be provided feedback, confirmation, and error messages where applicable during their interaction.

**4. Maintainability**

● The system will be modular and will allow for changes with minimal downtime.

**5. Portability**

● The application will run on all major browser platforms and will deploy on standard IT infrastructure that a university provides.


## 4 Verification.....................................................................................................................

### 4.1 Verification Approach..............................................................................................

A systematic verification process will be used to make sure the Campus Ride-Sharing
Platform With Parking System Integration satisfies all functional and non-functional requirements.
This comprises several testing tiers at various phases of development, each of which is mapped to
distinct system components.

**How** :

Verification will be conducted using the following methods:

● **Unit Testing:** Each class (Booking, CarpoolGroup, ParkingReservation, Payment,
Notification) will be individually tested to verify logic correctness, particularly with regard to
relationships like composition and dependency.

● **Integration Testing:** Interactions between modules (ebooking with parking, payment with
invoice, user with carpool creation) will be tested to ensure that communication between
classes works as expected.

● **System Testing:** Full end-to-end scenarios, such as “Reserving a Parking Spot with Carpool
Creation” or “Joining Existing Carpool and Completing a Ride,” will be tested against the
scenario flows.

● **Functional Testing:** All use cases will be tested, including user login, admin approval,
payment handling, and notification delivery.

● **Validation Against UML Design:** Verification will also ensure that the final implementation
remains aligned with the class diagram and system design artifacts.


**Who:**

Verification responsibilities are divided as follows:

● **Development Team:** Responsible for unit and integration testing throughout the development
process.

● **QA/Test Team:** In charge of functional and system-level testing, particularly on staging
environments.

● **System Administration Team:** Will verify backend logs, monitor real-time parking data
flows, and validate payment security.

● **Admin and System Monitor Roles:** Participate in verification for request approval flows,
feedback flagging, and system event logging.

**When:**

Verification will occur in iterative stages:

● **After Each Sprint:** Unit and integration tests will be run at the end of every sprint cycle.

● **After Major Features Are Built:** Once features like booking, payment, and parking modules are complete, full system tests will be executed.

● **Before Deployment:** Complete system verification will be performed before staging and final production deployment.

**Where:**

Verification activities will take place in:

● **Local Development Environments:** For unit and initial integration tests.

● **QA Testing Environment (Staging Server):** For full system and functional testing.

● **Monitoring Dashboards:** For live verification and backend performance assessment after deployment.


### 4.2 Verification Criteria................................................................................................

● **Login & Authentication:**

The system must verify user identity through university ID and password. Unauthenticated
users must be denied access.

● **Carpool Creation & Request:**

A carpool group must not be created unless at least one other participant has been invited.
Join requests must be reviewed and approved by the carpool creator or admin within 24 hours.

● **Parking Reservation:**

Parking reservation should only be enabled after a carpool is approved. The system must
check real-time slot availability before confirming.

● **Ride-Matching Algorithm:**

The system must assign drivers to riders within 10 seconds after carpool and parking
approval.

● **Booking Confirmation:**

The system must send a confirmation notification (email and in-app) within 5 seconds of
booking approval.

● **Payment Processing:**

Payment must be processed securely via a simulated payment gateway, with a success/failure
response within 5 seconds. A transaction ID must be generated for each successful booking.

● **Response Time:**

All user actions (e.g., searching carpools, booking ride, loading parking zones) should
complete in under 3 seconds under normal server load.

● **Admin Actions:**

Admin should be able to view, approve, or reject any booking or carpool request in under 5
seconds.

● **System Monitoring:**

Parking availability must update in real time every 30 seconds, monitored and refreshed by
the System Monitor module.

● **Error Handling:**

If any component fails (ride matching or payment), an error log should be generated and a
notification must be sent to System Administration within 1 minute.

● **Feedback Submission:**

Users must be able to submit ride feedback after marking the ride as “Completed,” and the
data should be saved and viewable in the system.


## 5 Appendices..................................................................................................................

### 5.1 Assumptions and Dependencies..........................................................................

#### 5.1.1 Assumptions................................................................................................

**1. Stable Internet Connection:**

    It is assumed that users and system components have consistent internet access for real-time
    operations.

**2. University Authentication Integration:**

    All users (students, staff, admin) are assumed to log in using valid MMU university
    credentials.

**3. Accurate Real-time Data Feeds:**

    It is assumed that the parking data feed and user booking information are accurate and
    updated in real time.

**4. Payment Gateway Availability:**

    The third-party payment gateway service is assumed to be operational and capable of
    processing transactions securely and efficiently.

**5. Email/SMS Notifications:**

    The system assumes the availability of a functioning notification system (e.g., SMTP or
    messaging API) to send booking confirmations or status updates.

**6. Database Integrity:**

    It is assumed that the database remains consistent, with valid data models and properly
    indexed tables for efficiency.

**7. Logging and Monitoring System:**

    The logging system is assumed to be operational and capable of tracking all backend actions
    for security and audit purpose


#### 5.1.2 Dependencies..............................................................................................

**1. University Authentication Server:**

    The platform depends on MMU’s identity management system for login and authentication.

**2. Real-Time Parking Feed System:**

    The availability and accuracy of parking slots rely on the data provided by sensors or manual
    updates from system monitors.

**3. Third-party Payment Gateway:**

    The system relies on an external payment gateway (e.g., FPX, Stripe, etc.) for processing and
    verifying user payments.

**4. Email/SMS Notification Service:**

    Notifications (like booking confirmations, status updates) depend on third-party services or
    university APIs.

**5. Web Hosting & Server Infrastructure:**

    The system is dependent on reliable hosting infrastructure (e.g., AWS, university servers) for
    uptime and performance.

**6. Browser Compatibility:**

    Users depend on modern web browsers (Chrome, Firefox, Edge) to access the platform
    effectively.

**7. Database Management System:**

    The backend relies on a functioning and optimized DBMS (e.g., MySQL, PostgreSQL) to
    store and retrieve system data efficiently.


### 5.2 Acronyms and Abbreviations................................................................................

The table below contains a variety of acronyms and abbreviations that are included in this
Software Requirement Specification (SRS) document. The terms provided below are included to
suggest meaning, promote common understanding by all stakeholders and avoid the redundancy of
lengthy terms. Each term contains its full form and a short statement about its relevance to the system.


| Acronym/ Abbreviation | Full Form                          | Description                                                                                                |
| :-------------------- | :--------------------------------- | :--------------------------------------------------------------------------------------------------------- |
| SRS                   | Software Requirements Specification | A document that outlines the software system’s functional and non-functional requirements.                  |
| UI                    | User Interface                     | The interface through which users interact with the system.                                                |
| DB                    | Database                           | A structured collection of data stored and accessed electronically.                                         |
| SSO                   | Single Sign-On                     | An authentication process that allows a user to access multiple applications with one set of login credentials. |
| MMU                   | Multimedia University              | The institution for which the ride-sharing and parking platform is developed.                               |
| ID                    | Identification                     | A unique identifier used to authenticate or represent a user in the system.                                 |
| FPX                   | Financial Process Exchange         | A Malaysian online payment gateway system.                                                                  |
| SMTP                  | Simple Mail Transfer Protocol      | A protocol used for sending emails.                                                                         |
| API                   | Application Programming Interface  | A set of tools and definitions for building and interacting with software applications.                     |
| UX                    | User Experience                    | The overall experience a user has when interacting with the platform.                                       |
| OS                    | Operating System                   | System software that manages hardware and software resources.                                               |

_Table 5.2: Acronyms and Abbreviations_


