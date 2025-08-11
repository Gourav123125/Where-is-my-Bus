# 🚍 Where is My Bus
*Real-Time Bus Tracking & Scheduling by Trackila Smart Innovations*
A smart public transport platform offering live bus tracking, accurate ETAs, and route info to make commuting faster, safer, and more reliable.

✨ Features  
🗺 **GPS Live Tracking** – View buses in real time on an interactive map  
⏱ **AI-Powered ETA** – Arrival predictions using traffic & route data  
📍 **Route & Stop Information** – Detailed route maps and stop lists  
🔔 **Instant Alerts** – Delays, breakdowns, or route changes in real time  
🔎 **Search & Filter** – Find buses by route number, source, or destination  
📂 **Offline Access** – Access saved schedules without internet  
📊 **Admin Dashboard** – Fleet and schedule management tools  
🌗 **Responsive Design** – Optimized for mobile, tablet, and desktop  
🔐 **Secure Authentication** – JWT-based login & access control  
📩 **Feedback System** – Submit suggestions and report issues instantly  

---

🛠️ Tech Stack  

| Layer         | Technology                                      |
|---------------|-------------------------------------------------|
| Frontend      | Flutter (Mobile), React.js (Web Dashboard)      |
| Backend       | Node.js, Express.js                             |
| Database      | MongoDB Atlas                                   |
| Real-Time     | WebSockets                                      |
| Mapping       | Google Maps API / OpenStreetMap                 |
| Notifications | Firebase Cloud Messaging                        |
| Auth          | JSON Web Tokens (JWT)                           |
| Styling       | Tailwind CSS / Material UI                      |
| Deployment    | Netlify (Dashboard), Render (Backend), Play Store (Mobile) |

📂 Project Structure
where-is-my-bus/
├── frontend/               # Flutter mobile app
│   ├── lib/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   └── main.dart
│   └── pubspec.yaml
│
├── dashboard/              # React.js admin dashboard
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   └── tailwind.config.js
│
├── backend/                # Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── .env                     # Environment variables
├── README.md
└── package.json
🧑‍💻 Local Development Setup
1. Clone the Repo
git clone https://github.com/your-username/where-is-my-bus.git
cd where-is-my-bus
2. Install Frontend (Mobile) Dependencies
cd frontend
flutter pub get
3. Install Dashboard Dependencies
   cd ../dashboard
npm install
4. Install Backend Dependencies
   cd ../backend
npm install
5. Configure Environment Variables
   Create a .env file inside the backend/ directory:
   PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
GOOGLE_MAPS_API_KEY=your_maps_key
FIREBASE_CONFIG=your_firebase_config

6. Start Development Servers
Open three terminals:
Terminal 1 – Backend:
cd backend
npm run dev
Terminal 2 – Dashboard:
cd dashboard
npm run dev
Terminal 3 – Mobile App:
cd frontend
flutter run
App runs at:
Mobile: via emulator or device
Dashboard: http://localhost:5173
API: http://localhost:5000
🧪 Testing & QA
Manual testing has been performed on:

✅ Chrome, Firefox, Brave browsers
✅ Android & iOS devices
✅ Multiple screen sizes via DevTools
✅ Firebase push notification sandbox
✅ Google Maps API integration test

Automated testing is planned for future releases.

🙋‍♂️ Contribution Guidelines
We welcome contributions from GSSoC '25 participants and the open-source community.

To contribute:

Fork the repo

Create a new branch (git checkout -b feature-name)

Commit changes (git commit -m 'Add new feature')

Push branch (git push origin feature-name)

Open a Pull Request
📜 License
This project is licensed under the MIT License.
Feel free to use, modify, and distribute with proper attribution.
🤝 Acknowledgements

Inspired by the need for smart, efficient public transport solutions

Google Maps API for real-time mapping

Firebase Cloud Messaging for instant alerts

Open-source contributors & GSSoC community

