# Therapist (Bears-Team-23)
Location based therapist appoinment scheduling portal

#### Feature Purposal:
1. Landing Page
2. Registration
   1. Sign-Up as patient
   2. Sign-Up as therapist
3. Authorized View (role-based)
   1. **Patient Dashboard**
       1. List of therapists
       7. Therapist review
       8. Therapist profile
       3. Reserve appointment
       4. Update/Cancel appointment
       5. Upcoming appointments list
       6. Text chat with therapish (encrypted/incognito)
       7. Update personal information
       8. Reminder notifications of upcoming appointment
    2. **Therapist Dashboard**
       1. Setup/Update personal profile
       2. Customize work schedule (by dates and time)
       3. Review appointment request (Accept / Reject)
       4. View list of up-coming appointments
       5. Request appointment transfter to fellow therapist
    3. Email/Text notifications of upcoming appointments
4. Guest View
  1. Visit differnt parts of portal
  2. See limited list of therapists (public profiles)
  3. See limited information about selected therapist

#### Project Setup Instructions:
This project is designed based upon **yarn workspaces**, install yarn first `npm install -g yarn`. All dependencies will manage at root.

> `$ cd api/` and run `yarn install`

> `$ cd web-client/` and run `yarn install`

Common functionality is managed in `common/` directory.

Voyage-7 | https://chingu.io/
