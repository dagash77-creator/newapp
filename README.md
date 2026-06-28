
# 🚀 Market Research Assistant (NotebookLM for Strategic Intelligence)

An advanced, multimodal **Multi-Document Research Agent** inspired by the core architecture of Google NotebookLM. Tailored specifically for deep market exploration, competitive intelligence, and product strategy, this agent dynamically sources data from the web, processes it into transient knowledge bases, and provides structured analytical outputs with strict source grounding to eliminate hallucinations.

Live Application: `https://newapp-ochre-ten.vercel.app/`

---

## 💡 Design Philosophy & Innovation (Judges' Overview)

> **"Instead of forcing the user to manually collect market reports and upload them (which often leads to data gaps and outdated insights), this agent is uniquely engineered as an *Automated Web-Sourcing Multi-Doc Agent*. The agent performs an autonomous Deep Research sweep across the web, instantly constructing a real-time *Dynamic Knowledge Base* from the latest market data available. It then processes these multiple dynamically-generated documents to synthesize six distinct strategic reports with high accuracy and strict source citations."**

By shifting from manual uploads to automated, real-time web sourcing, this architecture provides a far more autonomous and scalable solution. The user simply enters a product name, and the agent completely automates the documentation gathering, indexing, and synthesis process.

---

## ✨ Key Features & Strategic Analytical Frameworks

The system orchestrates complex multi-agentic workflows to ingest live data and synthesize it into **6 comprehensive strategic modules** accessible via the interactive dashboard:

1. 📈 **Market Position:** Mapping the product landscape, baseline valuations, and target audience segments.
2. 🎯 **SWOT Analysis:** Contextual parsing of internal Strengths/Weaknesses and external Opportunities/Threats.
3. 🌍 **PESTELE Matrix:** Dynamic macro-environmental tracking (Political, Economic, Social, Technological, Environmental, Legal, Ethical).
4. 🛡️ **Porter’s 5 Forces:** Structural evaluation of competitive rivalry, buyer/supplier power, and substitution threats.
5. 📊 **Quantitative Trend Valuation Matrix:** (As shown in the live dashboard UI) Deep data synthesis displaying:
   * **Metrics Dimensions:** Trackers like *Global Market Valuation Size* and *Customer Acquisition Index (CAC)*.
   * **Projections:** Projected CAGR figures computed dynamically.
   * **Strict Grounding:** Primary source citations mapped directly to source records (e.g., *Statista Logistics Database*, *AdWords Benchmarks Q1-2026*).
6. 🎬 **Multimodal Outputs (Presentation & Video Briefing):**
   * **Presentation Deck:** Structural slide-by-slide strategy outline ready for executive pitches.
   * **Video Briefing:** Production-ready script and asset breakdowns for product marketing.

---

## 🧠 System Architecture & Advanced Tech Stack

The architecture is built using cutting-edge enterprise AI practices focusing on high-context handling and custom evaluation logic:

* **Core LLM Engine:** Google Gemini 1.5 Pro / Flash via Google AI Studio API for massive context-window processing and advanced reasoning.
* **Orchestration & Workflow:** Python agentic frameworks handling specialized sub-agents (Strategic Analyst, Contextual Data Bot).
* **Automated Web-Sourcing (Deep Research):** Automated pipelines that search, scrape, and structure live web data dynamically, formatting them into internal "Dynamic Documents" instead of relying on stale, static uploads.
* **Frontend UI:** Responsive Next.js / React web interface optimized for modern data synthesis rendering and deployed on **Vercel**.
* **Enterprise Integration Ready:** Fully compatible with enterprise automation tools (**Make, Zapier, n8n, Power Automate**) for asynchronous pipeline triggering and report delivery.

---

## 🛠️ Installation & Setup

### Prerequisites
* Node.js (v18 or higher)
* Python 3.10+
* Google Gemini API Key

### Local Deployment Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd newapp
   ```

2. **Environment Configuration:**
   Create a `.env` file in the root directory and append your secure API configurations:
   ```env
   NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key_here
   ```

3. **Install Dependencies:**
   ```bash
   npm install
   # For the backend agent engine
   pip install -r requirements.txt
   ```

4. **Run the Application locally:**
   ```bash
   npm run dev
   ```

---

## 🏆 Evaluation Highlights (Build with AI Program)

* **Contextual Data Bot Interaction:** The application features a dedicated sidebar assistant that enables interactive prompt adjustments, live custom evaluation logic verification, and sandbox telemetry configuration.
* **Data Privacy:** Sourced internet documents and telemetry configurations are processed securely and transiently, respecting absolute data boundaries.

---

## 🤝 Acknowledgments
Built with 💙 during the **Build with AI** Program, proudly presented by **Google for Developers** and **GeeksforGeeks**.
