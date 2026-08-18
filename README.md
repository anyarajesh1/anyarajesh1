# Hey, I'm Anya Rajesh 👋

I'm a Computer Science student focused on building AI systems that solve practical, real-world problems. My work spans community safety, healthcare, and trustworthy information systems—domains where reliable technology can have a meaningful impact on people's lives. I build end-to-end machine learning and LLM pipelines, develop production-ready full-stack applications, and care deeply about transparent reasoning, responsible deployment, and clean system design.

## 🚀 Featured Projects

### 🔎 Axiom

Evidence-led claim analysis with transparent, source-backed verdicts.

Axiom transforms free-form text into checkable claims, retrieves relevant evidence, evaluates conflicting information, and explains the reasoning behind each result.

- **Verification Pipeline:** Orchestrated claim extraction, retrieval, reranking, entailment analysis, contradiction detection, and final judgment with LangGraph.
- **Hybrid Retrieval:** Combined a curated Qdrant corpus with Tavily web search fallback to find relevant, traceable sources.
- **Production System:** Built with FastAPI, Next.js, Groq, Qdrant, and Neon Postgres; deployed on Vercel and Render with automated GitHub Actions testing.

[Live Demo](https://axiom-ten-alpha.vercel.app) · [GitHub Repository](https://github.com/anyarajesh1/Axiom)

### ⚡ Vigil AI

Real-time community safety intelligence for any US ZIP code.

Vigil AI brings crime information, weather conditions, emergency declarations, and AI-generated safety summaries into one accessible dashboard.

- **Hyperlocal Data:** Integrated crime statistics, NOAA and Open-Meteo weather data, FEMA emergency declarations, and location services.
- **AI Summaries:** Used Groq to turn multiple data sources into clear, plain-language neighborhood safety insights and risk levels.
- **Interactive Experience:** Built a Next.js and Leaflet interface backed by FastAPI, then deployed the frontend and API through Vercel and Render.

[Live Demo](https://vigil-ai-two.vercel.app) · [GitHub Repository](https://github.com/anyarajesh1/Vigil-AI)

### 🏥 MedInsight AI

Privacy-first medical document analysis with retrieval-augmented generation.

MedInsight AI lets users upload medical lab PDFs, ask questions about their documents, and receive grounded answers with cited medical sources.

- **Document Processing:** Built native PDF extraction with OCR fallback for scanned documents and redacted sensitive information before processing.
- **Grounded Retrieval:** Used LangChain, ChromaDB, and sentence-transformer embeddings to retrieve relevant medical context and cite its sources.
- **Accessible Interface:** Developed simplified and technical result views in a React and TypeScript frontend designed around privacy and readability.

[GitHub Repository](https://github.com/anyarajesh1/MedInsight-AI)

## 🤖 Technical Stack

- **Languages:** Python, TypeScript, JavaScript, SQL, Bash
- **AI and Machine Learning:** LangGraph, LangChain, RAG, Groq, Hugging Face, sentence-transformers, scikit-learn
- **Data and Retrieval:** Qdrant, ChromaDB, PostgreSQL, Neon, Supabase
- **Backend:** FastAPI, Node.js, REST APIs, SQLModel
- **Frontend:** Next.js, React, Vite, Tailwind CSS, Leaflet
- **Infrastructure:** Vercel, Render, GitHub Actions
- **Data Tools:** Pandas, NumPy, Matplotlib, Seaborn, Jupyter

## 📚 Current Focus

I'm currently exploring LLM evaluation, agentic workflows, retrieval systems, and responsible AI design. I'm especially interested in building systems that remain transparent, reliable, and useful in high-impact domains.

## 🔗 Let's Connect

- **Portfolio:** [anya-rajesh.vercel.app](https://anya-rajesh.vercel.app/)
- **GitHub:** [@anyarajesh1](https://github.com/anyarajesh1)
- **LinkedIn:** [linkedin.com/in/anya-raj](https://linkedin.com/in/anya-raj)
