
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
