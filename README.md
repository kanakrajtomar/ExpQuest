# 🏠 ExpQuest – Smart Room Booking Platform

**ExpQuest** is a modern and modular room booking system designed to simplify PG/hostel management. It enables owners to manage room availability, automate document verification, track vacant rooms building-wise, and send rent notifications with ease. Built with scalability and integration in mind.

---

## 🚀 Features

- ✅ **Owner Dashboard**
  - Manually update room status (Booked/Vacant)
  - View all rooms by building

- 🏢 **Vacant Room Tracker**
  - Building-wise room availability summary

- 🔐 **Document Verification Automation**
  - Upload and simulate verification of tenant documents
  - Easily expandable to integrate real-time AI verification

- 🔔 **Rent Notification System** (Upcoming)
  - Schedule rent reminders (email/SMS support ready)

- 🗺️ **Virtual PG Tour** (Upcoming)
  - Grid-based view of rooms with live status

---

## 🛠️ Tech Stack

- **Frontend**: React.js (Planned)
- **Backend**: Node.js + Express.js
- **Database**: MongoDB / Supabase
- **Authentication**: JWT or basic auth (planned)

---

## 📂 Folder Structure

expquest/ ├── backend/ │ ├── controllers/ │ ├── models/ │ ├── routes/ │ ├── services/ │ └── server.js ├── frontend/ (coming soon) └── README.md

yaml
Copy
Edit

---

## 🔧 Setup Instructions

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/expquest.git
cd expquest
Install Dependencies

bash
Copy
Edit
cd backend
npm install
Configure Environment Variables Create a .env file in the backend folder with:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
Start the Server

bash
Copy
Edit
npm start
📡 API Endpoints (Backend)
Method	Endpoint	Description
GET	/api/rooms	Get list of all rooms
PATCH	/api/rooms/:id/status	Update room status (booked/vacant)
GET	/api/buildings/vacant	Vacant rooms per building
POST	/api/documents/upload	Upload tenant documents for verification
GET	/api/documents/:id/status	Get document verification status
🧠 Future Enhancements
Virtual room tour with interactive floor plan

Real-time room status updates

Role-based access for owners, tenants, admins

Payment gateway integration

Mobile app (React Native or Flutter)

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

📄 License
MIT License. Feel free to use and customize.

🙌 Developed With Love
Crafted for smart PG/hostel management.
ExpQuest – Experience Booking, the Smart Way.

vbnet
Copy
Edit

Let me know if you'd like this in Hindi too or want a GitHub badge/CI/CD section added!
