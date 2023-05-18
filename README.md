# Doctor Appointment Application
The Doctor Appointment Application is a web-based application that allows patients to schedule and manage appointments with doctors. It provides a user-friendly interface for patients to sign up, sign in, browse doctors' profiles, and book appointments. The application also includes features for canceling appointments and managing authentication tokens.

## Features
- **User Sign-up:** Patients can create an account by providing their personal information, including name, email, password, and contact details.
- **User Sign-in:** Registered patients can sign in using their email and password to access their account.
- **Doctor Profiles:** Patients can view profiles of doctors, including their specialties, qualifications, and availability.
- **Appointment Booking:** Patients can schedule appointments with their chosen doctors by selecting the date and time.
- **Appointment Cancellation:** Patients can cancel their appointments if necessary.
- **Token-based Authentication:** The application uses tokens for authentication and ensures secure access to user accounts.

## Technologies Used
- Java
- Spring Boot
- Spring Data JPA
- Lombok
- Maven

## Endpoints
The following are the sample endpoints provided by the Doctor Appointment Application:
- **POST /api/signup -** Create a new patient account.
- **POST /api/signin -** Sign in with a patient account.
- **GET /api/doctors -** Retrieve a list of available doctors.
- **POST /api/appointments -** Book a new appointment.
- **DELETE /api/appointments/{appointmentId} -** Cancel a specific appointment.

## How to Use
- **Sign Up:** Create a new account by providing your personal details.
- **Sign In:** Log in to your account using your email and password.
- **Browse Doctors:** Explore the list of doctors and view their profiles.
- **Book an Appointment:** Select a doctor, choose a suitable date and time, and confirm your appointment.
- **Cancel Appointment:** If needed, you can cancel your appointment from your account.
- **Log Out:** To securely sign out, click on the "Log Out" button.

## Summary
The Doctor Appointment Application is designed to streamline the appointment scheduling process for patients seeking medical consultation with doctors. With this application, patients can easily create an account, browse through a list of available doctors, book appointments, and manage their scheduled appointments. The application also ensures secure access to user accounts through token-based authentication.
