# Completed application setup

Requires Node.js 20.19+ and local MongoDB Community Edition running on port 27017. The tracked .env file sets MONGODB_URI=mongodb://127.0.0.1:27017/cis3339_homework1 and PORT=3000. No database setup, seeding, or Atlas account is required. MongoDB initializes on first write and Mongoose initializes indexes at startup.

From the repository root run:

```bash
npm install
npm run build
npm start
```

Open http://localhost:3000. Refresh /students, /courses, and /enrollments to verify SPA fallback. For development, run npm start and npm run dev in separate terminals and open http://localhost:5173. The backend uses MongoDB, not JSON files. Test duplicate student/course IDs, duplicate enrollments, deleting a student/course with enrollments, and persistence after restarting.

The original instructor README.md remains in the repository as the assignment specification. Original starter code is preserved in Git history (initial commit).