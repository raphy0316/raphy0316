# Hi, I'm Raphael (Hyuntaek) Oh

I'm a **full-stack software engineer & CS student at UW–Madison (Fall 2026)**.  
I build **AI-powered systems**, **real-time collaboration tools**, and **scalable backend infrastructure**.  
My work focuses on **multimodal AI**, **retrieval systems (RAG, vector search, BM25)**,  
and **ML-powered user experiences**.

raphael.oh0316@gmail.com · [Resume](https://1drv.ms/b/c/6fbd824c4c15afcd/EU5iB0FN9fZDr4LYCyL3RJQBCLek9TPMvR9pbOnrS7aYZQ?e=NEuVNK) · [Portfolio](https://www.notion.so/Portfolio-27cd0b7951b680aca051d1c3cd7d6ced?source=copy_link) · [LinkedIn](https://www.linkedin.com/in/raphael-oh-3155b1332/)  

---

## Tech Stack

**Languages:** Python, Java, TypeScript, C++  
**Frameworks:** FastAPI, Spring Boot, Node.js (Express), Next.js, React Native  
**Databases:** PostgreSQL, MySQL, MongoDB, Redis  
**Infra/Data:** Docker, AWS (EC2/S3/Textract/Comprehend Medical), GCP Dataproc, Kafka, Celery, Prometheus, Grafana, Apache Spark  
**AI/ML:** PyTorch, Hugging Face, CLIP/CLAP, YOLOv8, MoveNet, scikit-learn, Pinecone, BM25/RRF  
**MLOps:** Vector DBs, ETL pipelines, batch/stream ingestion, distributed inference, model serving, profiling  

---

# Featured Projects

## **SAIL — AI Basketball Shooting Coach (UW–Madison × OpenAI)**
_A real-time AI coach analyzing biomechanics from video_

- Fine-tuned **YOLOv8 + MoveNet Thunder**, achieving **94% detection accuracy** and **~60ms inference**  
- Built **6-phase shot segmentation** (setup → loading → rising → release → follow-through)  
  → **91% segmentation accuracy** across 100+ labeled videos  
- Engineered **DTW-based similarity scoring** with kinematic features (angles, timing, velocities)  
- Built a **FastAPI backend + React Native app**, with caching & deduplication for real-time mobile use  
- Integrated an **LLM feedback module** that generates personalized, coach-style tips  
- Tech: Python, TensorFlow Hub, PyTorch, OpenCV, FastAPI, Docker, React Native

[GitHub](https://github.com/raphy0316/basketball-form-analyzer) · [Notion](https://www.notion.so/Basketball-Shooting-Analyzer-SAIL-OpenAI-UW-Madison-27dd0b7951b680f1b8d4c23a2d0962ea?source=copy_link)

---

## **InsightHub — Multimodal AI Evaluation Platform** *(In Progress)*
_A benchmarking & evaluation platform for multimodal models (CLIP, CLAP, ImageBind)_

- Built **Celery + Redis** distributed inference pipeline  
- Benchmarked multimodal models for **image → music retrieval**  
- Integrated **CLIP × CLAP**, **EmoCLIP**, and **ImageBind** with cosine similarity + text-pivot alignment  
- Added **RRF (Reciprocal Rank Fusion)** ensemble scoring  
- Monitored runtime with **Prometheus + Grafana**, including GPU/CPU load & worker queues  
- Designed scalable DB schema: models, datasets, embeddings, runs, metrics

[Backend](https://github.com/raphy0316/InsightHub) · [Model](https://github.com/raphy0316/Insight-Hub-Models) · [Notion](https://www.notion.so/Insight-Hub-In-progress-2aed0b7951b6802d989ac1220d1f5a19?source=copy_link)

---

## **NovelCanvas — AI Novel Worldbuilding Engine** *(In Progress, Private)*
_An LLM-powered system that extracts, normalizes, and manages story settings_

- Built an **LLM-driven extractor** for characters, places, items, relationships, skills  
- Designed **self-referential PostgreSQL schema** for hierarchical world knowledge  
- Detects **setting conflicts** using embedding similarity + coreference resolution  
- Implements **temporal attribute scoping** for multi-chapter consistency checks  
- Built with FastAPI + PostgreSQL + Alembic + Docker

[Notion](https://www.notion.so/NovelCanvas-In-progress-27dd0b7951b680b0a838c2a2a430d7b8?source=copy_link)

---

## **Grow — Course Reviews + Real-Time Chat Platform**
_A social–academic app for 500+ students (Next.js + React Native)_

- Integrated **Madgrades API → PostgreSQL ingestion (900k+ records)**  
  → parallel batching, idempotent upserts → **33% faster pipeline**  
- Auto-generated **semester-based course chatrooms** using Firebase Realtime DB  
- Verified-review system: students staying in chat all semester get a **verified badge**  
- Built mobile client with React Native; backend on Next.js (App Router)

[Mobile App](https://github.com/raphy0316/BuckyClass-mobile-ReactNative) · [Backend](https://github.com/raphy0316/BuckyClass-general-api) · [Notion](https://www.notion.so/Grow-27dd0b7951b6804a8a4cf7cb0f7489d1?source=copy_link)

---

## **Live Palette — Real-Time Collaborative Whiteboard + Video Chat**
_A dual-backend architecture for designers & clients_

- Spring Boot (auth, users, projects) + Node.js (Socket.IO, Mediasoup)  
- Supported **50+ concurrent sessions <200ms latency**  
- Deployed via Docker + Nginx reverse proxy with JWT and Redis token rotation  
- Real-time whiteboard, multi-user video calls, shared workspace

[Auth Server](https://github.com/jparkrighthere/LivePalette) · [Stream Server](https://github.com/jparkrighthere/streamServer) · [Notion](https://www.notion.so/Live-Pallete-27dd0b7951b680dc9fdeff701c40d3b3?source=copy_link)

---

## **YSViewer — Web Novel Reader**
_Django-based lightweight reading app_

- Upload & parse novel files with bookmarking, theme toggling, reading modes  
- Built for mobile-first readers  

[GitHub](https://github.com/raphy0316/YSViewer)

---

## **Second Eye for Buffet — Assistive Tech for Visually Impaired Users**
_RFID-based food identification assistant_

- Used MongoDB + Node.js for food metadata & allergy tracking  
- Built admin APIs, meal mapping, and RFID integration  
- Android app built in Kotlin with accessible UI design  

[Backend](https://github.com/raphy0316/SecondEyeForBuffetServer)

---

## **Who Am I? — SDL2 Game With Evolving Characters**
_C++ educational game mixing word creation & RPG-like stat progression_

- Led a 3-person team (PM role), scoped project, designed UI & mechanic flow  
- Built alphabet → stat mapping system to deepen learning through gameplay  

[GitHub](https://github.com/raphy0316/WhoAmI)

---

## **Second Touch — One-Handed Korean Keyboard**
_Award-winning assistive typing layout_

- Designed directional Hangul layout for one-handed use  
- User-tested iteration cycles; formal competition project  
- **Silver Prize**, 2018 Seoul Creative IT Competition  

---

# Interests

- Multimodal AI (vision–language–audio)
- Retrieval systems (BM25, Pinecone, hybrid RAG)
- MLOps & large-scale inference pipelines  
- Real-time collaboration software  
- Accessibility & education-focused tech  

---

Thanks for visiting!  
If you're working on AI infra, multimodal systems, or scalable backend tools — **I'd love to connect!**
