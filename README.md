
# Cair – Caregiving Service Platform

Cair is an Android-based mobile application designed to connect caregivers (CGs) with individuals in need of care (INOC). It offers a seamless platform for users to create a profile, select their preference (caregiver, INOC, or referral), and request or provide caregiving services. The app ensures a smooth experience by allowing easy booking, payments, and communication between caregivers and individuals needing care.

## Features

- **Profile Creation**: Users can create a profile and select their preference (Caregiver, INOC, Referral).
- **Search Functionality**: INOCs can search for available caregivers in their area, filtered by H3 index.
- **Caregiver Booking**: INOCs can book caregivers based on their rate.
- **Notification System**: Caregivers receive notifications for booking requests and have 24 hours to accept or reject.
- **Chat Feature**: Upon acceptance, a real-time chat system is initiated between the caregiver and INOC.
- **Service Booking**: Caregivers provide the service on the agreed date and time.

## Tech Stack

- **Kotlin**: Android app development language.
- **MVVM Architecture**: Clean separation of concerns with ViewModel and Repository layers.
- **Firebase**:
  - **Firestore**: For storing user profiles, booking data, and chat messages.
  - **Firebase Authentication**: For secure user authentication.
  - **Firebase Cloud Functions**: For serverless backend operations (e.g., notifications, booking management).
  - **Firebase Messaging**: For push notifications.
- **Stripe**: For handling payments securely.
- **Third-party SDKs**: Used for various functionalities such as payments and notifications.
  
## App Flow

1. **Profile Setup**:
   - Users select their role (Caregiver, INOC, or Referral) during profile creation.
   
2. **INOC Search**:
   - INOCs can search for caregivers in their area using H3 indexing.
   - Caregivers are displayed with their profiles and rate information.
   
3. **Booking Request**:
   - INOCs can select a caregiver and book the service.
   - The caregiver receives a notification of the booking request and has 24 hours to accept or reject the request.

4. **Chat System**:
   - If the caregiver accepts the request, a real-time chat is initiated.
   
5. **Caregiving Service**:
   - The caregiver provides the service on the agreed date and time.


📸 Screenshots
---

<p align="start">
  <span><strong> Registration</strong></span> &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
  <span><strong> Profile Creation</strong></span> &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
  <span><strong> Home Screen</strong></span>
</p>
  <img src="https://github.com/user-attachments/assets/7d8ffb01-57fe-43a2-9938-f55a74118437" alt="Screen1" width="250"/>
  <img src="https://github.com/user-attachments/assets/f05628a2-e8c6-4893-8e79-edd915e096e9" alt="Screen2" width="250"/>
  <img src="https://github.com/user-attachments/assets/8af7ca28-b7a3-41c8-82a7-703a2121d7d8" alt="Screen3" width="250"/>
  
  <p align="start">
  <span><strong>Caregiver Profile</strong></span> &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
  <span><strong>Caregiver Booking Calendar</strong></span> &emsp;&emsp;&emsp;&emsp;&emsp;
  <span><strong>Book Caregiver</strong></span>
  </p>
  <img src="https://github.com/user-attachments/assets/2e9098e8-9194-4c7d-88c4-14c05c9e20d9" alt="Screen4" width="250"/>
  <img src="https://github.com/user-attachments/assets/0e9e1115-96f8-42df-b151-04f289955239" alt="Screen10" width="250"/>
  <img src="https://github.com/user-attachments/assets/907dba7b-b5ab-4763-8c4a-010def0c9ccf" alt="Screen6" width="250"/>

  <p align="start">
  <span><strong>InNeedOfCare Profile</strong></span> &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
  <span><strong>Share INOC Profile</strong></span> &emsp;&emsp;&emsp;&emsp;&emsp;
  <span><strong>View CG Profile</strong></span>
  </p>

  <img src="https://github.com/user-attachments/assets/67bbed95-0855-455a-8de3-42e00f9ee2bf" alt="Screen8" width="250"/>
  <img src="https://github.com/user-attachments/assets/f2516382-b515-4f54-825d-28c9501915f2" alt="Screen10" width="250"/>
  <img src="https://github.com/user-attachments/assets/5b9cc9e1-9a07-4385-a42a-f6d3f94a92c0" alt="Screen9" width="250"/>
  
</div>

