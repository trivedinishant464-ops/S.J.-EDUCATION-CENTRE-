
# S.J EDUCATION CENTRE — Complete School App

This is a fresh full-stack school management app project.

## Important: You become the Super Admin
On the first launch, there is no admin account. The first setup screen asks for:
- Your name
- Your Admin ID
- Your password (minimum 8 characters)

That account is the only initial `admin` account.

After setup you can create:
- Student IDs/passwords
- Parent IDs/passwords
- Teacher IDs/passwords
- Reset passwords
- Enable/disable accounts

## Included
- Node.js + Express backend
- SQLite database
- Password hashing with bcrypt
- Session-based login
- Role-based authorization
- Admin panel
- Notice management
- Homework management
- Attendance
- Timetable database/API
- Fees database/API
- Results database/API
- Installable PWA shell
- Your supplied S.J EDUCATION CENTRE logo

## Run
1. Install Node.js 18+.
2. Open a terminal in this folder.
3. Run:
   npm install
4. Run:
   npm start
5. Open:
   http://localhost:3000

## Production
For a real public school deployment:
- Set a strong SESSION_SECRET environment variable.
- Use HTTPS.
- Put the app behind a production reverse proxy.
- Back up `school.db`.
- Add a real cloud database if many simultaneous users are expected.
- Configure secure cookies (`secure:true`) when HTTPS is enabled.
- Add a dedicated domain and Android/iOS store build if required.

The source is intentionally built so the first-run admin setup is controlled by you rather than shipping a public default admin password.
## 🚀 School App Features

### 📊 Data Management
- Excel Import
- Excel Export
- PDF Export
- PDF Print
- CSV Import/Export
- Bulk Student Import
- Bulk Teacher Import
- Backup & Restore

### 👨‍🎓 Student Management
- Student Registration
- Student Profile
- Student ID
- Class & Section
- Parent Details
- Student Photo
- Student ID Card
- Student Search & Filter

### 👨‍🏫 Teacher & Staff
- Teacher Management
- Staff Management
- Teacher Attendance
- Staff Attendance
- Leave Management
- Salary/Payroll

### 📝 Attendance
- Student Attendance
- Teacher Attendance
- Daily/Monthly Reports
- Present/Absent/Late
- Attendance PDF & Excel Report

### 💰 Fees Management
- Fee Structure
- Fee Collection
- Paid/Pending Fees
- Fee Receipt PDF
- Fee Reports
- Excel Export

### 📚 Homework & Study
- Homework
- Assignments
- Study Material
- Class-wise Content

### 📅 Timetable
- Class Timetable
- Teacher Timetable
- Subject Management

### 📝 Exam & Results
- Exam Management
- Marks Entry
- Automatic Grade Calculation
- Result Generation
- Report Card PDF
- Result Excel Export

### 📢 Communication
- Notice Board
- School Announcements
- Events
- Holidays
- Notifications

### 🔐 User & Security
- Super Admin
- Admin
- Teacher
- Parent
- Student
- Role-based Permissions
- Password Reset
- Enable/Disable Accounts

### ⚙️ Admin Panel
- School Name Editing
- School Logo Editing
- Session Management
- Class & Section Management
- Subject Management
- User Management
- Database Backup & Restore

### 📱 App
- Mobile Responsive Design
- Installable PWA
- Search & Filters
- Dashboard
- Print Support
