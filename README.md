# 🚀 AI Product Engineering Internship Assignment – DisruptiveNext

## 👤 Applicant Details

**Name:** Abrar Kivande  
**Role:** AI Product Engineering Intern  
**Assignment Level Completed:** ✅ Level 1, ✅ Level 2, ✅ Level 3

---

## 🧠 Project Summary

This repository contains the completed assignment for the AI Product Engineering Internship at **DisruptiveNext**. The assignment involves analyzing, comparing, and merging two GitHub repositories related to a modern AI-powered chat interface and backend agent.

---

## 🛠 Tech Stack

- **React.js** (with Next.js v15 and Turbopack)
- **TypeScript**
- **Tailwind CSS**
- **Axios** for API communication
- **Node.js** + **NPM**
- **Server-Sent Events (SSE)** for real-time streaming
- **GitHub Copilot** (Student Developer Pack)

---

## 📂 Key Files in This Repository

| File | Description |
|------|-------------|
| `L1_Summary.md` | Understanding of project architecture |
| `L2_Changes.md` | Detailed comparison of original vs forked repo |
| `L3_Merge_Summary.md` | Summary of merging backend and frontend |
| `README.md` | Setup guide and overview |

---

## 🚦 How to Run the Project

### 🔧 Requirements

- Node.js (v18+)
- NPM

### ▶️ Steps

```bash
git clone https://github.com/AbrarKivande/scira-mcp-ui-merged
cd <repo-name>
npm install
npm run dev
```

Visit: [http://localhost:3000](http://localhost:3000)

> 💡 Note: You may encounter errors due to missing `GROQ_API_KEY` or database credentials. These are expected if no `.env.local` is configured. See notes below.

---

## ⚠️ Known Limitations

- Backend-related routes (`/api/chat`, `/api/chats`) expect valid DB/API configuration via `.env.local`
- These have been wrapped in try/catch for local development to prevent app crash

Example `.env.local` (excluded from repo):
```env
GROQ_API_KEY=your-groq-api-key
DATABASE_URL=postgresql://user:password@localhost:5432/dbname
```

---

## 📷 (Optional) Screenshots

You may add UI screenshots inside a `screenshots/` folder and showcase interface behavior.

---

## 🙏 Acknowledgements

Thanks to the DisruptiveNext team for this exciting opportunity to learn and build in the generative AI space.

---

## 📬 Submission Info

- **Submitted to:** ask@disruptivenext.com  
- **Completed Levels:** Level 1 (Architecture), Level 2 (Code Analysis), Level 3 (Merge)