# VoiceEnquiry

A project completed as part of the CSE302 DBMS course.

## Technology Stack
- **Frontend:** React.js (located in the `VoiceEnquirySystem` folder)
- **Backend:** Node.js + Express.js (located in the `VoiceEnquiryBackEnd` folder)
- **Database:** MySQL

## Setup Instructions

1. **Fork the repository** and clone it to your local machine.
2. Install dependencies in both the frontend and backend directories using:
   ```bash
   npm install
   ```
3. Update the database connection details in the `server.js` file to match your host database.
4. Execute the SQL commands provided in the `Database.txt` file to set up the database schema and initial data.
5. Start the server by running:
   ```bash
   node server.js
   ```
   The application will run on the default port: `3000`.

## Notes
- Make sure your MySQL server is running and accessible.
- Ensure that the database credentials in `server.js` are correctly configured.
