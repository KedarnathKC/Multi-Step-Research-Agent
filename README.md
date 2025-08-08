# Multi-Step-Research-Agent

**Status:** MVP planning  
**Goal:** Given a text prompt _or_ a research paper (URL/PDF), the agent finds relevant papers (for prompts), parses the PDF(s), **extracts tables & figures**, and produces a **grounded PDF report** with TL;DR, methods, key metrics (with evidence), figures, and limitations.  
**No local model serving** — all LLM calls go through a hosted API.

---

## Features (MVP)

- 🔎 **Prompt → Papers** via arXiv / Semantic Scholar search + reranking  
- 📄 **PDF Parse** with page/section structure  
- 📊 **Table extraction** to Markdown/HTML  
- 🖼️ **Figure extraction** with captions + page refs  
- 🧠 **LLM-aided extraction & summarization** (requires evidence pointers)  
- 📑 **Final PDF report** rendered from HTML (anchors to pages/sections)  
<!-- - 🧪 Tiny evals: retrieval@k, metric-extraction accuracy, faithfulness -->

---