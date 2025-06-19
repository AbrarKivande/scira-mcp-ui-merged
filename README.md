# 🧠 Scira Chat UI + Agent Backend (Merged)

A powerful AI-powered chat interface built with **Next.js**, **PostgreSQL**, and **Groq LLM API**, combining the capabilities of both `scira-mcp-ui-chat` and `scira-mcp-agent` repositories.

---

## 🚀 Features

- ✨ Chat interface with clean, modern UI (Next.js + TailwindCSS)
- 🧠 AI assistant responses using Groq API (Mixtral or LLaMA)
- 💬 Chat history saved to PostgreSQL via Drizzle ORM
- 🧾 Full CRUD API endpoints for chats and messages
- 🛠️ Modular architecture for frontend and backend separation

---

## 📂 Project Structure

```
├── app/
│   ├── api/
│   │   ├── chat/route.ts       # POST AI messages
│   │   └── chats/route.ts      # GET all chats
├── lib/
│   ├── chat-store.ts           # Core chat DB logic
│   ├── db/index.ts             # Drizzle DB instance
│   └── schema.ts               # DB schema for chats/messages
├── .env.local                  # Env variables
└── README.md                   # This file
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/AbrarKivande/scira-mcp-ui-merged.git
cd scira-mcp-ui-merged
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create `.env.local` file in the root:

```env
DATABASE_URL=postgresql://postgres:your_password@localhost:5432/chatdb
GROQ_API_KEY=your_groq_api_key
```

### 4. Start PostgreSQL

Make sure PostgreSQL is running and database `chatdb` exists.

You can create the DB using:

```bash
createdb chatdb
```

### 5. Run the Dev Server

```bash
npm run dev
```

Visit: [http://localhost:3000](http://localhost:3000)

---

## 📦 Tech Stack

| Tech           | Description                         |
|----------------|-------------------------------------|
| Next.js 15     | Frontend framework (Turbopack)      |
| Tailwind CSS   | Styling                             |
| PostgreSQL     | Relational database                 |
| Drizzle ORM    | Type-safe DB access                 |
| Groq API       | AI assistant responses              |
| React Query    | Data fetching and caching           |

---

## 🧪 Sample API Request

```ts
POST /api/chat

{
  "messages": [
    { "role": "user", "content": "Hi, who are you?" }
  ]
}
```

---

## 📸 Screenshots

> Add your screenshots here:
- Home page
- Chat screen
- Terminal success logs
- DB proof (optional)

---

## 👤 Author

**Abrar Kivande**  
🔗 [GitHub Repo](https://github.com/AbrarKivande/scira-mcp-ui-merged)

---

## ✅ License

MIT License — free to use and modify.

---

> Built with ❤️ for DisruptiveNext Internship
