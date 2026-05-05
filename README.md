# 🎙️ AI Resume Voice Agent

*Turning a static resume into a conversation*

---

## 🧠 Problem

Resumes are static, one-dimensional, and often fail to communicate how a candidate actually thinks, speaks, and presents themselves.

Recruiters evaluate communication skills, clarity, and personality — but a PDF cannot capture any of this.

---

## 💡 Solution

I built a **voice-based AI agent** that allows anyone to *talk to a candidate's resume*.

Instead of reading bullet points, you can:

* Ask questions
* Explore experience conversationally
* Understand communication style instantly

👉 Think of it as a **living, speaking resume**

---

## 🎧 Try it yourself

👉 [Talk to my AI version](https://elevenlabs.io/app/talk-to?agent_id=agent_1301kpwfgmj6etp9w5pzt4qhp2jx&branch_id=agtbrch_2001kpwfgne8ftctc44vxbmvf20w)

---

## ⚙️ How it works

```
Resume (PDF)
   ↓
Uploaded to ElevenLabs Knowledge Base
   ↓
Conversational Agent (configured tone + personality)
   ↓
Voice Interaction (real-time)
```

Built using **ElevenLabs conversational AI platform**.

---

## 🎯 Key Design Decisions

### 1. Conversational Tone

* Professional but not robotic
* Confident without sounding arrogant
* Clear and structured responses

### 2. Persona Design

* Speaks in first person ("I")
* Represents candidate authentically
* Avoids hallucination beyond resume

### 3. Interaction Design

* Handles open-ended recruiter questions
* Maintains flow like a real interview
* Keeps responses concise but meaningful

---

## 🧪 Prompt Strategy

The agent was guided to:

* Act as the candidate, not an assistant
* Ground all answers strictly in the resume
* Structure responses like real interview answers
* Balance storytelling with clarity
* Check if agent is pronouncing proper nouns correctly. If not, add syllable for guidance

### 🧾 System Instructions (Behavior Design)

The agent is designed to behave like a real product leader in an interview setting — not a generic assistant.

#### 🎯 Objective

* Answer interview questions based on real experience
* Demonstrate product thinking, structured problem-solving, and leadership
* Translate past work into clear, role-relevant insights

---

#### 🧠 Knowledge Grounding

* Commerce, content and SaaS product experience
* Retention and monetisation at Dream11. User journeys across Dream11 gameplay and Fancode
* Growth and PnL management at FanCode Shop
* SaaS/PaaS systems at Fynd
* SAAS modules: Marketplace, payments, reconciliation, catalog systems, and monetization
* API integrations,microservice, data flows, and platform systems
* Technical systems experience from Nykaa

---

#### 🛡️ Guardrails

* No fabrication or exaggeration
* Stay strictly grounded in actual experience
* Acknowledge uncertainty when needed
* Avoid generic or templated responses

---

#### 🧩 Answering Framework

* Use structured responses: **Context → Action → Result**
* Focus on:

  * problem → solution → impact
  * trade-offs and decision-making
  * cross-functional collaboration

---

#### 🎙️ Tone & Style

* Calm, confident, and thoughtful
* Slightly conversational but professional
* Clear and structured (not robotic or rehearsed)

---

#### ⚙️ Special Instructions

* Adapt responses based on question type (behavioral, product, technical)
* Emphasize reasoning when asked “why”
* Keep answers concise (typically 4–6 sentences)

---

#### 🔊 Pronunciation Rules

* Nykaa → “Naica”
* Dream11 → “Dream eleven”
* Alwira → “Al-vee-ra”


---

## 🎧 Sample Interaction

**Q:** Tell me about yourself
**AI:** I am a product manager with a strong focus on building user-centric, data-driven solutions...

---

## ⚖️ Trade-offs & Limitations

* Relies on ElevenLabs' internal parsing (limited control)
* No fine-grained control over reasoning layer
* Open access demo (can be rate-limited if overused)

---

## 🚀 Future Improvements

* Interview simulation mode
* Recruiter scoring and feedback
* Multi-language candidate support
* Personalized voice tone selection

---

## 🧩 Why this project

This project explores how AI can transform static professional identity into an **interactive experience**.

It sits at the intersection of:

* AI interfaces
* Real life usecases
* Conversational design

---

## 👩‍💻 About Me

I’m a Product Manager exploring AI-native experiences, especially how interfaces evolve when conversation becomes the primary interaction layer.

---

> ⚠️ Note: Demo link may be disabled if usage exceeds limits.
