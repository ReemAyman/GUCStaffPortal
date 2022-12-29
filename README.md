# GUC Staff Portal Web Platform :man_teacher:
## Description :memo:
This project aims to implement a web platform for the university staff (Teaching Assistant, Instructors, and Human Resources). In this portal, they can access multiple functionalities whether academic (for TAs and Instructors only) or non-academic.
## Core Features
1. **Authentication**

* The system includes authentication (logging in/out) for staff members only.
* A new staff member is added by an HR member.

2. **Attendance System** 

* The staff should be able to track the number of days and hours spent in the university to be able to know whether they have missing days/hours in their working days.
* Signing-in/out is simulated by a button click in the platform.

3. **Leave System**

* There are multiple types of leaves to be requested/responded in the system. They include:
1. Annual Leave.
2. Accidental Leave.
3. Sick Leave.
4. Maternity Leave.
5. Compensation Leave.

For more information :memo:: you can read the documents in this link [GUC Staff Portal Project Description](https://drive.google.com/drive/folders/1BTsLcJL2vaZzvU4GFugoHjjG9sgEYd4W?usp=sharing).
## Getting Started :rocket:
### Downloading the project
Run the command `git clone https://github.com/ReemAyman/GUCStaffPortal.git` to get the project inside your local PC.

### Launching the project
* To install the needed packages, run the command `npm i` inside the project diectory.
* To launch the server: `npm /server/index.js`
* The server is listening to port 3000.
* For seeded data (Open the directory: locations/departments/faculties/staff members), please uncomment `dummy.seedDB();` found in `index.js`, then run once then comment it back again after seeing the last debug message "Seeded TA successfully".
* For more information about the features inside the backend: see readme.txt


---
**Disclaimer** :warning:

This project can only be used for learning and referencing purposes.

---