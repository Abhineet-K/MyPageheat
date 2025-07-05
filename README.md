# 🔥 MyPageHeat – AI-Powered Website Design Evaluator

**MyPageHeat** is an AI-powered tool that generates predictive heatmaps and smart UX suggestions for your web designs — before your site ever goes live.

> “See how users will see your website — before you launch.”

---

## 📌 Overview

MyPageHeat helps developers, designers, and marketers evaluate how users are likely to **view, click, and engage** with a webpage layout or screenshot using AI-based prediction models. It’s perfect for **pre-launch validation** — unlike Hotjar or Clarity, it doesn’t require real user traffic.

---

## 🧠 Key Features

### ✅ Upload & Analyze

* Upload screenshot or paste live URL
* Auto-screenshot for live URLs using Puppeteer
* Choose device type (Desktop / Mobile / Tablet)

### 🔥 AI-Powered Heatmap Generation

* Predicts user eye fixation zones using saliency models
* Visual heatmap overlay (Red = high attention)

### 🖱️ Click Likelihood Prediction

* Detects interactive elements (buttons, navs)
* Scores elements based on visibility + likelihood of interaction

### 🎯 CTA Visibility Score

* AI evaluates position, contrast, size of your Call-to-Action
* Suggestions like: *“Move CTA above the fold”*

### 🧠 UX Suggestions Panel

* AI explains layout strengths and weaknesses
* Recommendations for improving clarity, readability, and focus

### ♿ Accessibility Mode *(optional)*

* Simulate color blindness
* Check font readability and contrast

### 🆚 Before & After Comparison

* Upload two versions and compare heatmaps + UX feedback

### 🔗 Sharable Public Report

* Get a public link for client or team review
* Includes annotated heatmap, scores, and suggestions

---

## 💡 Unique Selling Points

| Feature                  | Hotjar/Clarity | MyPageHeat |
| ------------------------ | -------------- | ---------- |
| Requires user traffic    | ✅ Yes          | ❌ No       |
| Works before site launch | ❌              | ✅          |
| Accepts Figma/screenshot | ❌              | ✅          |
| AI CTA scoring           | ❌              | ✅          |
| UX smart suggestions     | ❌              | ✅          |
| Comparison mode          | ❌              | ✅          |
| Shareable reports        | ✅ (Enterprise) | ✅ (Free)   |

---

## 🚀 Tech Stack

| Layer        | Technology                                                   |
| ------------ | ------------------------------------------------------------ |
| Frontend     | React.js + TailwindCSS + Zustand                             |
| Backend      | Node.js + Express                                            |
| AI/ML        | Python (Flask/FastAPI) + OpenCV + DeepGaze/MLNet             |
| Screenshot   | Puppeteer / Playwright                                       |
| File Storage | Firebase / Cloudinary                                        |
| Hosting      | Vercel (frontend), Render (backend), Hugging Face (ML model) |

---

## 🗂️ Folder Structure (Suggested)

```bash
/client
  /components
  /pages
  /styles
/server
  /routes
  /services
  /utils
/ml-server
  /models
  /predict.py
```

---

## 🧪 MVP User Flow

1. User uploads screenshot or enters live URL
2. App renders the page if needed
3. AI generates:

   * Heatmap
   * Click map
   * CTA score
   * UX feedback
4. User views results
5. Optionally uploads 2nd version to compare
6. Generates public shareable report

---

## 🎯 Outcomes for Users

* Validate UX early, reduce rework
* Discover visual issues without analytics
* Improve CTA and layout placement
* Get client-ready, data-backed insights instantly

---

## 👨‍💻 Built By

**Abhineet Kumar**
Software Developer | Node.js | React | Product Engineer
[LinkedIn](#) • [Portfolio](#) • [Twitter](#)

---

## 🏆 Resume Value (Why This Project Rocks)

* Combines AI, frontend, and product thinking
* Useful for frontend/UX-heavy roles
* Demonstrates visual rendering logic (Canvas, DOM overlay, ML integration)
* Unique: almost no competition in pre-launch design evaluators

---

## 📅 Roadmap Ideas

* [ ] Figma Plugin
* [ ] Mobile/Desktop view comparison toggle
* [ ] Emotion tone analysis (calm / loud / distracting)
* [ ] Browser extension
* [ ] Team dashboard

---

## 📄 License

MIT
