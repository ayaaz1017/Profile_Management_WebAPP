# Full-Stack Profile Viewer Application

This project is a full-stack web application that allows users to view profiles and explore their associated addresses interactively on a map. The application includes features for profile management, search, and filtering, as well as an admin panel for adding, editing, or deleting profiles.

---

## Features

- **Profile Display:** View profiles with details like name, photo, and description.
- **Interactive Mapping:** Explore addresses on a map with dynamic markers.
- **Admin Dashboard:** Manage profiles with options to add, edit, or delete.
- **Search and Filter:** Search profiles by name or other attributes.
- **Responsive Design:** Fully functional across devices, including smartphones and tablets.
- **Error Handling:** Robust mechanisms to handle invalid inputs and failed requests.
- **Loading Indicators:** Feedback provided during data fetch and map rendering.

---

## Technology Stack

### Frontend
- React.js
- Google Maps API

### Backend
- Node.js with Express.js
- MongoDB

---

## Installation and Setup

### Prerequisites
- Node.js
- MongoDB
- Google Maps API key

### Steps

#### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-folder>
```

#### 2. Backend Setup
```bash
cd backend
npm install
```
- Ensure MongoDB is running locally.
- Start the backend server:
```bash
node index.js
```
The server will run on `http://localhost:5000`.

#### 3. Frontend Setup
```bash
cd frontend
npm install
```
- Update the `Google Maps API key` in `frontend/src/components/Map.js`.
- Start the frontend:
```bash
npm start
```
The frontend will run on `http://localhost:3000`.

---

## Usage

- **Frontend:**
  - Visit `http://localhost:3000` for the profile viewing interface.
  - Visit `http://localhost:3000/admin` for the admin dashboard.

- **Admin Actions:**
  - Add, edit, or delete profiles.

- **Search and Filter:**
  - Use the search bar to find specific profiles.

- **Interactive Map:**
  - Click the "Summary" button on any profile to view its location on the map.

---

## Project Structure

### Backend (`/backend`)
- `index.js`: Express server and MongoDB connection.
- Profile schema and API routes.

### Frontend (`/frontend`)
- **Components:**
  - `ProfileList.js`: Displays profiles and integrates search.
  - `ProfileCard.js`: Individual profile cards.
  - `Map.js`: Interactive map using Google Maps API.
  - `AdminDashboard.js`: Admin interface for managing profiles.

---

## Troubleshooting

1. **Frontend Issues:**
   - Ensure all dependencies are installed (`npm install`).
   - Check the browser console for errors.

2. **Backend Issues:**
   - Verify MongoDB is running locally.
   - Test API endpoints using tools like Postman.

3. **Map Not Displaying:**
   - Ensure the Google Maps API key is valid and unrestricted for your domain.
   - Check the browser console for API-related errors.

---
