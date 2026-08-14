# Campus Issue Reporting and Resolution System (CIRRS)

**Course**: Engineering Capstone Project – 1 (23IE4053R / 23IE4053A)  
**Academic Year**: 2026 - 2027  
**Department**: Department of Computer Science & Engineering (CSE)  
**Repository Name**: `KLH-CSE-2026-27-2420030604-CampusIssueReportingSystem`

---

## 👥 Team Details

* **Supervisor / Guide Name**: K. Bhavya Mam

### Team Members
| S. No. | University ID | Team Member Name | Role |
| :--- | :--- | :--- | :--- |
| 1 | **2420030604** | Chavva Akshay Kumar Reddy | **Team Lead** (Team ID) |
| 2 | **2420030133** | Y. Sai Charan Reddy | Member |
| 3 | **2420030135** | Surrisetti Bhuvanesh | Member |
| 4 | **2420030644** | Eshwar Miyyapuram | Member |

---

## 📝 Abstract

Educational campuses generate a continuous stream of day-to-day operational issues — malfunctioning Wi-Fi routers, faulty classroom electronics, plumbing failures in hostels, unclean restrooms, broken furniture, and irregular transport schedules. At present, most institutions rely on informal channels such as verbal complaints, phone calls, or physical registers maintained by administrative staff to report and track such issues. This process is slow, undocumented, and lacks accountability, frequently resulting in delayed resolution, duplicated complaints, and dissatisfied students and staff.

The **Campus Issue Reporting and Resolution System (CIRRS)** is proposed as a centralized, web-based platform that allows students and staff to report campus-related issues digitally, track their resolution status in real time, and enables administrators to prioritize, assign, and resolve issues efficiently. The system follows a role-based architecture: a student/staff interface for submitting issue reports with category, location, and photo evidence, and an administrator dashboard for tracking, filtering, and resolving reported issues through a transparent status pipeline (`Reported` → `Acknowledged` → `In Progress` → `Resolved`).

The project is developed using **React.js** for the frontend and **Firebase** (Authentication, Firestore Database, Hosting) for the backend, following an **Adaptive Software Engineering** methodology with short, iterative sprint cycles rather than a fixed upfront specification — allowing the system's features to evolve based on real feedback across development stages. The expected outcome is a fully functional, centralized issue-reporting platform that reduces average resolution time, improves accountability, and offers a scalable foundation for future extension across departments or institutions.

---

## 📁 Mandatory Repository Structure

```
├── /src        # Source code files (React frontend components, pages, context, and styles)
├── /docs       # Project documentation, abstract files, design specs, and architectural diagrams
├── /data       # Database schemas, Firestore collection models, and reference datasets
├── /results    # Evaluation metrics, performance benchmark logs, and resolution testing results
├── /reports    # Phase deliverables, review presentation documents, and evaluation progress reports
├── .gitignore  # Excludes environment credentials, build artifacts, and node_modules
└── README.md   # Top-level repository overview and execution manual
```

---

## 🚀 Setup and Execution Instructions

### Prerequisites
Ensure you have the following installed on your local machine:
- [Node.js](https://nodejs.org/) (v16.x or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

### Step 1: Clone the Repository
```bash
git clone https://github.com/tonyboss365/ASE-2420030604-CampusIssueReportingSystem.git
cd ASE-2420030604-CampusIssueReportingSystem
```

### Step 2: Install Dependencies
Navigate to the root directory (or `/src` if separate frontend directory) and install required node modules:
```bash
npm install
```

### Step 3: Configure Environment Variables
Create a `.env` file in the project root directory and configure your Firebase keys (do **NOT** commit `.env` to GitHub as per Norm #8):
```env
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```

### Step 4: Run the Local Development Server
Start the local React development server:
```bash
npm start
```
The application will be accessible at `http://localhost:3000`.

### Step 5: Build for Production
To generate an optimized production build:
```bash
npm run build
```

---

## 📌 Current Phase Status

- **Current Phase**: **Review-1 (Phase 1 Complete)**
- **Deliverable Tag**: `review-1`
- **Milestone Highlights**:
  - [x] Mandatory folder structure initialized (`/src`, `/docs`, `/data`, `/results`, `/reports`).
  - [x] Official Project Abstract uploaded & verified.
  - [x] Standard `README.md` and repository compliance completed.
  - [x] Git release tag `review-1` applied.
  - [ ] Review-2 Prototype UI & Firebase Auth Integration (*Upcoming*).
