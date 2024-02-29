# docap
(CBP-16) Optimizing Doctor Availability and Appointment Allocation in Hospitals through Digital Technology

## Introduction

In healthcare, efficient appointment scheduling is crucial to ensure patients receive timely care while maximizing the utilization of doctor resources. This project proposes a digital solution that leverages advanced technologies to automate the process of identifying doctor availability and allocate appointment slots accordingly. The primary goal is to reduce patient wait times and improve the overall efficiency of the appointment scheduling process in hospitals.

## Features

Disease Selection: Users can select specific diseases (e.g., Fever, Skin, Eye) to find relevant doctors.

Doctor Availability: A list of doctors specializing in the selected disease is displayed, marked in green (available) or red (unavailable) based on their current status.

Slot Description: Users can view detailed slot information for each doctor, including availability and description of available slots.

Sorting Options: Doctors can be sorted based on appointment time or fees, allowing patients to choose the most convenient option.

Booking and Registration: When a patient selects a doctor and appointment time, a login/register popup appears for user authentication.

Time and Fee Adjustments: Booking time intervals are customizable (e.g., 5 or 10 minutes), with fees adjusted accordingly.

## Doctor's Attendance

Manual Attendance: Doctors have the option to manually mark their attendance using a separate dashboard.

Face Detection: Alternatively, a face detection system at the entrance can automate entry and exit tracking, ensuring real-time doctor availability updates.

## Technologies

HTML, CSS (Tailwind CSS), JavaScript: Frontend development for the user interface.

Django, SQL: Backend development for managing user data, appointments, and doctor attendance.

## Usage
Visit the website and use the user dashboard to find doctors based on disease, availability, and fees.

Doctors can log in to mark their attendance manually or use the face detection system for automatic attendance tracking.
