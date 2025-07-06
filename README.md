# YapSpace

YapSpace is a real-time chat application that allows users to connect and communicate instantly. Built with a modern frontend and backend stack, it supports live messaging, theme switching, and user presence indicators with a clean and responsive UI.

---

## ✨ Features

### 💬 Real-time Messaging

- Built using **Socket.IO** for seamless, low-latency communication.
- Instantly receive and send messages with live updates.

### 🔐 User Authentication

- Secure **signup**, **login**, and **logout** flows.
- JSON Web Token (JWT)-based session management.

### 👤 Profile Management

- Update your **profile picture** (supports image upload via **Cloudinary**).

### 🎨 Theming

- Choose from multiple beautiful **DaisyUI themes**: Light, Dark, Cupcake, Dracula, and more.
- Instant **theme preview** from the settings page.

### 🖼️ UI/UX Highlights

- Built with **TailwindCSS** for utility-first styling.
- Uses **Lucide Icons** for a clean, modern interface.
- Fully **responsive design** for all devices.
- **Toast notifications** for smooth, real-time user feedback.

---

## 🛠 Tech Stack

**Frontend:**

- React
- Socket.IO Client (real-time communication)
- Tailwind CSS
- DaisyUI (UI components)
- Zustand (state management)
- React Router
- Axios
- React Hot Toast

**Backend:**

- Node.js + Express
- MongoDB + Mongoose
- Socket.IO (real-time messaging)
- Cloudinary (image uploads)
- JSON Web Tokens (JWT)

---

## 📦 Installation

### 1. Clone the Repository

```
git clone https://github.com/Videh75/YapSpace.git
cd YapSpace
```

### 2. Setup .env file

```
PORT=5001
MONGODB_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 3. Build the app

```
npm run build
```

### 4. Start the app

```
npm start
```
