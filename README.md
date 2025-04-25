# AcademicApp
Academic Resource Hub

A centralized web application for students of Kongu Engineering College to access academic resources, certification courses, and collaborate with peers—all through a secure institution-specific login.

 Team Members:
 Pooja E
 Rohini Devi T P
 M.M. Suroopika

🔍 Overview
The Academic Resource Hub simplifies access to:

📘 Syllabi

❓ Question Banks

📗 E-books

🏆 Certification Courses (with student reviews)

💬 Peer Collaboration and Preferences

Built with a modern tech stack to ensure scalability, real-time updates, and a user-friendly experience.

⭐ Key Features
🔐 User Authentication via @kongu.edu emails

📂 Downloadable & searchable syllabi, e-books, and question banks

💡 Course recommendations based on user preferences

📊 Analytics dashboard for admins

📬 Real-time grievance submission and status tracking

📝 Admin can upload resources, add quizzes, and view users

🌐 Multi-language & responsive design

🔐 User Authentication
Secure login via Kongu.edu emails

Role-based access: Student, Admin, Instructor

Email verification and password recovery

JWT-based token handling for secure sessions

🛠️ Technologies Used

Layer	Tech Stack
Frontend	React.js, Ant Design, JSX, CSS
Backend	Node.js, Express.js
Database	MongoDB (Cloud - MongoDB Atlas)
Hosting	Vercel / Netlify (Frontend), Render / Railway (Backend)
Authentication	Firebase / Custom JWT Handling
Dev Tools	Visual Studio Code, ESLint, Prettier
🖼️ Screenshots

📸 Screenshot	Description
User registration with department dropdown
Secure login form
Download resources and search
Upload materials and manage users
Take multiple-choice quizzes

⚙️ Installation Instructions
bash
Copy
Edit
# 1. Clone the repository
git clone https://github.com/your-username/academic-resource-hub.git
cd academic-resource-hub

# 2. Install dependencies for backend and frontend
cd backend
npm install

cd ../frontend
npm install

# 3. Start backend server
cd ../backend
npm start

# 4. Start frontend
cd ../frontend
npm start
🧠 Don't forget to set up .env files for backend JWT keys and MongoDB URI.

✅ How to Use

Register with your kongu.edu email

Login and access the dashboard

Download syllabi, question banks, and e-books

Explore and enroll in rated certification courses

Take quizzes and collaborate with peers

📈 Future Enhancements

AI-based course recommendations

Chat-based peer discussion

Push notifications & progress tracking

Mobile app version
