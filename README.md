Step 1: Update the Data
        First, fix the data by updating the Admissions table:

        Change attending_doctor_id from 3 to 29.

        Change patient_id from 35 to 4.

Step 2: Solve the Tasks
        Doctors with Admissions:

        Find doctors who are linked to at least one admission.

Doctors without Admissions:

Find doctors who are not linked to any admissions.

Patients with Missing Doctor Details:

Find patients whose admissions are linked to a non-existent doctor.

How It Works:

Use JOINs to connect tables (Doctors, Patients, and Admissions).

Use LEFT JOIN to include all records, even if there’s no match.

Use WHERE to filter results (e.g., find missing doctor details)
