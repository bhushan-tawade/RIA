# RIA – Real-time Interactive Assistant

**RIA** is a real-time chatbot powered by the **Gemini API**, designed to facilitate intelligent, natural conversations with users. Built with **React.js** and **Node.js**, and styled using **Tailwind CSS**, this project demonstrates a seamless full-stack integration of AI with modern web technologies.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/bhushan-tawade/RIA.git
cd RIA
```

### 2. Install Frontend Dependencies

```bash
cd frontend
npm install
```

### 3. Install Backend Dependencies

```bash
cd ../backend
npm install
```

### 4. Create Environment Variables

Inside the `backend` directory, create a `.env` file with the following:

```env
PORT=5000
GEMINI_API_KEY=your_gemini_api_key
MONGODB_URI=your_mongodb_connection_string
```

---

## 🧠 Running the Application

### 1. Start the Backend Server

```bash
cd backend
npm run dev
```

### 2. Start the Frontend Development Server

```bash
cd frontend
npm run dev
```

The application will be available at: [http://localhost:5173](http://localhost:5173)

---

## 📡 API Endpoints

### 🔐 Authentication

- `POST /login` - User login  
- `POST /signup` - User registration

### 💬 Chat

- `GET /history/:userId` - Get user's chat history  
- `POST /chat` - Send a message to AI  
- `DELETE /history/:userId` - Clear chat history

---


## 🙏 Acknowledgments

- Built with **React.js** and **Node.js**
- Styled using **Tailwind CSS**
- AI capabilities powered by **Gemini API**

