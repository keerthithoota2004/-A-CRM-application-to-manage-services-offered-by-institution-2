# A CRM APPLICATION TO MANAGE SERVICES OFFERED BY INSTITUTION - SALESFORCE

EduConsultPro Institute is dedicated to enhancing the management of its admission processes, consulting services, and immigration case handling. Facing a surge in applications and service requests, EduConsultPro Institute has adopted Salesforce CRM to streamline operations and ensure an efficient experience for students and admissions staff.

This project integrates a range of features, optimizing processes for admissions, consulting, and immigration case management within a single, cohesive platform. Here’s a summary of the components and functionalities implemented in Salesforce:

---

## Project Overview

### Key Components:

1. **Admissions Application System**
   - Developed a user-friendly admission system that enables online applications.
   - Includes automated notifications and detailed reporting for admissions staff.

2. **Consulting Request Management**
   - Created an efficient approval workflow with automated email alerts and a streamlined submission process for consulting requests.
   - Allows students to request consultations, schedule appointments, and track service statuses.

3. **Immigration Case Handling**
   - Allows students to initiate cases, manage documents, and track case progress with integrated tools, ensuring seamless support for immigration and visa applications.

4. **Salesforce Objects and Custom Flows**
   - Designed Salesforce objects, lookup relationships, and custom flows to unify app pages in the Salesforce Lightning Experience, delivering a clear and efficient interface for users.

---

## Tasks Breakdown

### Task 1: Create Objects from Spreadsheet
- Imported objects like **Course**, **Consultant**, **Student**, and **Appointment** to represent key institutional data.
- Established lookup relationships for integrity and data navigation, including links between **Appointment ↔ Student** and **Appointment ↔ Consultant**.
- Created a **Registration** object to manage student and course data, along with lookup relationships for immigration or visa cases.
- Customized the **Case** object with "Type" and "Status" fields to define immigration and visa applications.

### Task 3: Create Users
- Added a new user with a **Consultant** profile and configured user settings for manager approval in the profile setup.

### Task 4: Create an Approval Process
- Designed an **Appointment Approval** process with automated email templates for request submission, approval, and rejection.
- Configured record editability settings to allow modifications by the administrator or assigned approver.

### Task 5: Record-Triggered Flow
- Developed a record-triggered flow for appointment approvals, named **EduConsultPro Approval Flow**, to automatically submit approval requests when records are created.

### Task 6: ScreenFlow for Existing Student Appointment Booking
- Created a **ScreenFlow** for student appointment and case management.
- Configured elements to gather student information, retrieve records, and create appointments or cases based on student needs.

### Task 7: Unified ScreenFlow
- Developed a **Welcome Screen** to display EduConsultPro’s services and options for existing and new students.
- Integrated subflows to manage existing and new student pathways, ensuring efficient service across user types.

---

## Final Deliverable: EduConsultPro Lightning App Page
- Configured the **EduConsultPro Home Page** in Lightning App Builder.
- Incorporated the **EduConsultantPro Flow** to enhance user experience and streamline administrative processes.

---

This Salesforce implementation brings increased efficiency to EduConsultPro’s admissions, consulting, and immigration services, all within an optimized, user-friendly CRM interface.

