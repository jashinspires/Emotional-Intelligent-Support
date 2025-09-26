# 🧠 Emotional Intelligent Support

Empathetic, AI-powered mental health support—accessible 24/7 through a safe, privacy-first conversational experience.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-0A81D1?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)

## 🌟 Vision Statement
Normalize seeking mental health support by offering compassionate, culturally aware, always-available help that complements—not replaces—licensed therapy.

## 🧩 Problem Statement
- Long wait times and high costs limit access to mental healthcare
- Stigma prevents early intervention and open conversations
- Crisis escalation can occur when support is unavailable at critical moments
- Generic chatbots miss nuance and cultural sensitivity, risking harm
- Many tools ignore privacy, safety, and ethical guardrails

## 💡 Solution Approach
A human-centered, AI-assisted mental health companion:
- Empathetic conversational agent tuned for supportive, non-judgmental responses
- Emotion detection from text to tailor coping strategies and resources
- Safety-first escalation with crisis detection and localized helplines
- Journaling, grounding exercises, CBT-inspired prompts and mood tracking
- Multilingual support and culturally sensitive response templates
- Clear disclaimers and nudges toward professional help when needed

## 🧠 AI Tools & Architecture
- LLM Orchestration: LangChain / Instructor for safe prompting and tool use
- Models: gpt-4o-mini or comparable; distilled local model option for privacy
- Embeddings/RAG: Pinecone or pgvector for coping content retrieval
- Safety Layer: prompt routing, content filters, crisis classifiers
- Backend: FastAPI with background tasks and rate limiting
- Frontend: Flutter mobile app and web client (responsive)
- Data: PostgreSQL for user profiles, secure journal entries (encrypted at rest)
- Telemetry: Privacy-preserving analytics (opt-in)

## 🔐 Ethics, Privacy, and Safety
- Not a substitute for professional care; disclaimers throughout
- Crisis protocol: detect self-harm intent, provide region-specific resources, suggest contacting trusted people; never give harmful instructions
- Data minimization: store only what’s necessary, encryption at rest and in transit
- Transparent logs for moderation; red-team tests for harmful outputs

## 📅 10-Day Actionable Development Plan

### Days 1–2: Foundations and Guardrails
- Project scaffolding (FastAPI + Flutter), env management, CI setup
- Safety policies, disclaimers, crisis detection heuristics and test cases
- Initial prompt templates for supportive tone, boundaries, and referrals

### Days 3–4: Core Conversation Engine
- Integrate LangChain with chosen LLM and safety filters
- Implement session context and memory (bounded, privacy-aware)
- Add emotion classification pipeline and response modulation

### Days 5–6: Coping Toolkit and RAG
- Build coping strategies library (CBT prompts, grounding, journaling)
- Set up embeddings + vector store for relevant, safe retrieval
- Create journaling and mood tracking flows with simple analytics

### Days 7–8: Frontend UX and Accessibility
- Flutter UI for chat, mood inputs, exercises, and journal timeline
- Localization support, large text, high contrast, screen reader labels
- Offline-first drafts and seamless sync; rate-limited API calls

### Days 9–10: Testing, Safety Audits, and Launch Prep
- Unit/integration tests incl. red-team scenarios and crisis tests
- Load testing, observability, and privacy reviews
- Beta release checklist, feedback loop, and next-steps roadmap

## 🎯 Impact Goals
- Reduce loneliness and anxiety spikes by offering immediate, empathetic support
- Encourage help-seeking behavior and early intervention
- Provide a safe, stigma-free space to reflect and grow

## 📈 Success Metrics
- Session quality (post-chat self-report + sentiment delta)
- Crisis detection precision/recall and response time
- Retention of journalers and exercise completion rates
- Opt-in NPS and qualitative feedback from pilot users

## 🙋‍♂️ Personal Motivation
Mental health is close to my heart. Friends and peers often struggle silently due to stigma and access barriers. I’m building this to make compassionate support feel reachable—anytime, anywhere—while honoring safety, ethics, and human dignity.

## 🔧 Tech Stack (Initial)
- Frontend: Flutter (mobile + web), Riverpod/Bloc, Material 3
- Backend: FastAPI, Uvicorn, PostgreSQL, Redis (rate limits/queues)
- AI: OpenAI API or local LLM, LangChain, pgvector/Pinecone
- Infra: Docker, GitHub Actions, Fly.io/Render (starter deploy)

## 🚀 Getting Started (placeholder)
```bash
# Placeholder until code is added (post-planning phase)
# API
uvicorn app.main:app --reload

# Flutter
flutter run
```

## 🤝 Contributing
We welcome contributions from mental health professionals, designers, and developers. Please open issues for safety concerns or improvement ideas.

## 📞 Important Resources
- International Suicide Hotlines: https://www.opencounseling.com/suicide-hotlines
- India Helpline (Kiran): 1800-599-0019
- If you are in immediate danger, contact local emergency services.

---
Disclaimers: This app does not provide medical advice. It is not a replacement for licensed therapy. If you are in crisis, please seek professional help immediately.
