# Neuroleap – Full-Stack Conversational AI Web Application

A MERN-based conversational chatbot inspired by ChatGPT, built using the OpenAI API. Developed as part of a full-stack learning initiative using resources from Apna College.

---

## 📌 Project Goal

To create an intelligent, responsive AI chatbot that can understand and generate human-like responses using OpenAI's language model, packaged within a dynamic and scalable web interface.

---

## 🚀 Key Features

- 🤖 Chat with real-time OpenAI responses
- 🔐 JWT-based secure login & registration
- 📜 Maintains session chat history
- 🎨 Responsive UI built with Tailwind CSS
- 📥 API integration for OpenAI GPT-3.5/GPT-4
- ⚙️ Modular and scalable full-stack architecture

---

## 🛠️ Tech Stack

**Frontend:** React.js, Tailwind CSS, Axios  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Authentication:** JSON Web Tokens (JWT)  
**AI Integration:** OpenAI API

---

## 💡 How I Developed It

- Followed Apna College’s MERN stack learning roadmap
- Integrated OpenAI's language API for smart, contextual responses
- Designed a clean chat UI and built reusable components in React
- Implemented user authentication and role-based routing
- Managed API calls securely with Axios and backend routing

---

## ⚙️ How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/triveninelakurthi9/neuroleap.git
cd neuroleap
```

### 2. Install Dependencies

#### Backend

```bash
cd server
npm install
```

#### Frontend

```bash
cd ../client
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in both `/client` and `/server` folders.

#### Example `.env` for Server

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_api_key
```

### 4. Run the Project

#### Backend

```bash
cd server
npm start
```

#### Frontend

```bash
cd ../client
npm start
```

### 5. Open in Browser

Visit: [http://localhost:3000](http://localhost:3000)

---

## 📁 Folder Structure

```
neuroleap/
├── client/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── utils/
│       └── App.jsx
│
├── server/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── server.js
│
├── .env
├── package.json
├── README.md
```
