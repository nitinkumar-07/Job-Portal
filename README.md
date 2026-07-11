<div align="center">

# 💼 TalentHub - Full-Stack Job Portal

🚀 **TalentHub** is a production-ready, feature-rich Full-Stack Job Portal built using the **MERN Stack** (MongoDB, Express.js, React, Node.js). This project was engineered to create a seamless, robust, and scalable platform bridging the gap between talented job seekers and recruiters.

### 🚀 Live Demo
👉 https://job-portal-backend-tkdn.onrender.com/

</div>

---


## 📝📌 Project Overview

**TalentHub** is a modern, responsive full-stack web application designed to streamline the hiring workflow. The platform addresses the core needs of the modern job market by providing dual-role capabilities under a single integrated system. 

The application enables **Job Seekers** to seamlessly build profiles, explore real-time listings with smart multi-filtering, and track application progress on interactive dashboards. Simultaneously, it empowers **Recruiters** with an employer-focused control suite to register companies, manage job lifecycles (post, update, or archive openings), and review candidate applications efficiently. Optimized for production, the entire system utilizes robust REST APIs, global state hydration via Redux, and high-availability server setups to deliver an instantaneous, enterprise-grade user experience.

---

# ✨ Features

## 👨‍🎓 Job Seeker Features

| Feature | Feature |
|---------|---------|
| ✅ Secure Signup/Login | ✅ JWT Authentication |
| ✅ Protected Routes | ✅ Update Profile |
| ✅ Upload Resume (PDF) | ✅ Upload Profile Photo |
| ✅ Add Skills & Bio | ✅ Browse Jobs |
| ✅ Search Jobs | ✅ Filter Jobs |
| ✅ Job Details Page | ✅ One Click Apply |
| ✅ Track Applications | ✅ View Application Status |
| ✅ Responsive Dashboard | | 

---

## 🏢 Recruiter Features

| Feature | Feature |
|---------|---------|
| ✅ Recruiter Login | ✅ Company Registration |
| ✅ Company Management | ✅ Upload Company Logo |
| ✅ Create Jobs | ✅ Update Jobs |
| ✅ Delete Jobs | ✅ View Posted Jobs |
| ✅ View Applicants | ✅ Accept/Reject Applications |
| ✅ Recruiter Dashboard | |

---

## 🔐 Authentication & Security

| Feature | Feature |
|---------|---------|
| ✅ JWT Authentication | ✅ HTTP Only Cookies |
| ✅ Password Hashing (bcrypt) | ✅ Protected APIs |
| ✅ Role-Based Authorization | ✅ Input Validation |
| ✅ Secure File Upload | |

---

## 📂 Resume & Image Upload

- Cloudinary Integration
- Resume Upload
- Profile Image Upload
- Company Logo Upload
- Optimized Media Storage

---

## 🔍 Job Search

| Feature | Feature |
|---------|---------|
| 🔎 Search by Keyword | 📍 Filter by Location |
| 🏢 Filter by Company | 💼 Filter by Job Role |
| ⚡ Instant Search Results | 📱 Responsive Job Cards |


---

## 📊 Dashboards

| 👨‍🎓 Student Dashboard | 🏢 Recruiter Dashboard |
|------------------------|------------------------|
| 👤 Profile Overview | 🏢 Total Companies |
| 📄 Resume Preview | 💼 Posted Jobs |
| 📋 Applied Jobs History | 👥 Applicants List |
| ⚙️ Account Management | 📊 Company Management |

---

# 🛠 Tech Stack

| 🎨 Frontend | ⚙️ Backend |
|-------------|------------|
| React.js | Node.js |
| Vite | Express.js |
| Redux Toolkit | MongoDB |
| React Router DOM | Mongoose |
| Tailwind CSS | JWT |
| Shadcn UI | bcryptjs |
| Axios | Multer |
| Lucide React | Cloudinary |
| | Cookie Parser |
| | CORS |

---

## 📂 Folder Structure

The repository is structured into two main directories decoupling the client interface and server-side REST APIs:

```text
├── backend/
│   ├── controller/         # Core backend logic for users, jobs, and companies
│   ├── middleware/         # Custom authentication and route protection logics
│   ├── models/             # Mongoose schemas representing database collections
│   ├── routes/             # API endpoint route mappings
│   ├── utils/              # Server-side utility functions and helper methods
│   └── index.js            # Entry configuration point for the Node server
│
├── frontend/
│   ├── src/
│   │   ├── assets/         # Static images, icons, and media files
│   │   ├── components/     # UI layer broken into modular modules:
│   │   │   ├── adminCompo...  # Admin & recruiter control management interfaces
│   │   │   ├── authentication # Login, signup, and validation containers
│   │   │   └── component_lite  # Core portal views (Home, Browse, JobCards, AppliedJobs, FilterCard)
│   │   ├── hooks/          # Custom hooks handling asynchronous data workflows
│   │   ├── lib/            # External library custom wrappers and instantiations
│   │   ├── redux/          # Global application store slices and configurations
│   │   ├── utils/          # Client-side utility functions and formatting helpers
│   │   ├── App.css / App.jsx# Core design mappings and routing orchestrations
│   │   ├── index.css       # Tailwind base injection stylesheet
│   │   └── main.jsx        # App mounting and production environment bootstrap
│   ├── .gitignore          # Version control ignore lists
│   └── components.json     # Architectural UI setup registry config file
└── README.md               # Production architecture manual
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/job-portal.git
```

Move into project

```bash
cd job-portal
```

---

## Install Dependencies

Frontend

```bash
cd frontend
npm install
```

Backend

```bash
cd backend
npm install
```

---

## Environment Variables

Create a `.env` file inside the server folder.

```env
PORT=

MONGO_URI=

JWT_SECRET=

CLOUD_NAME=

CLOUD_API=

API_SECRET=

CLIENT_URL=
```

---

## Run Backend

```bash
npm run dev
```

---

## Run Frontend

```bash
npm run dev
```

# 📸 Screenshots

<table align="center">
<tr>
<th>Home</th>
<th>Home (Jobs Section)</th>
</tr>

<tr>
<td align="center">
<img width="1917" height="1017" alt="Screenshot 2026-07-10 210207" src="https://github.com/user-attachments/assets/c7f74273-19d0-475e-8b48-5591d6c2f60f" />
</td>

<td align="center">
<img width="1920" height="1014" alt="Screenshot (494)" src="https://github.com/user-attachments/assets/41e9e6d6-b63c-419e-8f09-497a2208c055" />
</td>
</tr>

<tr>
<th>Jobs</th>
<th>Login</th>
</tr>

<tr>
<td align="center">
<img width="1920" height="1014" alt="Screenshot (495)" src="https://github.com/user-attachments/assets/ee8fb414-4735-4832-a8dd-9adc59c2c17d" />
</td>

<td align="center">
<img width="1920" height="1016" alt="Screenshot (496)" src="https://github.com/user-attachments/assets/897389e7-b6d6-4a08-98d9-5c9982e726c3" />
</td>
</tr>


<tr>
<th>Profile</th>
<th>Applied Jobs</th>
</tr>

<tr>
<td align="center">
<img width="1920" height="1017" alt="Screenshot (497)" src="https://github.com/user-attachments/assets/ff61d571-b6a9-410d-b3de-4050f8839689" />
</td>

<td align="center">
<img width="1920" height="1017" alt="Screenshot (498)" src="https://github.com/user-attachments/assets/2d716255-a595-4415-ab50-1473e56c7ab2" />
</td>
</tr>

<tr>
<th>Recruiter Job Dashboard</th>
<th>Company Dashboard</th>
</tr>

<tr>
<td align="center">
<img width="1920" height="1024" alt="Screenshot (500)" src="https://github.com/user-attachments/assets/6caebc94-59ad-40f4-afb5-f7ec0a466e4e" />
</td>

<td align="center">
<img width="1920" height="1021" alt="Screenshot (499)" src="https://github.com/user-attachments/assets/5422c6db-9dc7-423f-8222-74dd73188f3b" />
</td>
</tr>
</table>

# 🎯 Major Functionalities

| Functionality | Functionality |
|--------------|--------------|
| ✅ User Authentication | ✅ Recruiter Authentication |
| ✅ Company Management | ✅ Job Posting |
| ✅ Job Editing | ✅ Job Searching |
| ✅ Job Filtering | ✅ Resume Upload |
| ✅ Profile Management | ✅ Apply for Jobs |
| ✅ Applicant Tracking | ✅ Protected Routes |
| ✅ Student Dashboard | ✅ Recruiter Dashboard |
| ✅ Responsive UI | |

---

# 👨‍💻 Author

**Nitin Kumar**

💼 MERN Stack Developer

GitHub:
https://github.com/nitinkumar-07

LinkedIn:
https://www.linkedin.com/in/nitin-kumar-491813336/

---

# ⭐ Support

If you like this project, don't forget to ⭐ the repository.

It motivates me to build more amazing projects.

---

<div align="center">

Made with ❤️ using MERN Stack

</div>
