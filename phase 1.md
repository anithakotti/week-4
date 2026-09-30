# Harshu Multispeciality Hospital — Website Architecture

## Project Overview

A professional, clean, and responsive healthcare website for Harshu Multispeciality Hospital.

The website helps patients:
- Learn about the hospital
- Search for doctors
- Explore departments
- View doctor details
- Check doctor availability
- Book appointments
- View appointment confirmation
- Access contact information
- Login or sign up

**Technology:** HTML5 and CSS3 only.

---

## Main Architecture

```text
Patient
   |
   v
Harshu Multispeciality Hospital Website
   |
   +-- Home
   +-- Doctors
   |     +-- Doctor Search
   |     +-- Doctor Cards
   |             |
   |             v
   |       Doctor Details
   |             |
   |             v
   |       Book Appointment
   |             |
   |             v
   |       Confirmation
   |
   +-- Departments
   |     +-- Department Search
   +-- About Us
   +-- Contact
   +-- Login / Sign Up
```

## Website Pages

### 1. Home

- Hospital logo and name
- Sticky navigation
- Hero section
- Healthcare image
- Hospital introduction
- Doctor search
- Department search
- Featured departments
- Featured doctors
- Book appointment CTA
- Contact information
- Footer

### 2. Doctors

- Doctor search bar
- Search by doctor name
- Search by specialization
- Doctor cards
- Doctor image
- Doctor name
- Specialization
- Experience
- Availability
- View Doctor button
- Book Appointment button

### 3. Departments

Six departments:
1. Cardiology
2. Neurology
3. Orthopedics
4. Pediatrics
5. Dermatology
6. General Medicine

Each department includes an image, name, description, available doctors, and View Doctors button.

### 4. Doctor Details

- Doctor photo
- Doctor name
- Specialization
- Qualification
- Experience
- About doctor
- Department
- Available days
- Available time
- Consultation information
- Book Appointment button

Flow: **Doctors → Doctor Details → Book Appointment**

### 5. Appointment

Appointment form fields:
- Patient Name
- Email
- Phone Number
- Select Department
- Select Doctor
- Appointment Date
- Appointment Time
- Reason for Visit
- Additional Message

Button: **Confirm Appointment**

### 6. Appointment Confirmation

```text
Appointment Confirmed

Thank you for booking your appointment.

Patient Name: Anitha Kumar
Doctor: Dr. Arun Kumar
Department: Cardiology
Date: 25 September 2026
Time: 10:30 AM

[ Back to Home ]
```

### 7. About Us

- Hospital introduction
- Mission
- Vision
- Healthcare services
- Experienced doctors
- Patient-focused care
- Hospital facilities

### 8. Contact

- Hospital address
- Phone number
- Email
- Working hours
- Contact form
- Hospital image
- Location/map placeholder

### 9. Login / Sign Up

Login:
- Email
- Password
- Login button
- Forgot Password
- Sign Up link

Sign Up:
- Full Name
- Email
- Phone Number
- Password
- Confirm Password
- Create Account button

**Note:** This is a frontend-only project, so real authentication/database functionality is not implemented.

---

## Header & Navigation

Use a sticky navigation header.

```text
---------------------------------------------------------
HARSHU HOSPITAL | Home | Doctors | Departments | About |
                Contact | Login
---------------------------------------------------------
```

The navigation remains visible while scrolling.

---

## Search Architecture

### Doctor Search

```text
Search Doctor
      |
      v
Doctor Name / Specialization
      |
      v
Matching Doctors
      |
      v
View Doctor
      |
      v
Doctor Details
```

### Department Search

```text
Search Department
       |
       v
Department
       |
       v
Department Details
       |
       v
Available Doctors
```

---

## Complete Patient Journey

```text
                    HOME
                     |
          +----------+----------+
          |                     |
          v                     v
     Doctor Search       Department Search
          |                     |
          v                     v
    Doctor Cards          Department Cards
          |
          v
     View Doctor
          |
          v
    Doctor Details
          |
          v
   Book Appointment
          |
          v
   Appointment Form
          |
          v
 Appointment Confirmation
```

---

## Visual Design

### Style

**Professional Healthcare**

### Color Direction

- Healthcare blue
- White
- Light blue
- Soft neutral backgrounds

### Typography

- Clean readable fonts
- Clear headings
- Comfortable spacing
- Easy-to-read buttons
- Good contrast

### UI Components

- Doctor cards
- Department cards
- Search bars
- Buttons
- Appointment forms
- Information cards
- Confirmation card
- Sticky navigation
- Footer

---

## Responsive Architecture

The website supports:

```text
Desktop
   |
   v
Tablet
   |
   v
Mobile
```

### Desktop
Multi-column layouts and larger cards.

### Tablet
Adjusted grids and spacing.

### Mobile
- Single-column layout
- Responsive navigation
- Full-width buttons
- Stacked appointment form
- Responsive doctor cards
- Responsive department cards

---

## Image Requirements

Use professional healthcare-related images:
- Hospital building
- Doctors
- Medical team
- Departments
- Medical equipment
- Healthcare services

Images should be professional and consistent with the healthcare theme.

---

## Technology

```text
Frontend
|
+-- HTML5
|
+-- CSS3
```

No unnecessary technologies or features.

**No backend, database, API, or JavaScript is required.**

---

## Final Architecture

```text
                    PATIENT
                       |
                       v
          HARSHU MULTISPECIALITY
                 HOSPITAL
                       |
        +--------------+--------------+
        |              |              |
        v              v              v
      HOME          DOCTORS      DEPARTMENTS
                       |              |
                       v              v
                 DOCTOR SEARCH   DEPARTMENT SEARCH
                       |
                       v
                 DOCTOR DETAILS
                       |
                       v
                BOOK APPOINTMENT
                       |
                       v
              APPOINTMENT FORM
                       |
                       v
               CONFIRMATION

        +--------------------------+
        |                          |
        v                          v
    ABOUT US                    CONTACT
        |
        v
   LOGIN / SIGN UP
```

## Final Project Direction

**Harshu Multispeciality Hospital** will be a professional, clean, blue-and-white healthcare website with sticky navigation, doctor and department search, doctor profiles, appointment booking, confirmation, hospital information, contact information, and responsive support for desktop, tablet, and mobile.

The project will be implemented using **HTML and CSS only**.
