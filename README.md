# CarePulse: Healthcare Management Application
A healthcare patient management application that allows patients to easily register, book, and manage their appointments with doctors, featuring administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications, all built using Next.js.  
  
This was a project by [JavaScript Mastery](https://www.jsmastery.pro/)  


## Visit the Site
You can visit the live site [here](https://healthcare-project-iota.vercel.app/) and contact me at [alexandrougrigorios@gmail.com](mailto:alexandrougrigorios@gmail.com) for any help!

## A look inside the Application
### 1) Patient Login Page  
![Patient Login Page](https://github.com/gregalexan/healthcare_project/blob/master/client_home.png)  
### 2) Admin Dashboard
![Admin Dashboard](https://github.com/gregalexan/healthcare_project/blob/master/admin_home.png)  

## ⚙️ Tech Stack
* Next.js  
* Appwrite
* Typescript
* TailwindCSS
* ShadCN
* Twilio

## 🔋 Features  
👉 **Register as a Patient**: Users can sign up and create a personal profile as a patient.  
👉 **Book a New Appointment with Doctor**: Patients can schedule appointments with doctors at their convenience and can book multiple appointments.  
👉 **Manage Appointments on Admin Side**: Administrators can efficiently view and handle all scheduled appointments.  
👉 **Confirm/Schedule Appointment from Admin Side**: Admins can confirm and set appointment times to ensure they are properly scheduled.  
👉 **Cancel Appointment from Admin Side**: Administrators have the ability to cancel any appointment as needed.  
👉 **Send SMS on Appointment Confirmation**: Patients receive SMS notifications to confirm their appointment details.  
👉 **Complete Responsiveness**: The application works seamlessly on all device types and screen sizes.  
👉 **File Upload Using Appwrite Storage**: Users can upload and store files securely within the app using Appwrite storage services.  
👉 **Manage and Track Application Performance Using Sentry**: The application uses Sentry to monitor and track its performance and detect any errors.  

## 🤸 Quick Start  
  
### Prerequisites  

Make sure you have the following installed on your machine:
* [Git](https://git-scm.com/)
* [NodeJS](https://nodejs.org/en)
* [npm](https://www.npmjs.com/)

### Cloning the Repository  
```sh
git clone git@github.com:gregalexan/healthcare_project.git
```
  
Inside the *healthcare_project*
```sh
cd healthcare_project
```

### Installation  
```sh
npm install
```
  
### Set Up Enviroment Variables
Create a new file named *.env.local* in the root of the project and add the following content:
```sh
#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=123456
```
Replace the placeholder values with your actual Appwrite credentials. You can get these by signing up one the [Appwrite Website](https://appwrite.io/)  

### Running the Project  
```sh
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
