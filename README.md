# SkillSync AI

SkillSync AI is a fully in-browser, AI-powered resume matcher that helps users tailor their resumes to any job description. Built using Scribbler Notebooks, it combines deep AI insights with local fallback logic to ensure reliable, secure, and insightful resume-JD matching - **all without a backend**.

> 🚀 Built for the [Summer of Scribbling 2025 Hackathon](https://hub.scribbler.live)

---

## 🔍 What It Does

SkillSync AI allows job seekers to:

- 📝 **Upload any Job Description** and **their Resume (PDF)**
- 📊 **Get a Match Score** with a breakdown of:
  - Skills matched
  - Skills missing
  - Tone and relevance
- 💡 **Receive AI-powered feedback** to tailor their resumes
- 🧠 **Auto-generate final resumes** with tailored markdown suggestions
- 🖼️ **Live preview and edit the markdown**
- 📄 **Download the final resume as a beautifully styled PDF**
- 📈 **Visualize match data** using simple, interactive charts
- 🛡️ **Stay secure** with no server interaction - all logic runs on the client

---

## ⚙️ Tech Stack & DeepTech Used

| Category        | Tools/Frameworks                     |
|----------------|--------------------------------------|
| AI Analysis     | Google Gemini API                    |
| Resume Editor   | Markdown + `marked.js` + Tailwind    |
| PDF Exporting   | `html2pdf.js` + `jsPDF`              |
| Local Fallback  | Custom Tokenizer in JavaScript       |
| PDF Parsing     | `pdf.js` (WASM-powered)              |
| Visualization   | Chart.js                             |
| Styling         | Tailwind CSS + Tabler Icons          |
| Runtime         | Scribbler JS Notebook (no backend)   |

### ✅ DeepTech Highlights:

- **WASM-powered pdf.js** for client-side PDF parsing of resumes and job descriptions

- AI + Local Hybrid Matching using: Google Gemini API for advanced skill/tone extraction

- Custom JavaScript tokenizer for offline match scoring fallback

- Inline Tailoring Logic: AI suggestions are automatically incorporated into a final, editable markdown resume

- Live Markdown Editor + Preview powered by **marked.js**

- Client-side PDF Generation using **html2pdf.js** and **jsPDF**, with no server dependency

- Fully Serverless Runtime via **Scribbler Notebook** - all parsing, scoring, and editing happens in-browser

- Secure API Key Handling using **Scribbler’s local secrets vault**

---

## 🧪 How to Run

### 📎 [Open the Notebook in Scribbler](https://app.scribbler.live/?jsnb=github:ayushichoudhary-19/skillsync-ai/SkillSync-AI.jsnb)

1. Take the notebook out of sandbox by choosing the option from the toolbar  
2. Run all the cells together via **Run All** from the toolbar  
3. **Follow UI Steps**:  
   - Paste Job Description → Upload Resume PDF  
   - Get match score, feedback, and suggestions  
   - Auto-generate & edit the markdown resume  
   - Live preview + export final resume as a polished PDF

---

## 📸 Screenshots

### Match Analysis  
<img width="1201" alt="Screenshot 2025-06-03 at 10 25 41 PM" src="https://github.com/user-attachments/assets/debf5edd-51c1-42ce-991d-97e72c416e6d" />

### Tailoring Suggestions  
<img width="1196" alt="Screenshot 2025-06-03 at 10 25 58 PM" src="https://github.com/user-attachments/assets/d036848d-16bd-42ba-9c2f-6cb703d9f9b7" />

### Markdown Resume Editor + PDF Export  
<img width="1207" alt="Screenshot 2025-06-07 at 6 21 27 PM" src="https://github.com/user-attachments/assets/c880d5f5-41e4-444d-9224-eef545bd62c6" />

---

## 📝 Submission Info

- **Team Name**: geekyAyushi  
- **Notebook**: [`SkillSync-AI.jsnb`](https://app.scribbler.live/?jsnb=github:ayushichoudhary-19/skillsync-ai/SkillSync-AI.jsnb)  
- **Hackathon**: Summer of Scribbling 2025  
- **GitHub Repo**: [ayushichoudhary-19/skillsync-ai](https://github.com/ayushichoudhary-19/skillsync-ai)

---

## 📜 License

MIT – open-sourced for the community!

---

## 🙌 Acknowledgements

- Team Scribbler for the platform  
- Google Gemini API for intelligent analysis  
- Mozilla's `pdf.js` for seamless resume parsing  
- The open-source community for `html2pdf.js`, `marked.js`, and `Chart.js`  

---

> Built by [Ayushi Choudhary](https://github.com/ayushichoudhary-19)
