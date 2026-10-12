# ESL B1 Speaking Studio — CEFR Intermediate Fluency Suite

A complete, interactive 10-module web-based speaking curriculum designed for English language learners and teachers at the **CEFR B1 (Intermediate)** level.

Every lesson module is a standalone, dependency-free single-page web application featuring browser-native speech synthesis, live microphone audio recording, interactive flippable vocabulary cards, roleplay timers, grammar quizzes, and print-ready classroom handouts.

---

## 📚 Curriculum Overview

| Unit | Topic & Theme | Grammar Target | Spoken Interaction & Functions | File |
| :--- | :--- | :--- | :--- | :--- |
| **Unit 1** | **Travel Dilemmas & Storytelling** | Past Continuous vs. Past Simple | Dealing with delayed flights, lost luggage, and travel complaints | [`index.html`](index.html) |
| **Unit 2** | **The Modern Workplace & Careers** | Modals of Obligation (*must*, *have to*, *should*) | Job interview scenarios, workplace negotiations, work-life balance | [`career-lesson.html`](career-lesson.html) |
| **Unit 3** | **Digital Life & Screen Time** | *Used to* vs. *Be used to* | Debating social media habits, AI ethics, and household screen time | [`tech-lesson.html`](tech-lesson.html) |
| **Unit 4** | **Food, Dining & Culinary Debates** | Quantifiers & Defining Relative Clauses | Restaurant complaints, tipping etiquette, dietary preferences | [`food-lesson.html`](food-lesson.html) |
| **Unit 5** | **Green Living & Eco-Choices** | First Conditional (*if* / *unless*) | Cause and effect, sustainable habits, zero-waste lifestyle debates | [`environment-lesson.html`](environment-lesson.html) |
| **Unit 6** | **Health, Fitness & Well-Being** | *Had better*, Gerunds vs. Infinitives | Describing symptoms to a doctor, gym advice, stress management | [`health-lesson.html`](health-lesson.html) |
| **Unit 7** | **Money, Smart Spending & Consumer Dilemmas** | Passive Voice in Commerce | Disputing bank/billing fees, bargaining, personal budgeting | [`finance-lesson.html`](finance-lesson.html) |
| **Unit 8** | **Entertainment, Cinema & Streaming Culture** | *-ed* vs. *-ing* Adjectives & Second Conditional | Film reviews, binge-watching habits, spoilers, book vs. film adaptations | [`entertainment-lesson.html`](entertainment-lesson.html) |
| **Unit 9** | **Housing, Flat-Hunting & Neighborhood Life** | Comparative Modifiers & Indirect Questions | Apartment viewings, urgent repair requests to landlords, housemate rules | [`housing-lesson.html`](housing-lesson.html) |
| **Unit 10** | **Education, Lifelong Learning & Modern Skills** | Modals of Deduction (*must/can't be*) & Contrast Connectors | University vs. apprenticeships, exam anxiety, AI tutors, group projects | [`education-lesson.html`](education-lesson.html) |

---

## 🌟 Key Features

1. **Native Text-to-Speech (TTS):**
   - Built with the Web Speech API (`speechSynthesis`).
   - Standard UK English model pronunciation with a toggle for normal (`1.0x`) and learner-friendly slow (`0.8x`) speeds.

2. **In-Browser Microphone Studio:**
   - Real-time voice recording via the HTML5 `MediaRecorder` API.
   - Record spoken answers, stop, and play back immediately to evaluate pronunciation, rhythm, and hesitation without external servers (100% client-side & private).

3. **Flippable 3D Flashcards:**
   - Six high-frequency collocations per unit.
   - Includes IPA phonetics, in-context sentences, spoken production drills, and a global "Flip All" toggle.

4. **Interactive Practice Clock:**
   - 60-second preparation phase followed by a 90-second speaking phase.
   - Synthesized Web Audio tone alerts to mimic real speaking exams (e.g. Cambridge B1 Preliminary / IELTS Speaking).

5. **Self-Assessment Checklists:**
   - CEFR B1 criteria rubrics on every unit allowing learners to track their communicative competence.

6. **Classroom Print Mode (`@media print`):**
   - Cleanly hides digital widgets and audio controls, formatting the lesson into a clean, 2-page printable handout for physical classrooms.

---

## 🚀 How to Use

No build step or dependencies required!

### Option A: Local Browser
Double-click any `.html` file (e.g., `index.html`) in your file explorer to open it in Chrome, Edge, Firefox, or Safari.

### Option B: Local Web Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```
Navigate to `http://localhost:8000` in your web browser.

### Option C: GitHub Pages
Enable GitHub Pages in this repository under **Settings > Pages > Branch: `main` or `master`** to serve the curriculum as a live website.

---

## 📄 License
MIT License. Created for ESL teachers, tutors, and self-directed English learners worldwide.
