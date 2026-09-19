# Know AI — Interactive Executive Workshop

An interactive, zero-dependency web application designed for live corporate and higher-education sessions based on **Ime Inyang's "Introduction to AI"** workshop presentation. 

Crafted with a clean, executive light theme, fluid micro-interactions, and accessible controls tailored specifically for adult learners (ages 30–40), facilitators, and executive participants.

---

## 🎯 Overview & Objectives

The application guides participants through two core conceptual pillars of practical artificial intelligence:

1. **Classification (What is AI vs. Traditional Automation?):** Demystifying machine learning by contrasting deterministic, rule-based software with pattern-recognizing probabilistic systems.
2. **Applied Ethics & Governance (When should AI be deployed?):** Evaluating high-value, safe productivity applications against critical risk scenarios requiring strict human judgment and data privacy safeguards.

---

## 🕹️ Workshop Modules

### Module 1: Classification — *"Is it AI?"*
Participants sort 6 real-world scenarios into two distinct categories: **Artificial Intelligence (AI)** or **Standard Software (NOT AI)**.

- **Scenarios Evaluated**:
  - **A. Calculator adding 250 + 450** $\rightarrow$ `NOT AI` *(Deterministic IF/THEN arithmetic)*
  - **B. Email automatically identifying spam** $\rightarrow$ `AI` *(Statistical pattern recognition & NLP)*
  - **C. Photocopier making 20 copies** $\rightarrow$ `NOT AI` *(Mechanical optical reproduction)*
  - **D. Phone recognizing your face** $\rightarrow$ `AI` *(Computer Vision & neural biometrics)*
  - **E. Camera detecting people entering a building** $\rightarrow$ `AI` *(Real-time object detection & tracking)*
  - **F. System predicting equipment failure** $\rightarrow$ `AI` *(Predictive analytics & anomaly detection)*
- **Interaction Modes**: Universal Pointer drag-and-drop for desktop/laptop users, plus intuitive one-tap quick assignment buttons on every card for mobile/touchscreen participants.
- **Round 1 Evaluation**: Displays a glowing score circle with fractional denominator ($X_{/6}$) and drill-down explanations citing the workshop presentation principles.

---

### Module 2: Evaluation — *"Should AI be used here?"*
A flashcard swiping stage where scenarios appear **individually** (one case at a time with no visual clutter or card overlapping).

- **Scenarios Evaluated**:
  - **G. Drafting a routine office announcement** $\rightarrow$ `USE AI` *(High-efficiency generative drafting with human final proofreading)*
  - **H. Summarising a university policy** $\rightarrow$ `USE AI` *(Synthesizing dense text into accessible executive briefings)*
  - **I. Uploading confidential student records to an unknown AI tool** $\rightarrow$ `DON'T USE` *(Severe breach of privacy, GDPR/FERPA compliance, and institutional data governance)*
  - **J. Making a final disciplinary decision about a student** $\rightarrow$ `DON'T USE` *(High-stakes ethical decision requiring irreplaceable human empathy, context, and accountability)*
- **Interaction Modes**:
  - **Swipe Left**: `DON'T USE` (red angled stamp)
  - **Swipe Right**: `USE AI` (emerald angled stamp)
  - **Action Buttons**: Dedicated `[← DON'T USE]` and `[USE AI →]` buttons for accessibility
  - **Keyboard Controls**: Arrow Left (`←`) and Arrow Right (`→`)
  - **Visual Case Stepper**: Real-time progress bar (`Case G`, `Case H`, `Case I`, `Case J`) showing the active question and completed steps.
- **Round 2 Evaluation**: Luminous score circle ($X_{/4}$) with institutional policy rationale and governance breakdown.

---

### Final Workshop Summary
At the conclusion of both modules, the application presents:
- An aggregate master score with a glowing ring ($X_{/10}$).
- Performance badge and feedback tier.
- Complete combined review of all 10 scenarios with full slide-referenced explanations.
- One-click reset to allow multiple workshop cohorts or breakout groups to participate.

---

## 🎨 Design Philosophy & UX

- **Executive Aesthetic**: Clean off-white canvas (`#f8fafc`), crisp card surfaces (`#ffffff`), hairline borders, and subtle multi-tier shadows designed for professional training environments.
- **Audio Feedback**: Subtle, non-intrusive harmonic chimes synthesized in real-time via the **Web Audio API** (no harsh arcade bleeps, with an accessible Mute toggle).
- **Celebration Particle Engine**: Lightweight HTML5 Canvas confetti for high-performing participants.
- **Fully Responsive**: Adapts seamlessly to smartphones, tablets, laptop screens, and large projector displays.
- **Zero Dependencies**: 100% self-contained single-file architecture. No npm, no CDNs, no external frameworks, and no trackers. Works completely offline.

---

## 🚀 Getting Started

### Run Locally
No installation or build step is required:
1. Clone or download this repository:
   ```bash
   git clone https://github.com/xpr-ltd/know-ai.git
   ```
2. Double-click `index.html` or open it directly in any modern web browser (Chrome, Edge, Safari, Firefox).

Alternatively, launch a lightweight local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

### Deploy to GitHub Pages
1. Go to repository **Settings** > **Pages**.
2. Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/ (root)`.
3. Click **Save**. Your interactive session will be live at `https://xpr-ltd.github.io/know-ai/`.

---

## 📁 Repository Structure

```
know-ai/
├── index.html       # Complete self-contained single-page application (UI, CSS, JS, Audio)
└── README.md        # Workshop overview and facilitator documentation
```

---

## 👥 Credits & Facilitator

- **Session Facilitator**: Ime Inyang
- **Presentation**: *Introduction to AI*
- **Organization**: [XPR Ltd](https://github.com/xpr-ltd)
