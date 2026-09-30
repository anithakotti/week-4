# Healthcare Website Architecture

## Simple Architecture

```text
             USER
               |
               v
        HEALTHCARE WEBSITE
               |
       +-------+--------+
       |       |        |
       v       v        v
    Doctors  Departments Services
       |       |        |
       +-------+--------+
               |
               v
        Appointment
               |
               v
           Database
               |
       +-------+--------+
       |       |        |
       v       v        v
    Patients Doctors Appointments
```

## Simple Explanation

- **User** → visits the healthcare website.
- **Website** → shows doctors, departments, and services.
- **Doctors** → users can view doctor information.
- **Departments** → users can see different hospital departments.
- **Services** → users can see healthcare services.
- **Appointment** → users can book an appointment.
- **Database** → stores patient, doctor, and appointment information.

## Interview Explanation

> Our healthcare website allows users to view doctors, departments, and services, book appointments, and store the required information in the database.
