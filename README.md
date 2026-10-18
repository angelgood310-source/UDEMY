# 🎓 Udemy Clone - E-Learning Platform

A full-stack, responsive e-learning web application that mirrors the core functionalities of Udemy. This platform allows instructors to publish video courses and enables students to enroll, track progress, and learn seamlessly.

## 🚀 Key Features

### 👨‍🎓 For Students
* **Course Discovery:** Advanced search, category filtering, and dynamic ratings/reviews.
* **Video Streaming:** A custom video player with progress tracking and automatic "mark as completed" status.
* **Shopping Cart & Checkout:** Add multiple courses to a cart with secure payment gateway integration.
* **Dashboard:** A personalized learning portal displaying enrolled courses and overall progress.

### 👨‍🏫 For Instructors
* **Instructor Dashboard:** Real-time analytics showing total students enrolled, ratings, and revenue generated.
* **Course Creator:** A step-by-step curriculum builder to upload videos, organize sections, and set pricing.

### 🛠️ Tech Stack

* **Frontend:** React.js / Next.js, Tailwind CSS, Redux Toolkit (State Management)
* **Backend:** Node.js, Express.js
* **Database:** MongoDB / PostgreSQL
* **Authentication:** JWT (JSON Web Tokens) or Firebase Auth
* **Media Storage:** Cloudinary or AWS S3 (for video and thumbnail hosting)
* **Payments:** Stripe API integration

## 🏁 Getting Started

Follow these steps to set up the project locally.

### Prerequisites
* Node.js installed on your machine
* A database instance (MongoDB Atlas / PostgreSQL)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd udemy-clone
   ```

2. **Install dependencies:**
   ```bash
   # Install backend dependencies
   cd backend && npm install
   
   # Install frontend dependencies
   cd ../frontend && npm install
   ```

3. **Set up Environment Variables:**
   Create a `.env` file in the root of both the backend and frontend folders using the `.env.example` templates provided.

4. **Run the application:**
   ```bash
   # From the root directory (or run separately in their respective folders)
   npm run dev
   ```
