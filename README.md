# SkillSync AI

SkillSync AI is a fully in-browser, AI-powered resume matcher that helps users tailor their resumes to any job description. Built using Scribbler Notebooks, it combines deep AI insights with local fallback logic to ensure reliable, secure, and insightful resume–JD matching - **all without a backend**.

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
- 📈 **Visualize match data** using simple, interactive charts
- 🛡️ **Stay secure** with no server interaction all logic runs on the client

---

## ⚙️ Tech Stack & DeepTech Used

| Category | Tools/Frameworks |
|---------|------------------|
| AI Analysis | Google Gemini API |
| Local Fallback | Custom Tokenizer in JavaScript |
| PDF Parsing | `pdf.js` (WASM-powered) |
| Visualization | Chart.js |
| Styling | Tailwind CSS + Tabler Icons |
| Runtime |  Scribbler JS Notebook (no backend) |

### ✅ DeepTech Highlights:
- **WASM-powered pdf.js** for fast, secure resume parsing  
- **Local tokenizer-based scoring fallback** for offline usability  
- **Secrets management** via Scribbler to securely store API keys  
- **Everything runs 100% in-browser**

---

## 🧪 How to Run

### 📎 [Open the Notebook in Scribbler](https://app.scribbler.live/?jsnb=github:ayushichoudhary-19/skillsync-ai/SkillSync-AI.jsnb)

1. Take the notebook out of sandbox by choosing the option from the toolbar
2. Run all the cells together via 'Run All' option from the toolbar
3. **Follow UI steps**: Write/Paste a JD → Upload Resume → View Results → Tailor with AI

---

## 📸 Screenshots
### Match Analysis
<img width="1201" alt="Screenshot 2025-06-03 at 10 25 41 PM" src="https://github.com/user-attachments/assets/debf5edd-51c1-42ce-991d-97e72c416e6d" />

### Tailoring Suggestions
<img width="1196" alt="Screenshot 2025-06-03 at 10 25 58 PM" src="https://github.com/user-attachments/assets/d036848d-16bd-42ba-9c2f-6cb703d9f9b7" />

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

---

> Built by [Ayushi Choudhary](https://github.com/ayushichoudhary-19)

