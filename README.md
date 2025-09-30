# Hi, I'm Rahael(Hyuntaek) Oh

I'm a full-stack software developer and CS student at the University of Wisconsin–Madison (graduating Fall 2026). I love building real-world systems that solve real problems—from AI-powered chat platforms to assistive tech for accessibility.

raphael.oh0316@gmail.com | [Resume](https://1drv.ms/b/c/6fbd824c4c15afcd/EU5iB0FN9fZDr4LYCyL3RJQBCLek9TPMvR9pbOnrS7aYZQ?e=NEuVNK) | [Portfolio](https://www.notion.so/Portfolio-27cd0b7951b680aca051d1c3cd7d6ced?source=copy_link) | [LinkedIn](https://www.linkedin.com/in/raphael-oh-3155b1332/)

---

## Tech Stack

- **Languages:** Python, Java, TypeScript, C++  
- **Frameworks:** FastAPI, Spring Boot, Node.js (Express), Next.js  
- **Databases:** PostgreSQL, MySQL, MongoDB, Redis, Pinecone, Apache Spark, SQLAlchemy, Alembic  
- **AI/ML:** PyTorch, scikit-learn, Hugging Face (Transformers), CNNs, LLMs, Prompt Engineering, YOLOv8, MoveNet (Pose Estimation)  
- **Cloud & DevOps:** Docker, AWS (EC2, S3, Textract, Comprehend Medical), Firebase (Auth & Realtime DB), Vercel, Render, Nginx, Neon  

---

## Featured Projects


### [SAIL — Basketball Shooting Form Analysis](https://github.com/raphy0316/basketball-form-analyzer)
> Real-time mobile basketball shooting analysis with pose estimation, ball tracking, and coach-style feedback

- Optimized mobile pose estimation with **MoveNet Thunder (TensorFlow Hub)** using preprocessing (cropping, color correction, confidence filtering)  
- Trained **YOLOv8 (Ultralytics, PyTorch)** for reliable basketball detection and tracking in varied video conditions  
- Designed 6-phase shot segmentation (setup → loading → rising → release → follow-through) with cancellation logic for noise reduction  
- Engineered **DTW-based similarity scoring** with biomechanical features (angles, release timing, jump height, velocities)  
- Integrated **LLM feedback layer (OpenAI API)** to generate concise, coach-style training tips from motion deviations  
- Reduced latency with caching, deduplication, and prompt compaction → near real-time feedback on mobile  
- Tech: **Python, TensorFlow, PyTorch, OpenCV, NumPy/Pandas, FastAPI, Docker, React Native**
- [Notion](https://www.notion.so/Basketball-Shooting-Analyzer-SAIL-OpenAI-UW-Madison-27dd0b7951b680f1b8d4c23a2d0962ea?source=copy_link) 

---

### [Live Palette](https://github.com/jparkrighthere/LivePalette)
> Real-time whiteboard and video conferencing platform for collaborative design meetings

- Built real-time multi-user communication with Socket.io
- Dual backend: Spring Boot for user/auth, Node.js for real-time stream APIs
- Dockerized infrastructure with Nginx proxy  
- [Auth Server](https://github.com/jparkrighthere/LivePalette) · [Stream Server](https://github.com/jparkrighthere/streamServer) · [Notion](https://www.notion.so/Live-Pallete-27dd0b7951b680dc9fdeff701c40d3b3?source=copy_link)

---

### [Grow](https://github.com/raphy0316/BuckyClass-general-api)
> University course chat & review platform with integrated Madgrades data

- Next.js + PostgreSQL backend with Firebase Realtime DB sync
- Admin role-based auth and real-time course-based chatrooms
- Data ingestion pipeline for academic datasets using chunked inserts and transactional syncs
- [Frontend (React Native)](https://github.com/raphy0316/BuckyClass-mobile-ReactNative) · [Backend](https://github.com/raphy0316/BuckyClass-general-api) · [Notion](https://www.notion.so/Grow-27dd0b7951b6804a8a4cf7cb0f7489d1?source=copy_link)

---

### [YSViewer](https://github.com/raphy0316/YSViewer)
> Web-based viewer for uploaded novel/text files with customizable reading modes

- Django backend for text parsing, upload, and SQLite storage
- User features: dark mode, font toggling, bookmarking
- Lightweight platform for mobile novel readers

---

### [Second Eye for Buffet](https://github.com/raphy0316/SecondEyeForBuffetServer)
> Assistive app for visually impaired buffet users, using RFID + Node.js

- Designed MongoDB structure for food metadata & allergies
- Built APIs for admin logins, food-item mapping, RFID interactions
- [Frontend (Kotlin)](https://github.com/raphy0316/SecondEyeForBuffet) · [Backend](https://github.com/raphy0316/SecondEyeForBuffetServer)

---

### [Who am I?](https://github.com/raphy0316/WhoAmI)
> C++ SDL2 game where players combine letters to evolve character stats

- PM role: led team of 3 devs, scoped project, designed UI and upgrade mechanics
- Integrated alphabet-based stat system to mix gameplay with language learning
---

### [Second Touch](https://github.com/raphy0316/SecondHand)
> One-handed Korean keyboard layout for users with limb disabilities

- Developed a directional layout algorithm based on Hangul patterns
- Tested with users and improved usability via feedback loops
- Won Silver Prize, 2018 Seoul Creative IT Competition
---

## What I'm Interested In
- Building **AI-powered developer tools** and **LLM-integrated systems**
- Designing real-time collaboration platforms with scalable backend infrastructure
- Exploring **MLOps workflows**, data pipelines, and cloud-native AI deployment
- Building tech that *actually helps people*, especially in education and accessibility

---

Thanks for visiting!
