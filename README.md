# CampusOne College ERP Portal (Browser Demo)

## Run in VS Code
1. Extract `CampusOne_College_ERP.zip`.
2. Open the `college_erp_portal` folder in VS Code.
3. Open `index.html`.
4. Recommended: install the **Live Server** extension by Ritwick Dey.
5. Right-click `index.html` → **Open with Live Server**.
6. Sign in using one of the demo accounts below.

## Demo accounts
- Dean/Admin: `dean` / `dean123`
- Teacher: `teacher1` / `teach123`
- Student: `student1` / `stud123`

## Features
- Separate student, teacher, and dean/admin portal views.
- Student dashboard, attendance summary/history, syllabus & notes list, announcements, assignments.
- Teacher can record attendance, upload resources (small file/text demo), publish announcements and assignments.
- Dean/admin can create/delete student and teacher accounts.
- Data persists in this browser using localStorage.

## Important security note
This is a front-end demonstration project, **not a secure production ERP**. Usernames/passwords and records are stored in browser localStorage and can be inspected or modified by anyone using the browser. There is no real server-side role enforcement, multi-device sync, or secure file storage. Do not use real student data or real passwords. For a deployed college system, add a backend (for example Node.js/Express), database, secure password hashing, server-side authorization, and controlled file uploads.
