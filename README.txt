VELHERB NATURALS - COMPLETE FULL STACK WEBSITE

STACK
- Frontend: HTML/CSS/JavaScript
- Backend: Node.js + Express
- Database: SQLite (velherb.db)
- Authentication: bcrypt password hashing + JWT
- Admin dashboard: users, orders, revenue, status updates

SETUP ON WINDOWS
1. Install Node.js LTS from https://nodejs.org/
2. Open CMD inside this folder.
3. Run: npm install
4. Run: npm start
5. Open: http://localhost:3000

ADMIN DEMO
Username: admin
Password: 1234
Change these before production using environment variables.

PHONE
Replace YOUR_PHONE_NUMBER in public/app.js with your WhatsApp number including country code, without +, spaces or hyphens. Example: 919876543210

EMAIL
Configured as: whaleherbnature@gmail.com

DATABASE
A file named velherb.db is automatically created after first start. Customer accounts and orders are stored there.

IMPORTANT
This is a working local full-stack prototype. For public production use, deploy the Node backend and database on a server, use HTTPS, a strong JWT secret, a real admin authentication system, secure environment variables, backups, rate limiting, and proper legal/privacy/commerce compliance.
