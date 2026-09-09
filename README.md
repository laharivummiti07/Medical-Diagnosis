# 🏥 Medical Diagnosis Center by Service Portal (ServiceNow)

A complete healthcare management application built on the **ServiceNow Platform** that allows patients to book diagnostic tests, track appointments, view laboratory reports, manage payments, and receive automated notifications through a Service Portal.

---

## 📌 Project Overview

The **Medical Diagnosis Center by Service Portal** is a ServiceNow scoped application developed to automate the workflow of a medical diagnostic center.

This application provides a simple and user-friendly portal where patients can register, book diagnostic tests, track appointment status, view and download reports, while administrators manage appointments, reports, payments, and diagnostic services.

The project reduces manual work, improves appointment scheduling, and provides a centralized healthcare management system.

---

## 🎯 Objectives

* Digitize diagnostic test booking.
* Prevent duplicate appointment bookings.
* Automate appointment approval workflow.
* Generate and manage laboratory reports.
* Track payment status.
* Send automated email notifications.
* Provide role-based access for patients and administrators.

---

## ✨ Features

### 👤 Patient Portal

* Patient Login & Profile Management
* Search Diagnostic Tests
* Book Diagnostic Tests
* Select Appointment Date & Time Slot
* View Appointment Status
* Download Laboratory Reports
* View Payment Status
* Receive Email Notifications

### 🧑‍💼 Administrator Portal

* Manage Diagnostic Tests
* Approve or Reject Appointments
* Upload Laboratory Reports
* Update Appointment Status
* Update Payment Status
* Manage Patient Records
* View Dashboard Summary

---

## 🛠️ Technology Stack

| Technology               | Purpose                          |
| ------------------------ | -------------------------------- |
| **ServiceNow**           | Application Development Platform |
| **Service Portal**       | Frontend User Interface          |
| **Flow Designer**        | Workflow Automation              |
| **Business Rules**       | Server-side Validation           |
| **Client Scripts**       | Client-side Validation           |
| **UI Policies**          | Dynamic Form Behaviour           |
| **Notifications**        | Email Alerts                     |
| **Access Control (ACL)** | Role-Based Security              |
| **Custom Tables**        | Database Management              |

---

## 📂 Custom Tables

| Table Name      | Description                               |
| --------------- | ----------------------------------------- |
| Patient         | Stores patient personal details.          |
| Diagnostic Test | Stores diagnostic test information.       |
| Appointment     | Stores appointment booking details.       |
| Report          | Stores laboratory reports and findings.   |
| Payment         | Stores payment amount and payment status. |

---

## 📋 Service Portal Pages

* 🏠 Home Page
* 📝 Book a Test
* 📅 My Bookings
* 📄 My Reports
* ✅ Appointment Confirmation
* 📊 Admin Dashboard

---

## 🔄 Appointment Workflow

The appointment follows an automated workflow using **Flow Designer**.

Requested → Pending Approval → Confirmed → Sample Collected → Processing → Completed → Report Available

### Workflow Description

1. Patient books a diagnostic test.
2. Appointment is created with **Requested** status.
3. Administrator verifies and approves the appointment.
4. Patient receives a confirmation email within 24 hours.
5. Sample collection is completed.
6. Laboratory processes the test.
7. Report is generated.
8. Patient downloads the report from **My Reports**.

---

## 📧 Email Notifications

The application automatically sends emails for:

* Appointment Confirmation
* Appointment Approval
* Appointment Reminder
* Report Availability
* Payment Confirmation

---

## 🔒 Role-Based Access Control

### Patient

* Register and Login
* Book Diagnostic Tests
* View My Bookings
* View & Download Reports
* View Payment Status

### Administrator

* Manage Patients
* Manage Diagnostic Tests
* Approve Appointments
* Upload Reports
* Update Payments
* Monitor Dashboard

---

## 🧪 Functional Validations

The application includes the following validations:

* Mandatory Field Validation
* Duplicate Appointment Prevention
* Appointment Slot Availability Validation
* Maximum Booking Rules
* Payment Status Validation
* Report Availability Validation

---

## 📊 Project Workflow

Patient Login/Register

↓

Search Diagnostic Test

↓

Book Appointment

↓

Administrator Approval

↓

Confirmation Email

↓

Sample Collection

↓

Lab Processing

↓

Report Generation

↓

Download Report

---

## 📸 Project Screenshots

### 🏠 Home Page

Displays diagnostic tests, search bar, bookings, and reports.

### ✅ Appointment Confirmation

Shows appointment details, payment information, and approval status.

### 📄 My Reports

Displays completed laboratory reports with findings and download option.

> **Note:** Add your project screenshots in the `screenshots` folder and update image paths.

Example:

```md
![Home Page](screenshots/home-page.png)
![Appointment Confirmation](screenshots/appointment-confirmation.png)
![My Reports](screenshots/my-reports.png)
```

---

## ⚙️ Installation & Setup

### Prerequisites

* ServiceNow Personal Developer Instance (PDI)
* Service Portal Plugin Enabled
* Administrator Access

### Setup Steps

1. Login to ServiceNow Developer Instance.
2. Open **Studio**.
3. Create a Scoped Application named **Medical Diagnosis Center**.
4. Create custom tables.
5. Configure Service Portal pages and widgets.
6. Create Business Rules, Client Scripts, UI Policies, and Flow Designer.
7. Configure Notifications and ACLs.
8. Test the complete application.

---

## ✅ Testing

### Functional Testing

* Patient Registration
* Appointment Booking
* Appointment Validation
* Report Download
* Payment Tracking
* Email Notifications

### User Acceptance Testing (UAT)

* All major modules successfully passed testing.
* Duplicate booking validation works correctly.
* Workflow executes successfully.
* Reports are generated and downloaded successfully.

**Overall Status:** ✅ Passed

---

## 📈 Future Enhancements

* Online Payment Gateway Integration
* Home Sample Collection
* SMS & WhatsApp Notifications
* QR Code Report Download
* Doctor Consultation Booking
* Patient Medical History Dashboard
* Advanced Analytics Dashboard

---

## 👩‍💻 Developer Information

**Project Name:** Medical Diagnosis Center by Service Portal

**Developer:** Vummiti Naga Jyothi Lahari

**Platform:** ServiceNow

**Project Type:** Service Portal Healthcare Management System

---

## 🙏 Acknowledgement

This project was developed as part of the **SmartBridge ServiceNow Internship Program** using the ServiceNow platform. It demonstrates healthcare workflow automation through Service Portal, Flow Designer, Business Rules, Notifications, and Role-Based Access Control.
