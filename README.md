# Hi, I'm Jonathan Chong 👋

**AI Builder & Educator** · San Francisco, CA
M.S. Data Science · B.S. Chemistry · AWS AI Practitioner · Real Estate

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jjschong-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/jjschong)

---

## About Me

I'm hooked on AI building, learning, and networking.  Python since 2019, Data Science since 2024, AI-coding for a year.  I'm available for AI/DS/ML roles in the SF Bay Area or remote. My background spans Python ML pipelines, cloud data tools (AWS), and building full-stack agentic apps like calendar.jchong.dev -- which scrapes dozens of bay area event calendars for an all-in-one no-fomo result!

Previously ran a 21-year self-employed real estate business (7 units, end-to-end): financing, operations, contractor management, P&L. That sharpened the applied problem-solving that I now bring to data.

---

## Tech Stack

**Claude Code & Codex in VSCode**
**MCP and A2A**
**Languages (pre-AI)** Python · R · SQL
**ML/Data:** TensorFlow/Keras · Scikit-learn · PCA · Pandas · Jupyter
**Cloud/Infra:** AWS Lambda · AWS Textract · Supabase
**Web:** React · JavaScript
**Tools:** Tableau · Git · GitHub Actions · FireCrawl, x402

---

## Featured Projects

### 🗓️ What's Up In — Free Event Calendars for Dozens of Cities
**[whatsupin.ai](https://whatsupin.ai)** · *source private*
Scheduled Python pipelines pull event listings from many sources per city, de-duplicate them, and publish fast static calendar sites on Cloudflare Pages, plus a public MCP server so AI assistants can search the same events. Grew out of QuickCal ([calendar.jchong.dev](https://calendar.jchong.dev)), my original Bay Area aggregator.
`Python` `Playwright` `SQLite` `Cloudflare Pages` `MCP`

---

### 💼 AI Job-Search Pipeline
**[jobs-public](https://github.com/jjchong5/jobs-public)** (sanitized public copy)
Scrapes job postings, tags and ranks them with Claude (Haiku by default, escalating to Sonnet on low confidence), and serves them in a Streamlit UI with an MCP server. 566 real postings ingested and tagged end to end. Built as my M.S. capstone.
`Python` `Claude API` `SQLite` `Streamlit` `MCP`

---

### 📈 Kalshi Prediction-Market Scanner
**[kalshi-edge-scanner](https://github.com/jjchong5/kalshi-edge-scanner)** (showcase; methods private)
Scheduled pipeline that scans tens of thousands of open prediction markets, researches the best candidates with an LLM using web search, and reports mispricings.
`Python` `Claude API` `SQLite`

---

### ⚽ World Cup 2026 Trading Bot
**[worldcup-public](https://github.com/jjchong5/worldcup-public)** (case study; strategy code private)
Ran live on Polymarket during the tournament: market discovery, fill-realistic edge calculation against the live order book, position reconciliation, and failure alerting. The write-up covers the reliability lessons from going live.
`Python` `Polymarket CLOB` `Backtesting`

---

### 🧠 GPT-Style Transformer From Scratch
**[GPT2-test-model](https://github.com/jjchong5/GPT2-test-model)** · **[Live demo](https://huggingface.co/spaces/jjschong/GPT2testing-medicaldata)**
Decoder-only transformer built from scratch and trained on doctor–patient dialog, with character vs. BPE tokenization experiments (ROUGE-1 0.17 → 0.36), regularization and overfitting analysis, and KV-cache inference.
`Python` `PyTorch` `NLP`

---

### 💸 x402 Pay-Per-Book Library
**[VCN37-payment](https://github.com/jjchong5/VCN37-payment)** · **[Live demo](https://vcn37-payment.onrender.com/)**
HTTP 402 micropayments: a $0.01 USDC paywall (testnet) where a wallet signs an EIP-3009 authorization and the server settles on-chain before returning the book. Built at Vibe Coding Nights #37.
`Node.js` `x402` `USDC` `Express`

---

### 🤖 PhysAI Robotics Hackathon 2026 (SoloTech)
**[ACT Pouring Model](https://github.com/jjchong5/PhysAI-Hack2026-ACT-pouring-model)** · **[LeRobot SO-101 Fork](https://github.com/jjchong5/lerobot-SO101-PhysAIHackathon-SoloTech)**
Trained an ACT (Action Chunking Transformer) policy on a physical SO-101 robot arm for water pouring, from about 25 teleoperated episodes. Fixed Windows camera compatibility in the LeRobot training pipeline to enable local training. Competed in the SoloTech category at PhysAI Hackathon, Feb 2026.
`Python` `LeRobot` `ACT` `Robotics`

---

### 🎬 LUMIS — AI Spatial Cinema (OpenWorld Hackathon · Runner-Up)
**[Live Demo](https://filmverse-eight.vercel.app/)**
Browser-based AI filmmaking tool: build, direct, and review 3D scenes with natural language. Built with Three.js; characters have persistent memory, personality, and autonomous behavior. Team of 3; placed runner-up in multiple categories.
My contributions: architected the core LLM/API bridge to OpenRouter with Claude failover; integrated 3D character assets via Meshy; refined character interaction logic and UX.
`JavaScript` `Three.js` `OpenRouter` `Meshy` `WebXR`

---

### ☁️ Textract Resume Pipeline
**[textract-resume-lambda](https://github.com/jjchong5/textract-resume-lambda)**
S3-triggered AWS Lambda that runs Textract on uploaded PDF resumes and writes name, email and skills to CSV.
`Python` `AWS Lambda` `AWS Textract`

---

## Certifications & Education

**AWS Certified AI Practitioner** — Amazon Web Services *(2026)*

**M.S. Data Science** — Eastern University *(4.0 GPA)*
Keras · TF · Sklearn · SQL · R · Tableau · Jupyter

**B.S. Chemistry** — George Fox University

---

## Currently Looking For

DS / ML / Data Engineering roles in the **SF Bay Area** (or remote).
Open to internships, contracts, and project collaborations.
→ [linkedin.com/in/jjschong](https://linkedin.com/in/jjschong) · jjchong@msn.com
