# EventBuddy

EventBuddy is a comprehensive event management Android application that enables organizers to create and manage events, facilities, and participants while providing entrants and users with a seamless way to browse, join, and track events.  
It supports robust admin controls, QR code check-ins, waitlist management, notifications, and location mapping — making event organization and participation intuitive and efficient.

---

## 📷 Showcase

### Logic Flow
![Logic Flow](https://github.com/CMPUT301F24trojan1/trojan1-eventbuddy/blob/main/Overall%20Flow.png)

### Agile Development Backlog
<img width="800" src="https://github.com/user-attachments/assets/94b0f518-fbcd-4cdf-b03a-3740cab9e022" alt="Agile Backlog">

### User Interface of the Application
#### Main Page
![Main Page](https://github.com/CMPUT301F24trojan1/trojan1-eventbuddy/blob/main/UI-prototypes/User%20Flow%20Prototypes/User%20Flow%20Main%20Menu.png)

#### View Event
![View Event](https://github.com/CMPUT301F24trojan1/trojan1-eventbuddy/blob/main/UI-prototypes/User%20Flow%20Prototypes/User%20View%20event%20(3)-1.png)

#### Share Event
![Share Event](https://github.com/CMPUT301F24trojan1/trojan1-eventbuddy/blob/main/UI-prototypes/User%20Flow%20Prototypes/User%20share%20event%201.png)

#### Sign Up
![Sign Up](https://github.com/CMPUT301F24trojan1/trojan1-eventbuddy/blob/main/UI-prototypes/User%20Flow%20Prototypes/User%20sign%20up.png)

---

## ⚙️ Key Features

### Admin Features
- Browse and manage all events, facilities, images, and users.
- Remove or edit events, facilities, and users.
- View and manage QR codes for events.
- Access analytics for event participation.

### Organizer Features
- Create, edit, and manage events and facilities.
- Upload posters and facility images.
- Generate QR codes for event check-ins.
- Manage waitlists and attendee selection.
- Send notifications to participants.

### Entrant Features
- Browse available events and join waitlists.
- View event details, locations, and deadlines.
- Receive notifications for updates.
- Upload and manage profile details.

### Shared Features
- QR code generation and scanning.
- Interactive maps showing event locations and participants.
- Secure authentication and profile management.
- Personalized profile image generation using bitmaps.

---

## 🛠 Architecture & Components

EventBuddy is modular and uses adapters, fragments, and services to handle its complexity.

| Component                        | Responsibilities |
|-----------------------------------|------------------|
| AdminEventArrayAdapter           | Displays and manages events for admins. |
| AdminFacilitiesArrayAdapter      | Displays and manages facilities for admins. |
| AdminImagesArrayAdapter          | Manages uploaded images in the app. |
| AdminQRArrayAdapter              | Displays QR codes and event details. |
| AdminUsersArrayAdapter           | Manages user data and authentication. |
| EventArrayAdapter                | Displays event lists to entrants and organizers. |
| WaitlistAdapter                  | Manages waitlist and event participation. |
| FacilitySetupFragment            | Handles facility creation and editing. |
| EventDetailsDialogFragment       | Displays and manages event details for entrants. |
| EventOptionsDialogFragment       | Allows event-specific actions for organizers. |
| ProfileFragment                  | Displays and manages user profiles. |
| QRCodeUtil                       | Generates and hashes event QR codes. |
| NotificationSenderFragment       | Sends notifications to relevant users. |

---

## 📚 Technologies Used

- **Language:** Java  
- **Platform:** Android  
- **Architecture:** Adapter-based UI with modular fragments and services  
- **Database:** Firebase Realtime Database  
- **Notifications:** Firebase Cloud Messaging  
- **Other Tools:** Google Maps API, QR code libraries  

---

## 🚀 My Contributions

- Designed and implemented the **AdminEventArrayAdapter** for event listing and management.  
- Developed **facility and event management fragments** for organizer workflows.  
- Built **QR Code generation and scanning tools** for event check-ins.  
- Implemented **waitlist management logic** for entrants and organizers.  
- Integrated **Firebase Cloud Messaging** for notifications.  
- Created **profile customization features** including bitmap-based profile images.

---

## 📌 Additional Resources

- [UI Designs & Prototypes](Projects/UI-Designs)  
- [Overall Prototype View](Projects/Prototypes)  
- [User Flow](Projects/UserFlow)  
- [Organizer Flow](Projects/OrganizerFlow)  
- [Admin Flow](Projects/AdminFlow)  
- [Product Backlog](Projects/ProductBacklog)  
- [CRC Cards](Projects/CRCCards)  

