# Software Requirements

## 1. Problem Understanding

Many organizations and teams conduct meetings frequently, but they face difficulties in organizing meeting information, recording decisions, assigning tasks, and tracking task progress.

Meeting details may be stored in different places, which can cause loss of information, difficulty in following up on decisions, and delays in completing assigned tasks.

The system aims to provide a centralized platform for managing meetings, decisions, and related tasks.

---

# 2. Functional Requirements (FR)

## FR-01: User Registration

The system shall allow users to create a new account.

## FR-02: User Login

The system shall allow registered users to log in using their username/email and password.

## FR-03: User Management

The administrator shall be able to manage users and their roles.

## FR-04: Create Meeting

The user shall be able to create a new meeting with:

* Meeting title.
* Date and time.
* Location.
* Description.

## FR-05: Update Meeting Information

The user shall be able to modify meeting details.

## FR-06: Add Meeting Participants

The user shall be able to add participants to a meeting and define their roles.

## FR-07: Record Meeting Minutes

The system shall allow the user to write and save meeting minutes.

## FR-08: Add Decisions

The user shall be able to add decisions related to a specific meeting.

## FR-09: Create Tasks

The user shall be able to create tasks based on meeting decisions.

## FR-10: Assign Tasks

The user shall be able to assign tasks to specific users.

## FR-11: Track Task Status

The system shall allow users to update task status:

* Pending.
* In Progress.
* Completed.
* Delayed.

## FR-12: Generate Reports

The system shall allow users to view and generate reports about meetings, decisions, and tasks.

---

# 3. Non-Functional Requirements (NFR)

## NFR-01: Security

The system shall protect user passwords using secure hashing techniques.

## NFR-02: Performance

The system should provide fast response time during normal usage.

## NFR-03: Usability

The system interface should be simple and easy to use.

## NFR-04: Reliability

The system should maintain data consistency and prevent data loss.

## NFR-05: Authorization

Users shall only access features and data according to their permissions.

## NFR-06: Scalability

The system database and architecture should support future expansion.

---

# 4. User Requirements

## Administrator:

* Manage users.
* Manage permissions.
* Monitor system activities.

## Meeting Manager:

* Create meetings.
* Add participants.
* Record minutes.
* Add decisions.

## Team Member:

* View assigned tasks.
* Update task status.
* Follow meeting decisions.

---

# 5. System Constraints

* The system will be developed as a web application.
* The project duration is limited to the academic semester.
* The system depends on a database server.
* The system will use REST API communication between client and server.

---

# 6. Assumptions

* Users have valid accounts.
* Users enter correct meeting information.
* The database server is available during system operation.
* Users have internet/network access.

---

# 7. Main Project Goal

The goal of this project is to develop a web-based system that helps organizations manage meetings, record decisions, assign tasks, and monitor task completion in an organized and efficient way.
