# onlineVotingSystem
this is a online voting system 
# 🗳️ Online Voting System for Elections

## 📌 Project Overview
This is a simple online voting system built using **HTML**, **CSS**, and **JavaScript**. It aims to provide a secure and accessible voting experience for users, with features like user registration, voting interface, and real-time vote tracking—all implemented on the client side for demonstration purposes.

## 🚀 Features

### 📝 User Registration and Authentication
- Simple user registration form with:
  - Email and password fields
  - Email verification simulation (e.g. alert or message)
  - Password strength validation

### 👤 Voter Profile Management
- Voter profile form to collect:
  - Name
  - Age
  - Address
  - Unique Voter ID (generated on registration)
  - Upload ID (simulated using file input)

### 🗓️ Election Information
- Static election information displayed on the home page:
  - Upcoming election dates
  - Candidate details
  - Issues to vote on
  - FAQs section for guidance

### 🗳️ Voting Interface
- Interactive voting page with:
  - Candidate/issue selection (e.g. radio buttons or checkboxes)
  - Review screen before final submission

### ✅ Vote Casting
- Simulated vote casting with:
  - Confirmation message after casting
  - Prevention of multiple votes per user (using localStorage/sessionStorage)

## 🌟 Unique Features

### 📊 Real-Time Vote Tracking
- Simulated vote tracking with:
  - Confirmation status updates (e.g. progress bar or status indicator)
  - Notifications using JavaScript alerts or modal pop-ups

### 📍 Location Verification
- Use the **Geolocation API** to capture the user's location when voting
  - Display location on confirmation page
  - Store location data (in localStorage for demonstration)

### 🔗 Voting Link Management
- Simulated voting links generated with unique tokens
  - Links expire after **2 minutes** (timer-based disable)
  - Reminder alerts to users before link expiration

## 🔐 Challenging Features (Simulated)
- **Facial Recognition Simulation**:
  - Use the device camera via the HTML `<video>` element (optional)
  - Capture photo on vote submission (simulated snapshot)
  - Display photo for user confirmation
- **Audit Trail (Demo Only)**:
  - Store voting data in localStorage for demonstration
  - Display a log page with timestamps and voter IDs (anonymized)

## ➕ Additional Features
- **Responsive Design**: Fully accessible on mobile and desktop using CSS.
- **Secure Data (Demo)**: Use localStorage and sessionStorage for demonstration only (not secure for production).
- **Feedback System**: Feedback form for users to submit their experience (stored in localStorage).

## 🛠️ Tech Stack
- **HTML5**: Structure the application pages.
- **CSS3**: Style the pages, make the design responsive and accessible.
- **JavaScript (ES6+)**: Handle user interactions, registration, voting logic, geolocation, simulated authentication, and data storage.

## 📖 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/online-voting-system.git
   cd online-voting-system
