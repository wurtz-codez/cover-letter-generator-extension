# 🧠 Project Planning: AI Cover Letter Generator Extension

---

## 🎯 Goal
A Chrome extension that helps job seekers quickly generate personalized cover letters 
by combining their resume with a job description, powered by AI.

---

## 🛠️ Tech Stack
- **Frontend:** React.js, TailwindCSS
- **Backend (future):** Node.js + Express, MongoDB (for user storage)
- **AI:** Gemini API / OpenAI API
- **Chrome APIs:** Manifest V3, chrome.storage
- **File Handling:** pdf-lib, docx, file-saver
- **Build Tool:** Vite

---

## 📂 Project Structure
cover-letter-extension/
│── public/
│   └── manifest.json
│── src/
│   ├── popup/        # Popup UI
│   ├── options/      # Resume upload page
│   ├── background/   # Background scripts
│   └── index.css     # Tailwind styles
│── README.md
│── tasks.md
│── planning.md
│── package.json