# 🚀 Lost & Found

**Lost & Found** is a full-stack MERN (MongoDB, Express, React, Node.js) application designed to help users report and recover lost items. It allows users to post details about lost or found items, including images, locations, and descriptions. The system intelligently matches items based on proximity and similarity, enabling easy communication between item owners and finders.

Images are stored securely using **AWS S3**, ensuring scalability and reliability.

---

## 📁 Project Structure

```
Lost-and-Found/
│
├── back/           # Backend (Express, MongoDB)
│   └── npm start   # Starts the backend server
│
├── front/          # Frontend (React)
│   └── npm start   # Starts the React development server
│
├── .env.sample     # Sample environment configuration
├── .gitignore      # Git ignored files
└── README.md       # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/syedasufia-693/Lost-and-Found.git
cd Lost-and-Found
```

### 2. Setup Environment Variables

* Copy the sample `.env.sample` file and update the values with your configuration:

```bash
cp .env.sample back/.env
cp .env.sample front/.env
```

* Fill in the necessary variables like:

  * MongoDB connection string
  * AWS S3 credentials and bucket name
  * Any JWT or session secret keys

### 3. Install Dependencies

#### Backend

```bash
cd back
npm install
```

#### Frontend

```bash
cd ../front
npm install
```

### 4. Start the Application

#### Backend

```bash
cd ../back
npm start
```

#### Frontend

```bash
cd ../front
npm start
```

The frontend will usually run on `http://localhost:3000` and backend on `http://localhost:5000` (or as configured).

---

## 🛠 Features

* 🔍 Report lost or found items
* 📷 Upload item images to AWS S3
* 📍 Location-based item matching
* 💬 Easy communication between users
* 🧾 Secure and environment-configurable setup

---

## 📦 Tech Stack

* **Frontend**: React, Axios
* **Backend**: Node.js, Express, MongoDB
* **Cloud Storage**: AWS S3 (for image uploads)
* **Others**: JWT Authentication, REST APIs

---

## 📄 License

This project is licensed under the MIT License.
