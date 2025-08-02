# 🤖 deepseek-clone

A fully functional **Deepseek AI clone** built using **Next.js** and **Clerk authentication**, designed to provide a sleek chat experience with an intelligent AI assistant. This project includes features like chat history, renaming, deletion, and more — all wrapped in a responsive UI! 🚀

---

## ✨ Features

- 💬 Chat with **Deepseek AI**
- 📂 Fetch recent chat history
- 📝 Rename previous chats
- ❌ Delete chats
- 🔐 Clerk-powered login
- 📱 Fully responsive design

---

## 🛠️ Tech Stack

| Tech                | Usage                  |
| ------------------- | ---------------------- |
| **Next.js**         | Frontend framework     |
| **Clerk**           | Authentication         |
| **Axios**           | API calls              |
| **Mongoose**        | MongoDB schema & model |
| **Prism.js**        | Code snippet styling   |
| **React Hot Toast** | Toast notifications    |
| **React Markdown**  | Markdown rendering     |
| **Svix**            | Webhook management     |
| **useContext**      | Global state handling  |

---

## 🚀 Getting Started

Follow these simple steps to get the project up and running locally:

### 1. 📦 Clone the Repository

```
git clone https://github.com/tayyab-004/deepseek-clone.git
cd deepseek-clone
```

### 2. 🧪 Set Up Environment Variables

Create a `.env` file in the root directory and add the following environment variables:

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
MONGODB_URI=your_mongo_db_uri
SIGNING_SECRET=your_svix_signing_secret
DEEPSEEK_API_KEY=your_deepseek_api_key
```

### 3. 📦 Install Dependencies

```
npm install
```

### 4. 🔥 Start the Development Server

```
npm run dev
```

Your app will be running on [http://localhost:3000](http://localhost:3000) 🚀

---

Made with ❤️ by [@tayyab-004](https://github.com/tayyab-004)

Thank you for using DeepSeek Clone! If you have any questions or feedback, feel free to reach out. Happy Coding! 🚀
