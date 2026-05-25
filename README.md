# CredX — AI-Native Credit Decisioning Platform

> Automate corporate credit analysis end-to-end. CredX transforms raw, unstructured financial documents into structured Credit Appraisal Memos (CAM) using multi-agent AI — cutting underwriting turnaround time by up to **90%**.

---

## 🚀 Demo

<!-- Add a GIF or screenshot here once available -->
> _Screenshot / demo link coming soon_

---

## 🧩 Problem It Solves

Traditional corporate credit underwriting is slow, manual, and error-prone:
- Analysts spend hours extracting data from PDFs, spreadsheets, and scanned documents
- Inconsistent CAM formats across teams
- No audit trail for AI-assisted decisions

**CredX solves this with a fully automated, auditable AI pipeline.**

---

## ✨ Features

| Feature | Description |
|---|---|
| 📄 Document Ingestion | Upload unstructured financials (PDFs, balance sheets, P&L) |
| 🤖 Multi-Agent Orchestration | Specialized agents for extraction, enrichment, and narrative synthesis |
| 🌐 External Intel Scraping | Pulls live market data and company background automatically |
| 📝 Auto-Generated CAM | Produces a structured Credit Appraisal Memo with no manual input |
| 🔍 Transparent Formula Ledger | Every calculation is logged for full audit compliance |
| ⚡ 90% Faster Underwriting | Reduces TAT from days to minutes |

---

## 🛠 Tech Stack

**Frontend**
- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS

**Backend**
- FastAPI (Python)
- Multi-agent orchestration layer
- REST APIs for document processing

**AI / ML**
- LLM-based document extraction
- Structured output generation
- Narrative synthesis agents

---

## 📁 Project Structure

```
credx/
├── frontend/          # Next.js 14 app
│   ├── app/           # App Router pages
│   ├── components/    # UI components
│   └── lib/           # API clients & types
├── backend/           # FastAPI server
│   ├── agents/        # Multi-agent pipeline
│   ├── extractors/    # Document parsers
│   ├── models/        # Pydantic schemas
│   └── main.py        # Entry point
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites
- Node.js 18+
- Python 3.10+
- pip / npm

### 1. Clone the repo
```bash
git clone https://github.com/srvnkumr27/credx.git
cd credx
```

### 2. Backend setup
```bash
cd backend
pip install -r requirements.txt
cp .env.example .env   # Add your API keys
uvicorn main:app --reload
```

### 3. Frontend setup
```bash
cd frontend
npm install
cp .env.local.example .env.local   # Add your API URL
npm run dev
```

### 4. Open in browser
```
http://localhost:3000
```

---

## 🔐 Environment Variables

| Variable | Description |
|---|---|
| `OPENAI_API_KEY` | LLM provider key |
| `NEXT_PUBLIC_API_URL` | FastAPI backend URL |

---

## 🗺 Roadmap

- [ ] PDF upload drag-and-drop UI
- [ ] Multi-company batch processing
- [ ] CAM export to Word/PDF
- [ ] Role-based access control
- [ ] Integration with banking CRMs

---

## 🙋 Author

**M Sravan Kumar Varma**
- GitHub: [@srvnkumr27](https://github.com/srvnkumr27)
- Email: srvnkumr27@gmail.com
- LinkedIn: [M Sravan Varma](https://linkedin.com/in/m-sravan-varma)

---

## 📄 License

MIT License — feel free to use and build on this.

---

> Built as part of a personal initiative to explore AI applications in financial services. Open to feedback and contributions!
