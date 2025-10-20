# Jibonsheba Workflow

## High-Level Workflow Overview

1.  **Central Administration:** A super admin manages the entire system, including the different clinics (tenants) using the software.
2.  **Tenant (Clinic) Operation:** Each clinic has its own isolated environment to manage its day-to-day operations.
3.  **Patient Interaction:** Patients can access their reports through a dedicated portal.

---

## Central Administration Workflow

This workflow is handled by a **super administrator**.

### Tenant Management
The administrator can create, view, update, and delete tenant accounts. Each tenant represents a separate clinic or practice with its own data, users, and patients.

### Package Management
The administrator can define different subscription packages or plans (e.g., Basic, Premium) that tenants can subscribe to. This includes managing the features available in each package.

---

## Tenant (Clinic/Hospital) Workflow

This is the core application used by the staff of a clinic or hospital.

### Step 1: Initial Setup & Configuration (Admin of the Clinic)
1.  **System Settings:** Configure basic information about the clinic, such as its name, address, and logo.
2.  **User Management:** Create user accounts for all staff members (doctors, receptionists, lab technicians, accountants).
3.  **Roles & Permissions:** Assign roles to users (e.g., receptionist, doctor, lab-admin) and define what actions each role can perform.
4.  **Department Management:** Set up the various departments within the clinic (e.g., Cardiology, Pediatrics, Pathology).
5.  **Doctor & Schedule Management:**
    *   Add doctors to the system.
    *   Define the schedules for each doctor, including their available days and times.
6.  **Pathology/Lab Configuration:**
    *   Define laboratory tests that the clinic offers.
    *   Configure test parameters, including attributes, units of measurement, and reference ranges.
    *   Set the prices for each test.
7.  **Letterhead Configuration:** Design and upload letterheads for official documents like invoices and test reports.

### Step 2: Patient Registration and Appointment Scheduling (Receptionist)
1.  **Patient Registration:** A new patient's demographic information (name, age, contact details) is entered into the system to create a patient record.
2.  **Appointment Scheduling:**
    *   The receptionist books an appointment for a patient with a specific doctor based on the doctor’s availability.
    *   The system allows for rescheduling or canceling existing appointments.

### Step 3: Doctor's Consultation Workflow
1.  **View Dashboard:** The doctor logs in and views their dashboard, which shows a summary of their appointments and other relevant information.
2.  **Patient List:** The doctor can see a list of patients scheduled for the day.
3.  **Patient Details:** The doctor can access the complete medical history of a patient, including past visits and test results.
4.  **Consultation:** During the consultation, the doctor can record notes, diagnose, and prescribe medications or lab tests.

### Step 4: Billing and Invoicing (Receptionist/Billing Desk)
1.  **Create Bill:** After a consultation or for any service, a bill is generated. The system uses a cart to add multiple items (consultation fees, lab tests, procedures) to a single invoice.
2.  **Collect Payment:** The receptionist or cashier collects the payment from the patient. The system supports various payment methods.
3.  **Invoice Generation:** A formal invoice is generated and can be printed or sent to the patient.
4.  **Refunds:** The system handles full or partial refunds if required.

### Step 5: Pathology and Laboratory Workflow (Lab Technician)
1.  **Sample Collection:** When a test is prescribed, a sample is collected from the patient. The system tracks the sample and can print labels for identification.
2.  **Lab Receiving:** The lab technician formally receives the sample in the laboratory through the system.
3.  **Result Entry:** After processing the sample, the technician enters the test results into the system.
4.  **LIS Integration:** The application can integrate with a Laboratory Information System (LIS) to automatically receive test results from lab machines.
5.  **Report Generation:** Once the results are verified, a test report is generated, often using the pre-configured letterhead.

### Step 6: Financial and Administrative Tasks (Accountant/Admin)
1.  **Expense Management:** Record and categorize all expenses incurred by the clinic.
2.  **Commission Management:**
    *   Calculate and manage commissions for referring doctors or agents.
    *   Generate commission reports.

### Step 7: Reporting and Analytics (Management/Admin)
The system provides a comprehensive reporting module:
*   **Sales Reports:** To track revenue from different services.
*   **Payment Reports:** To monitor cash flow and payment methods.
*   **Expense Reports:** To analyze spending patterns.
*   **Test Summary Reports:** To see the volume and types of tests being performed.
*   **Doctor-specific Reports:** To analyze a doctor's patient load and referred tests.

---

## Patient Workflow

1.  **Login:** Patients can log in to a dedicated web portal using their credentials. The system uses OTP (One-Time Password) verification for security.
2.  **View Reports:** Once logged in, patients can view and download their test reports.
