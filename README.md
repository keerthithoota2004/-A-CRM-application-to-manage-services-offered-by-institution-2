# A CRM Application to manage services offered by institution

**EduConsultPro Institute** leverages Salesforce CRM to streamline the student journey from inquiry to enrollment, offering educational institutions a unified platform to manage courses, consultants, student data, appointments, and communications with efficiency and ease.

---

## Author
**Keerthi Thoota**  
Gayatri Vidya Parishad College of Engineering (Autonomous), Visakhapatnam  
Email: [21131a05q2@gvpce.ac.in](mailto:21131a05q2@gvpce.ac.in)

---

## Acknowledgments
This project would not have been possible without the support and guidance from:

- **Gayatri Vidya Parishad College of Engineering (A)**
- **Salesforce Development Team**
- **Project Mentors and Guides**

Thank you for the invaluable assistance throughout the development of this Salesforce CRM solution for EduConsultPro Institute.

---

## Project Summary
EduConsultPro Institute has adopted Salesforce CRM to effectively manage increasing applications, consulting requests, and immigration cases. This solution consolidates admissions, consulting, and immigration processes into a single platform, providing robust support across core institutional functions:

- **Student Enrollment Management:** Simplifies applications, course selections, registrations, and email notifications.
- **Appointment Coordination:** Streamlines consultant bookings, approvals, and calendar integration.
- **Immigration & Case Handling:** Manages student immigration support and visa tracking.
- **Course Oversight:** Tracks student registrations and provides a comprehensive course catalog.

---

## Core Capabilities

### Admissions & Enrollment
- **Streamlined Application Process:** Enables prospective students to apply online.
- **Course Selection & Registration:** Allows students to select courses during enrollment.
- **Automated Notifications:** Sends email updates for students and staff.
- **Student Profile Management:** Centralizes student data for easy access.

### Appointment Management
- **Consultant Booking:** Facilitates scheduling with available consultants.
- **Approval Automation:** Routes approvals through a manager-based workflow.
- **Automated Email Updates:** Keeps all parties informed at every stage.
- **Calendar Integration:** Synchronizes appointments with consultant availability.

### Case & Support Management
- **Immigration Services:** Manages immigration inquiries and support.
- **Visa Tracking:** Tracks visa applications and their status.
- **Support Ticketing System:** Manages student support requests and resolutions.

### Course Catalog & Enrollment Tracking
- **Course Listings:** Manages course offerings and information.
- **Registration Management:** Tracks student course registrations.
- **Enrollment Tracking:** Monitors student progress from registration to enrollment.

---

## Workflow Automation

### Process Flows
- **Admissions Flow:** Collects student info, processes course selection, registers students, and sends confirmation emails.
- **Booking Flow:** Manages student verification, consultant selection, appointment scheduling, and initiates approval workflows.
- **Master Flow:** Serves as a unified interface, guiding new and returning students to the appropriate processes.

### Approval Workflows
- **Appointment Approval:** Routes approvals to managers with automated email notifications for submission, approval, and rejection stages.

---

## Setup Guide

### Object Configuration
1. Import **Course**, **Consultant**, and **Student** objects and data.
2. Import **Appointment** object and set up relationships:
   - **Appointment ↔ Student**
   - **Appointment ↔ Consultant**
3. Create a **Registration** object for student/course data, including additional lookup relationships for immigration/visa cases.

### User Setup
1. Add users with the **Standard Platform User** profile.
2. Configure user hierarchies to support approval processes.

### Flow Implementation
1. Deploy the **Admissions Flow**.
2. Deploy the **Appointment Booking Flow**.
3. Deploy the **Master Flow** for an integrated process experience.

### Lightning App Configuration
1. Deploy the **EduConsultPro Lightning App**.
2. Configure home page layouts for optimal usability.
3. Assign user permissions for app access.

### Case Object Settings
- **Case Type Options:** Immigration, Visa Application
- **Case Status Options:** Open, In-Progress, Closed

---

## Process Overview

### Admissions Workflow
1. **Student Application:** Student fills out the admission form and selects desired courses.
2. **Record Creation:** The system automatically creates a registration record.
3. **Confirmation Notification:** A confirmation email is sent to the student, and a student profile is created in Salesforce.

### Appointment Scheduling
1. **Verification:** System verifies student information.
2. **Availability Check:** Consultant availability is reviewed before booking.
3. **Approval Submission:** The appointment is submitted for manager approval.
4. **Notifications:** Email notifications are sent to keep students and consultants informed.

---

## System Specifications

- **Salesforce Enterprise Edition** or higher
- **System Administrator** profile for initial setup
- **Standard Platform User** license for end users

---

## Final Summary

The EduConsultPro CRM solution brings greater efficiency to EduConsultPro Institute’s admissions, consulting, and immigration processes, unifying them into an optimized, user-friendly Salesforce platform. This system enables students and administrators to seamlessly navigate processes with a clear, streamlined interface.
