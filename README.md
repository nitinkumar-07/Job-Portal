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
<img width="1920" height="1080" alt="Screenshot (493)" src="https://github.com/user-attachments/assets/12dd757f-a81e-4a1e-adda-5e7388484807" />
</td>

<td align="center">
<img width="1920" height="1080" alt="Screenshot (494)" src="https://github.com/user-attachments/assets/3cd30ec2-5b4e-495c-b1e1-13af2f59eb72" />
</td>
</tr>

<tr>
<th>Jobs</th>
<th>Login</th>
</tr>

<tr>
<td align="center">
<img width="1920" height="1080" alt="Screenshot (495)" src="https://github.com/user-attachments/assets/cc9a57b3-f4e4-430a-b953-dd5e61c352bb" />
</td>

<td align="center">
<img width="1920" height="1080" alt="Screenshot (496)" src="https://github.com/user-attachments/assets/fc8652d7-f486-4485-9912-e6095f419fd5" />
</td>
</tr>


<tr>
<th>Profile</th>
<th>Applied Jobs</th>
</tr>

<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/c88cffdb-f8e2-4046-9dc5-63f1ec677fda" width="450">
</td>

<td align="center">
<img src="https://github.com/user-attachments/assets/9e8079f1-e214-4d8a-9a24-51c78532e84a" width="450">
</td>
</tr>

<tr>
<th>Recruiter Job Dashboard</th>
<th>Company Dashboard</th>
</tr>

<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/9c94e634-71bf-4aef-bf17-3eaf926e6582" width="450">
</td>

<td align="center">
<img src="https://github.com/user-attachments/assets/d3eb0687-d71b-4cf3-afae-ea794fdc67f8" width="450">
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
