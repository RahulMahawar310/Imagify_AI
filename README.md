# 🎨 Imagify AI

Imagify AI is a full-stack **text-to-image generator** built on the **MERN stack**, powered by the **ClipDrop API**. Users can describe an image in plain text and Imagify instantly generates a high-quality AI-rendered image from that prompt.

🔗 **Live:** ([https://github.com/RahulMahawar310/Imagify_AI](https://imagify-aiclient.onrender.com))

---

## ✨ Features

- 🖼️ **Text-to-Image Generation** — Convert natural language prompts into AI-generated images using the ClipDrop API
- 🔐 **User Authentication** — Secure signup/login with JWT-based sessions
- 💳 **Credit-Based System** — Users consume credits for each image generated, with options to top up
- 📱 **Responsive UI** — Built with Tailwind CSS v4 for a clean experience across devices
- ⚡ **Fast & Modern Frontend** — React + Vite for a snappy development and user experience
- 🗄️ **MongoDB Data Storage** — User accounts, credits, and history stored in MongoDB

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React, Vite, Tailwind CSS v4 |
| Backend | Node.js, Express.js |
| Database | MongoDB (Mongoose) |
| Authentication | JSON Web Tokens (JWT) |
| Image Generation | ClipDrop API |

---

## 📂 Project Structure

```
Imagify_AI/
├── client/          # React frontend (Vite + Tailwind CSS)
│   ├── src/
│   └── ...
├── server/          # Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── ...
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- A [MongoDB](https://www.mongodb.com/) database (local or Atlas)
- A [ClipDrop API](https://clipdrop.co/apis) key

### 1. Clone the repository

```bash
git clone https://github.com/RahulMahawar310/Imagify_AI.git
cd Imagify_AI
```

### 2. Set up the backend

```bash
cd server
npm install
```


Start the backend server:

```bash
npm run server
```

### 3. Set up the frontend

```bash
cd ../client
npm install
```


Start the frontend:

```bash
npm run dev
```

The app should now be running at `http://localhost:5173` (or the port shown in your terminal).

---

## 🚀 Usage

1. Sign up / log in to your account
2. Enter a text prompt describing the image you want
3. Click **Generate** — Imagify AI sends the prompt to the ClipDrop API and returns your image
4. Download or save your generated image
5. Purchase additional credits when you run low

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](https://github.com/RahulMahawar310/Imagify_AI/issues) or open a pull request.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Rahul Mahawar**
- GitHub: [@RahulMahawar310](https://github.com/RahulMahawar310)
- Portfolio: [rahulmahawar310.github.io/Portfolio](https://rahulmahawar310.github.io/Portfolio/)
