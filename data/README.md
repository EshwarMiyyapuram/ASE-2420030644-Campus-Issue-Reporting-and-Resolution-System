# Data & Database Schema (`/data`)

This folder contains database reference schemas, mock datasets, and data dictionary documentation for the **Campus Issue Reporting and Resolution System (CIRRS)**.

## Backend Data Source
The primary cloud database used by CIRRS is **Google Cloud Firebase Firestore**.

## Firestore Collections Schema
### 1. `users` Collection
- `uid`: string (Firebase Auth UID)
- `name`: string
- `email`: string
- `role`: string (`student` | `staff` | `admin`)
- `createdAt`: timestamp

### 2. `issues` Collection
- `issueId`: string (Auto-generated UUID / Firestore ID)
- `title`: string
- `category`: string (`WiFi/Network`, `Electronics`, `Plumbing`, `Restrooms`, `Furniture`, `Transport`)
- `location`: string (e.g., Block A - Room 204)
- `description`: string
- `photoUrl`: string (Firebase Storage URL)
- `status`: string (`Reported` -> `Acknowledged` -> `In Progress` -> `Resolved`)
- `submittedBy`: string (User UID)
- `assignedTo`: string (Admin/Staff UID)
- `createdAt`: timestamp
- `updatedAt`: timestamp
