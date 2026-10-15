<picture>
  <source media="(max-width: 600px)" srcset="./assets/profile-banner-mobile.svg" />
  <img src="./assets/profile-banner.svg" width="100%" alt="Ayush Bajaj — Complex signals. Clear decisions. Backend systems, applied AI, and full-stack products." />
</picture>

<div align="center">

# Ayush Bajaj

**Software Developer · Backend Systems & Applied AI**

VIT Vellore · B.Tech Computer Science · Class of 2027

I build software that makes complex information useful — from understanding a code change's blast radius to keeping business records consistent.

[![Portfolio](https://img.shields.io/badge/Portfolio-Explore_my_work-0B1220?style=for-the-badge&logo=vercel&logoColor=6DE4D5&labelColor=0B1220)](https://ayushbajaj7.github.io/Portfolio/)
[![Resume](https://img.shields.io/badge/Resume-View_CV-0B1220?style=for-the-badge&logo=googledrive&logoColor=A99AFF&labelColor=0B1220)](https://drive.google.com/file/d/1pNRl11o4bRue66-_wy4uAW5yQHv_iHgW/view)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0B1220?style=for-the-badge&logo=linkedin&logoColor=7DD3FC&labelColor=0B1220)](https://www.linkedin.com/in/ayush-bajaj-3a8b28295/)
[![Email](https://img.shields.io/badge/Email-Say_hello-0B1220?style=for-the-badge&logo=gmail&logoColor=6DE4D5&labelColor=0B1220)](mailto:ayushbajaj215@gmail.com)

[Selected work](#selected-work) · [Technical toolkit](#technical-toolkit) · [More projects](#more-projects) · [Experience](#experience--education)

</div>

## Selected work

### 01 / Microservice Drift Tracker

**A code change is local. Its consequences may not be.**

MDT connects Git diffs, AST analysis, service dependencies, and semantic context to estimate deployment impact across a microservice system.

**My contribution:** I built the **architectural smell detector** and **remediation simulator** in this ongoing team project. They help developers identify dependency problems and preview proposed changes in a Neo4j sandbox.

<sub>Code change → Dependency graph → Smell detection → Remediation preview</sub>

`Python` `FastAPI` `Neo4j` `ChromaDB` `Docker Compose` `React`

[Explore the shared repository ↗](https://github.com/kartick026/MDT) · [Read the smell detector](https://github.com/kartick026/MDT/blob/main/backend/services/smell_detector.py)

---

### 02 / Cat-X · Operator Shift Twin

**Make telemetry useful at the moment of a decision.**

An in-cab companion prototype combining shift tasks, proximity and safety signals, WebSocket telemetry, and consequence simulation to help compare possible operator actions.

**My contribution:** I built the **core prototype** as part of an ongoing college team project for the **Caterpillar Hackathon 2026**. The browser demo uses illustrative sample data.

<sub>Shift signals → Hazard checks → Consequence model → Operator decision</sub>

`Python` `FastAPI` `WebSockets` `React` `TypeScript`

[Try the sample-data demo ↗](https://cat-frontend-su80.onrender.com/shift) · [Explore the source](https://github.com/AyushBajaj7/Cat-X)

---

### 03 / Traders ERP

**One business action should leave every related record consistent.**

An ERP for hardware-trading workflows in Nepal, covering inventory, customer and supplier ledgers, billing, VCTS tracking, and cashbook.

**My contribution:** I built the platform **independently**. PostgreSQL functions coordinate bill creation, stock movements, and account balances atomically; the installable PWA supports offline-aware use.

<sub>Bill or purchase → Atomic database operation → Stock + ledger + cashbook</sub>

`Next.js` `TypeScript` `Supabase` `PostgreSQL` `PWA`

*Source is private.* [Project overview in my portfolio ↗](https://ayushbajaj7.github.io/Portfolio/)

---

### 04 / Document Summary Assistant

**A useful first read for documents that take time to unpack.**

A document workflow that accepts PDFs, Office files, spreadsheets, and scanned images, then combines Gemini and OCR to produce structured summaries, key points, and suggestions.

<sub>Document or scan → Text extraction / OCR → AI analysis → Structured summary</sub>

`Next.js` `TypeScript` `Gemini` `OCR` `Tailwind CSS`

[Try the app ↗](https://document-summary-assistant-beta.vercel.app/) · [Explore the source](https://github.com/AyushBajaj7/Document-summary-assistant)

## Technical toolkit

The tools behind the projects. **Click any badge to explore what the technology does.**

### Backend & data

[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)](https://en.wikipedia.org/wiki/Node.js) [![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)](https://en.wikipedia.org/wiki/Express.js) [![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)](https://en.wikipedia.org/wiki/Flask_(web_framework)) [![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)](https://en.wikipedia.org/wiki/Neo4j) [![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6600?style=flat-square&logoColor=white)](https://docs.trychroma.com/) [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://en.wikipedia.org/wiki/PostgreSQL) [![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)](https://en.wikipedia.org/wiki/MongoDB) [![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)](https://en.wikipedia.org/wiki/WebSocket)

### Applied AI & machine learning

[![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75C2?style=flat-square&logo=google&logoColor=white)](https://en.wikipedia.org/wiki/Gemini_(language_model)) [![RAG](https://img.shields.io/badge/RAG_%26_Vector_Retrieval-22D3EE?style=flat-square&logoColor=black)](https://en.wikipedia.org/wiki/Retrieval-augmented_generation) [![Transformers](https://img.shields.io/badge/FLAN--T5_Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://en.wikipedia.org/wiki/Transformer_(deep_learning_architecture)) [![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)](https://en.wikipedia.org/wiki/Scikit-learn) [![OCR](https://img.shields.io/badge/OCR_Document_AI-10B981?style=flat-square&logoColor=white)](https://en.wikipedia.org/wiki/Optical_character_recognition) [![AST](https://img.shields.io/badge/AST_Code_Analysis-6366F1?style=flat-square&logoColor=white)](https://en.wikipedia.org/wiki/Abstract_syntax_tree)

### Frontend engineering

[![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://en.wikipedia.org/wiki/React_(software)) [![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)](https://en.wikipedia.org/wiki/Next.js) [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://en.wikipedia.org/wiki/TypeScript) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://en.wikipedia.org/wiki/Tailwind_CSS) [![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)](https://motion.dev/) [![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)](https://en.wikipedia.org/wiki/Progressive_web_app)

### Cloud, delivery & media

[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://en.wikipedia.org/wiki/Docker_(software)) [![AWS EC2](https://img.shields.io/badge/AWS_EC2-232F3E?style=flat-square&logo=amazonwebservices&logoColor=FF9900)](https://en.wikipedia.org/wiki/Amazon_Elastic_Compute_Cloud) [![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)](https://render.com/docs) [![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)](https://en.wikipedia.org/wiki/Vercel) [![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)](https://en.wikipedia.org/wiki/GitHub#GitHub_Actions) [![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)](https://en.wikipedia.org/wiki/FFmpeg)

## More projects

### AgriConnect

An agriculture platform bringing schemes, mandi prices, weather, farming tools, and an AI assistant into one interface. I contributed to the project; the linked demo requires sign-in and uses development storage.

`React` `Node.js` `Express` `MongoDB`

[Demo ↗](https://agri-connect-gamma-one.vercel.app/) · [Source](https://github.com/AyushBajaj7/AgriConnect)

### WeatherVision

Weather, air quality, precipitation trends, and city comparisons, backed by a **Python standard-library server**. A focused example of turning data into a readable interface.

`Python` `JavaScript` `Chart.js` `Weather APIs`

[Demo ↗](https://weathervision.onrender.com/) · [Source](https://github.com/AyushBajaj7/WeatherVision)

### Luxon

A commerce platform connecting product discovery, authentication, wishlists, cart and checkout, payment integration, and an admin portal for inventory and orders.

`Python` `Flask` `PostgreSQL` `Cloudinary` `Razorpay`

[Demo ↗](https://luxon-store.onrender.com/) · [Source](https://github.com/AyushBajaj7/Luxon)

### AI Presentation Explainer & Video Generator

A presentation-to-video pipeline connecting slide extraction, narration, speaker-avatar animation, and rendering. The local Flask implementation includes **retries, resumable processing, and a static-video fallback** when Wav2Lip is unavailable.

`Python` `Flask` `python-pptx` `pyttsx3` `Wav2Lip` `FFmpeg`

[Explore the source ↗](https://github.com/AyushBajaj7/Avatar-for-presentation-) · [Wav2Lip upstream](https://github.com/Rudrabha/Wav2Lip)

## Experience & education

**Software Developer Intern · KuppiSmart Solutions**<br />
May–Jul 2025

- Built responsive React interfaces and reusable components with Tailwind CSS.
- Integrated Razorpay payment processing through REST APIs and contributed feature releases.
- Automated build, test, and deployment workflows with GitHub Actions.

**B.Tech · Computer Science & Engineering · VIT Vellore**<br />
2023–2027 · CGPA: **8.76 / 10**

### Hackathons & competitions

Caterpillar CODE-A-THON 2026 · DevJams'24 (GDSC) · IEEE Yantra Central Hack · CodeChef CookOff 9.0

---

<div align="center">

### Let's build something worth understanding.

Interested in **software engineering, backend systems, applied AI, and full-stack product work**.

[Portfolio](https://ayushbajaj7.github.io/Portfolio/) · [Resume](https://drive.google.com/file/d/1pNRl11o4bRue66-_wy4uAW5yQHv_iHgW/view) · [LinkedIn](https://www.linkedin.com/in/ayush-bajaj-3a8b28295/) · [ayushbajaj215@gmail.com](mailto:ayushbajaj215@gmail.com)

<sub>India & Kathmandu, Nepal</sub>

[![Profile Views](https://komarev.com/ghpvc/?username=AyushBajaj7&label=Profile%20views&color=5965d8&style=flat-square)](https://github.com/AyushBajaj7)

</div>
