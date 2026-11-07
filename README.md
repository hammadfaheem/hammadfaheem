<p align="center">
  <img src="assets/header.svg" width="100%" alt="Hammad Faheem — Voice AI Engineer" />
</p>

<p align="center">
  <img src="assets/typing.svg" alt="I build voice agents that sound human" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/hammad-faheem-2162601b3"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:hammadfaheem5@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://wa.me/923172828890"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
  <a href="https://kaggle.com/hammadfaheem"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" /></a>
  <br />
  <img src="https://komarev.com/ghpvc/?username=hammadfaheem&label=Profile%20views&color=70a5fd&style=flat-square" alt="Profile views" />
</p>

---

## 👋 About Me

I build voice agents that pick up the phone, hold a natural conversation, and actually get the job done: booking a hotel room, scheduling a plumber, or translating a live sermon into 100+ languages.

I've shipped real-time voice AI to production for teams in 🇺🇸 the US, 🇦🇺 Australia and 🇸🇪 Sweden, mostly on **LiveKit**, **Twilio SIP** and **WebRTC**.

- 🔭 Currently building **TarjamAI**, a live speech-translation platform for masjids that serves 100+ languages in real time
- 🎙️ Specialise in low-latency **STT → LLM → TTS** pipelines, SIP telephony, barge-in handling and tool-calling agents
- 🎓 Pursuing an **MS in Artificial Intelligence** at NED University
- 🧑‍🏫 Taught **3,000+ Data Science & Python lessons** on Preply with a 4.9★ rating
- 💬 Ask me about LiveKit Agents, Twilio SIP trunking, voice latency, or testing voice agents
- 🤝 Open to **Voice AI engineering roles** and **freelance voice-agent projects**

---

## 📈 Impact at a Glance

| ⚡ **< 800 ms** | 📞 **100+** | 🐞 **−35%** | 🌍 **100+** |
|:---:|:---:|:---:|:---:|
| voice response latency with barge-in | concurrent calls on Twilio SIP + LiveKit | production agent error rate | languages translated live |

---

## 🎙️ How I Build Voice Agents

A typical production call flow I design and ship:

```mermaid
flowchart LR
    caller["📞 Caller<br/>Phone or Browser"] -->|PSTN| sip["Twilio SIP Trunk"]
    sip -->|SIP| room["LiveKit Room"]
    caller -.->|WebRTC| room
    room --> vad["Silero VAD"]
    vad --> stt["Speech-to-Text"]
    stt --> llm["LLM Agent<br/>+ Tool Calling"]
    llm <-->|bookings · CRM · APIs| biz[("Business Systems")]
    llm --> tts["Text-to-Speech"]
    tts --> room
    vad -.->|barge-in| tts
```

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,react,vite,tailwind,redux,postgres,mysql,redis,docker,aws,githubactions,linux,git&perline=7" alt="Core stack" />
</p>

| Area | Tools |
|---|---|
| **Voice & Real-time** | ![LiveKit](https://img.shields.io/badge/LiveKit_Agents-111111?style=flat-square&logo=webrtc&logoColor=white) ![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white) ![Twilio](https://img.shields.io/badge/Twilio_SIP-F22F46?style=flat-square&logo=twilio&logoColor=white) ![Ultravox](https://img.shields.io/badge/Ultravox-5B3DF5?style=flat-square) ![Silero VAD](https://img.shields.io/badge/Silero_VAD-2E3440?style=flat-square) ![Deepgram](https://img.shields.io/badge/Deepgram_STT-13EF93?style=flat-square) ![Cartesia](https://img.shields.io/badge/Cartesia_TTS-1F1F1F?style=flat-square) ![HammingAI](https://img.shields.io/badge/HammingAI-6E40C9?style=flat-square) |
| **Agents & LLMs** | ![OpenAI Agents SDK](https://img.shields.io/badge/OpenAI_Agents_SDK-412991?style=flat-square&logo=openai&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![AutoGen](https://img.shields.io/badge/AutoGen-0078D4?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square) ![Multi-Agent](https://img.shields.io/badge/Multi--Agent_Orchestration-8A2BE2?style=flat-square) |
| **Vector Stores** | ![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white) ![Chroma](https://img.shields.io/badge/Chroma-FF6446?style=flat-square) ![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square) |
| **Machine Learning** | ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) |
| **AI Dev Tools** | ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white) ![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white) |

---

## 🚀 Featured Work

| Project | What it does | Built with |
|---|---|---|
| 🕌 **TarjamAI**<br/><sub>🔒 Product · 2026</sub> | Translates live Friday khutbahs and Islamic sermons into 100+ languages in real time. Detects Quranic verses, hadith and Islamic terms and links them to Quran.com / Sunnah.com instead of relying on free-form machine translation. | Low-latency streaming speech pipeline, live captions |
| 🔧 **MajsterAI**<br/><sub>🔒 Private · 2025</sub> | AI receptionist for plumbers, electricians and contractors. It answers inbound calls, qualifies the job, captures customer details and books the appointment mid-call. | LiveKit Agents, Ultravox, Silero VAD, FastAPI, PostgreSQL, React 18 + Vite, Docker Compose |
| 🏨 **Mews × LiveKit**<br/><sub>🔒 Client work</sub> | Voice agent that creates, updates and cancels hotel reservations and pulls guest profiles during live calls, saving ~15 hours of manual work per week. | LiveKit, Python, Mews API, HammingAI |
| 📞 **[AI Calling Agents](https://ai.digitalgraphiks.co.uk/)** | Multilingual inbound/outbound calling agents with real-time interruption handling and sub-800 ms responses. | Twilio SIP, LiveKit, OpenAI, Deepgram, Cartesia |
| 🎟️ **[Tixse](https://www.thetixse.com/)** | Event-ticketing web app with real-time seat selection, secure payments and AI-powered support. | FastAPI, React, PostgreSQL |

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | What it does | Built with |
|---|---|---|
| 📊 **[Call Analytics SaaS](https://dg-ai-chatbot-landing.vercel.app/)** | Central dashboard for monitoring AI-driven calls and insights | FastAPI, React, PostgreSQL |
| 🍽️ **[Restaurant AI Bot](https://ai-restaurant-chat.digitalgraphiks.co.uk/)** | Multi-platform assistant that handles restaurant reservations | LangChain, RAG, OpenAI |
| 📚 **[ICAP AI Bot](https://ai.digitalgraphiks.co.uk/)** | Domain-specific Q&A agent for accounting students | Llama-3, FAISS, LangChain |
| 🩺 **Healthcare Chatbots**<br/><sub>🔒 Client work</sub> | Multilingual assistants with contextual memory (5 languages, 3,000+ users) | LLMs, multi-agent tool use |

</details>

---

## 💼 Experience

**🟢 AI Engineer · TarjamAI** · 🇺🇸 United States (Remote) · *Apr 2026 – Present*
- Engineered a low-latency streaming pipeline from live speech to translated captions that keeps pace with the speaker through long-form sermons
- Built automatic detection of Quranic verses, hadith and Islamic terms, linked to authentic sources

**AI / Python Engineer · SophiieAI** · 🇦🇺 Australia (Remote) · *Nov 2025 – Apr 2026*
- Resolved 40+ critical bugs in production LiveKit voice agents, cutting agent error rates by **35%**
- Integrated the Mews hotel platform so agents handle bookings, changes and cancellations live (**~15 hrs/week** saved)
- Tested agents with HammingAI (**+22%** call-completion accuracy) and kept Python APIs at **99.5%** uptime

**AI Engineer · Omnigate** · 🇸🇪 Sweden (Remote) · *Jul 2025 – Nov 2025*
- Shipped multilingual healthcare chatbots for **3,000+ users** in 5 languages
- Built multi-agent SQL Q&A (**−45%** data-retrieval time) and AI ticketing that deflects **60%** of tickets

**Junior AI Engineer · Digital Graphiks** · 🇵🇰 Karachi · *May 2025 – Oct 2025*
- Designed an STT → LLM → TTS pipeline with barge-in handling and **< 800 ms** response latency
- Integrated Twilio SIP with LiveKit for inbound and outbound calling at **100+ concurrent calls**
- Synced real-time events and context across agents with data channels and async RPC

**AI Engineer Intern · Proxima** · 🇵🇰 Karachi · *Jan 2025 – Apr 2025*
- Built generative-AI support workflows that cut average resolution time by **30%**

**Data Science & Python Instructor · Preply** · 🌐 Remote · *Mar 2022 – Present*
- 3,000+ lessons for 200+ students, including learners from Harvard, Cornell and Johns Hopkins (4.9★)

---

## 🎓 Education & Certifications

| | |
|---|---|
| 🎓 **MS, Artificial Intelligence** | NED University of Engineering & Technology · *2026 – Present* |
| 🎓 **BS, Computer Science (AI & Big Data)** | University of Karachi · *2021 – 2025* |
| 🏅 **Certified AI Developer** | PIAIC (Presidential Initiative for AI & Computing) · *2020 – 2022* |
| 📜 **Building Agentic RAG with LlamaIndex** | DeepLearning.AI |
| 📜 **Building Autonomous Agents** | DeepLearning.AI |
| 📜 **LangChain for LLM Application Development** | DeepLearning.AI |
| 📜 **Machine Learning** | Kaggle / DataCamp |

---

## 📊 GitHub Activity

<p align="center">
  <img src="profile-summary-card-output/tokyonight/0-profile-details.svg" width="100%" alt="Profile details and contribution graph" />
</p>

<p align="center">
  <img src="profile-summary-card-output/tokyonight/3-stats.svg" height="165" alt="GitHub stats" />
  <img src="profile-summary-card-output/tokyonight/2-most-commit-language.svg" height="165" alt="Most-used languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=hammadfaheem&theme=tokyonight&hide_border=true" height="165" alt="GitHub streak" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hammadfaheem/hammadfaheem/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hammadfaheem/hammadfaheem/output/github-snake.svg" />
    <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/hammadfaheem/hammadfaheem/output/github-snake.svg" />
  </picture>
</p>

---

## 🤝 Let's Build Something

Building a voice agent, wiring up SIP telephony, or trying to bring latency down? I'm happy to walk you through a **LiveKit + Twilio SIP** setup on a short call.

📫 [hammadfaheem5@gmail.com](mailto:hammadfaheem5@gmail.com) · 💼 [LinkedIn](https://linkedin.com/in/hammad-faheem-2162601b3)

<p align="center">
  <i>"AI systems should feel seamless, not scripted."</i>
</p>

<p align="center">
  <img src="assets/footer.svg" width="100%" alt="" />
</p>
