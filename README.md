# myPortfolio - Full Stack Developer Portfolio

Welcome to my professional portfolio! This project showcases my skills, achievements, and projects as a Full Stack MERN Developer. It features a modern, responsive design with a glassmorphic aesthetic and includes an administrative interface for managing content.

## 🚀 Live Demo
*(Optional: Add a link to your hosted portfolio here)*

---

## 🛠 Tech Stack

### Frontend
- **HTML5 & Vanilla JavaScript**
- **Tailwind CSS** (via CDN)
- **Flowbite** (UI Components)
- **Font Awesome** & **Devicon** (Icons)
- **SweetAlert2** (Interactive Modals)

### Backend
- **Node.js** & **Express.js**
- **MongoDB** (via Mongoose)
- **Multer** (File Uploads)
- **Nodemailer** (Email Services)
- **CORS** & **Dotenv**

---

## ✨ Features

- **Responsive Design**: Optimized for all devices with a dedicated mobile navigation system.
- **Glassmorphic UI**: Premium look and feel with blurred backgrounds and sleek transitions.
- **Project Showcase**: Dynamically loaded project cards with live links and demo videos.
- **Achievements & Certifications**: Grid view of awards with support for PDF and Word document previews.
- **Admin Management**: Secure interface to Add, Edit, and Delete projects and achievements.
- **Contact Integration**: Fully functional "For Hire" and contact forms that send emails directly to the owner.
- **Skill Marquees**: Animated showcase of professional technical expertise.

---

## 📂 Project Structure

```text
myPortfolio/
├── Portfolio/              # Frontend Assets & Pages
│   ├── index.html          # Home Page
│   ├── about.html          # About Page
│   ├── projects.html       # Projects Showcase
│   ├── achievements.html   # Awards & Certifications
│   ├── contact.html        # Contact Page
│   ├── Images/             # Static Images
│   └── Resume/             # Downloadable CVs (PDF/Word)
└── Portfolio-backend/      # Backend API Service
    ├── server.js           # Express Server Entry Point
    ├── uploads/            # Directory for user-uploaded assets
    ├── models/             # Database Schemas
    └── .env                # Environment Variables
```

---

## ⚙️ Installation & Setup

### 1. Prerequisites
- [Node.js](https://nodejs.org/) installed
- [MongoDB](https://www.mongodb.com/) account/instance

### 2. Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd Portfolio-backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file based on `.env.example`:
   ```bash
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   EMAIL_USER=your_email@gmail.com
   EMAIL_PASS=your_app_specific_password
   ADMIN_PASSWORD=your_secure_admin_password
   ```
4. Start the server:
   ```bash
   npm start
   ```

### 3. Frontend Setup
The frontend is built with static HTML files. You can:
- Open `Portfolio/index.html` directly in your browser.
- Use a local server extension (like VS Code **Live Server**).
- Ensure the `API_BASE` in the scripts (usually `http://localhost:5000`) matches your running backend.

---

## 🛡 Admin Usage

To manage projects or achievements:
1. Navigate to the **Projects** or **Achievements** page.
2. Click the **"Add"** button.
3. You will be prompted for the **Admin Password** (set in your backend `.env` file).
4. Once verified, you can create, update, or delete entries.

---

## 📧 Contact

**Kristian Koome**  
Nairobi, Kenya  
Email: [kristian.koome@outlook.com](mailto:kristian.koome@outlook.com)

---


