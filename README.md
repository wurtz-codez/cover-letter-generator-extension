# AI Cover Letter Generator (Chrome Extension)

A Chrome Extension that generates personalized cover letters using AI (Gemini/OpenAI).  
Users can upload their resume once, paste a job description, and instantly generate a tailored cover letter.  
They can then copy it, or download it as PDF/DOCX — all without leaving the job portal. 🚀

---

## ✨ Features
- Upload and store resume (once, reuse anytime)
- Input job description → AI generates a personalized cover letter
- Download as **PDF/DOCX** or copy to clipboard
- Simple and clean UI (React + Tailwind)
- (Future Scope) Scrape job description directly from job portals
- (Future Scope) Multiple templates (formal, enthusiastic, short-pitch)

---

## 🛠️ Tech Stack
- **Frontend (Popup & Options UI):** React.js + TailwindCSS
- **Backend (for AI & storage):** Node.js + Express (future versions)
- **AI API:** Gemini API / OpenAI API
- **Chrome API:** Manifest V3, chrome.storage
- **File Handling:** pdf-lib / docx / file-saver

---

## 🚀 Getting Started

1. Clone the repo
   ```bash
   git clone https://github.com/your-username/cover-letter-extension.git
   cd cover-letter-extension