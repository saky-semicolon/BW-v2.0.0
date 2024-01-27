
# Software Requirements Specification (SRS) for Better World Application

## 1. Introduction
### 1.1 Purpose
The purpose of this document is to define the software requirements for Better World, an application dedicated to promoting positive global impact aligned with the UN's 17 SDGs. It outlines the functionalities and constraints of the software system.The document should undergo constant updates to accurately capture any changes in requirements that occur during the implementation and utilization of the Better World. This ensures that an up-to-date baseline of the actual requirements is readily accessible at any given time.

### 1.2 Scope
The scope includes the entire Better World application, covering education, gamification, and social impact features, focusing on fostering a community dedicated to creating a better world.<br>
A list of all major features of the solution is given below:

<table border="1">
<thead>
<tr>
<th scope="col">Feature</th>
<th scope="col">Name</th>
<th scope="col">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="3"><strong>HR-manager</strong></td>
</tr>
<tr>
<td>FT-01</td>
<td><strong>User Management</strong></td>
<td>
<ol>
<li>Authorization/ Registration</li>
<li>Add User</li>
<li>View the list of Users</li>
<li>View User profile information</li>
<li>Edit User profile information</li>
<li>Delete User</li>
<li>Archive/ Unarchive User</li>
<li>Manage User’s rights</li>
<li>View User dashboard</li>
</ol>
</td>
</tr>
<tr>
<td>FT-02</td>
<td><strong>Administration</strong></td>
<td>
<ol>
<li>Create Company Organizational Structure</li>
<li>Create Skill Matrix</li>
</ol>
</td>
</tr>
<tr>
<td colspan="3"><strong>Learner</strong></td>
</tr>
<tr>
<td>FT-03</td>
<td><strong>Onboarding</strong></td>
<td>
<ol>
<li>Start/Stop/Skip/Complete System Onboarding</li>
<li>Start/Stop/Complete Company Onboarding</li>
</ol>
</td>
</tr>
<tr>
<td>FT-04</td>
<td><strong>Professional development</strong></td>
<td>
<ol>
<li>Add Skill&nbsp;</li>
<li>Set Deadline</li>
<li>Delete Skill</li>
<li>Archive Skill</li>
<li>View the Skill completion progress</li>
<li>View the list of Skills</li>
<li>View information about Skill</li>
<li>View the list of completed Skills</li>
<li>View the list of Interests (favorite Skills)</li>
<li>Search for Skills</li>
</ol>
</td>
</tr>
<tr>
<td>FT-05</td>
<td>
<p><strong>Course</strong></p>
<p><strong>(All Courses are stored in LMS)</strong></p>
</td>
<td>
<ol>
<li>Start the Cours</li>
<li>Stop/Continue passing the Course</li>
<li>Complete the Course</li>
</ol>
</td>
</tr>
<tr>
<td>FT-06</td>
<td><strong>Certificates</strong></td>
<td>
<ol>
<li>Upload the Certificate</li>
<li>View the list of Certificates</li>
</ol>
</td>
</tr>
<tr>
<td>FT-07</td>
<td><strong>Badges</strong></td>
<td>
<ol>
<li>Get Badges</li>
<li>View the list of Badges</li>
</ol>
</td>
</tr>
<tr>
<td>FT-08</td>
<td><strong>Events</strong></td>
<td>
<ol>
<li>View the list of Events</li>
<li>Create new Event</li>
<li>Edit Event</li>
<li>Delete Event</li>
</ol>
</td>
</tr>
<tr>
<td>FT-09</td>
<td><strong>Widget</strong></td>
<td>
<ol>
<li>Add new Widget</li>
<li>Hide widget</li>
</ol>
</td>
</tr>
<tr>
<td>FT-10</td>
<td><strong>Calendar</strong></td>
<td>
<ol>
<li>View upcoming Events</li>
</ol>
</td>
</tr>
<tr>
<td>FT-11</td>
<td><strong>Chat</strong></td>
<td>
<ol>
<li>Online chat with other Users</li>
<li>Online chat with the Support team</li>
<li>View the list of dialogues</li>
</ol>
</td>
</tr>
<tr>
<td>FT-12</td>
<td><strong>Notifications</strong></td>
<td>
<ol>
<li>Enable/Disable Notifications</li>
<li>View the list of Notifications</li>
</ol>
</td>
</tr>
<tr>
<td colspan="3"><strong>Mentor</strong></td>
</tr>
<tr>
<td>FT-13</td>
<td><strong>Professional development</strong></td>
<td>
<ol>
<li>Add Skill to Learner Professional development plan</li>
<li>Set Deadline</li>
<li>Create Skill package</li>
<li>Delete from Skill Professional development plan</li>
<li>View the Skill completion progress</li>
<li>View the list of Skills</li>
<li>View information about Skill</li>
<li>View Learner dashboard</li>
</ol>
</td>
</tr>
</tbody>
</table>

### 1.3 Definitions, Acronyms, and Abbreviations
This section lists and explains technical terms, abbreviations, or acronyms used throughout the document for clarity.
<table border="1">
<tr>
<th>Acronyms & Abbreviations</th>
</tr>
<tr>
<td>

- **API:** Application Programming Interface
- **SDGs:** Sustainable Development Goals
- **SRS:** Software Requirements Specification
- **UN:** United Nations
- **LMS:** Learning Management System
- **FT:** Feature
- **HR:** Human Resources
- **URL:** Uniform Resource Locator
- **GUI:** Graphical User Interface
- **FAQ:** Frequently Asked Questions
- **HTTPS:** Hypertext Transfer Protocol Secure
- **SSL:** Secure Sockets Layer
- **TLS:** Transport Layer Security
- **HTTP:** Hypertext Transfer Protocol
- **SMTP:** Simple Mail Transfer Protocol
- **FTP:** File Transfer Protocol</td>

</tr>
</table>


## 2. System Description
### 2.1 System Overview
Better World is an interactive platform offering modules, challenges, and a gamified learning experience centered on the 17 SDGs. It caters to users of various age groups, particularly students and lifelong learners passionate about social impact.

### 2.2 System Features
Features include user registration, educational content, challenges aligned with the SDGs, impact evaluation, and user interaction tools such as forums and leaderboards.

### 2.3 User Interfaces

### 2.4 Hardware Interfaces

### 2.5 Software Interfaces

### 2.6 Communications Interfaces

### 2.7 Memory Constraints

### 2.8 Operations


## 3. Functional Requirements
### 3.1 Use Cases
- **Use Case v1.0.0:** User Registration
  - **Description:** Allows users to create accounts.
  - **Actors:** New Users
  - **Preconditions:** None
  - **Postconditions:** User account is created.

### 3.2 User Stories
- **User Story 1:** As a new user, I want to register an account so that I can access Better World's features.

## 4. Non-Functional Requirements
### 4.1 Performance Requirements
- **Performance Requirement 1:** The application must load within 5 seconds.

### 4.2 Security Requirements
- **Security Requirement 1:** User data must be encrypted using industry-standard protocols.

### 4.3 Usability Requirements
- **Usability Requirement 1:** The application interface must be intuitive and user-friendly.

## 5. System Architecture
### 5.1 High-Level Architecture
The system architecture includes a multi-tiered setup, with a front-end developed using HTML, CSS, and JavaScript, interacting with a back-end built on Node.js and a MongoDB database.

## 6. User Interface
### 6.1 User Interface Design
Mockups and design principles emphasizing simplicity, interactivity, and accessibility for diverse user groups.

## 7. Data Management
### 7.1 Data Models
Database schema representing users, challenges, educational content, and user-generated contributions aligned with SDGs.

## 8. Testing Requirements
### 8.1 Testing Approach
A combination of unit testing, integration testing, and user acceptance testing to ensure functionality and usability.

## 9. Deployment
### 9.1 Deployment Strategy
Continuous deployment using CI/CD pipelines for staging and production environments hosted on cloud platforms for scalability.

## 10. Glossary
A glossary of terms used in the SRS for easy reference and understanding.
