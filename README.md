# Hey, I'm Anya Rajesh 👋

I'm a Computer Science student focused on building AI systems that solve practical, real-world problems. My work spans community safety, healthcare, and trustworthy information systems—domains where reliable technology can have a meaningful impact on people's lives. I build end-to-end machine learning and LLM pipelines, develop production-ready full-stack applications, and care deeply about transparent reasoning, responsible deployment, and clean system design.

## 🚀 Featured Projects

### 🔎 Axiom

Evidence-led claim analysis platform for transparent, source-backed verification

Built and deployed a full-stack system that transforms free-form text into checkable claims, retrieves relevant sources, evaluates conflicting information, and produces explained verdicts.

* Claim Decomposition: Used structured LLM outputs to separate paragraphs into individual, verifiable claims while preserving their original context.
* Hybrid Retrieval: Combined a curated Qdrant corpus with Tavily web search fallback to find relevant evidence from traceable sources.
* Verification Pipeline: Orchestrated retrieval, reranking, entailment analysis, contradiction detection, and final judgment through a LangGraph workflow.
* Transparent Results: Returned supported, contradicted, or insufficient-evidence verdicts with confidence scores, explanations, and direct source links.
* Production Architecture: Built with FastAPI, Next.js, Groq, Qdrant, and Neon Postgres; deployed across Vercel and Render with automated GitHub Actions testing.


### ⚡ Vigil AI

AI-powered cybersecurity monitoring and automated incident response platform

Built a real-time threat detection system that ingests and analyzes live log data across distributed systems to identify and respond to security incidents.

* Real-Time Detection: Designed ML-driven anomaly detection on log streams to flag suspicious behavior, attack patterns, and indicators of compromise (IoCs).
* Scalable Backend: Developed a FastAPI-based ingestion pipeline that processes logs from multiple sources (servers, firewalls, cloud services) and normalizes them for analysis.
* Threat Contextualization: Mapped detected events to the MITRE ATT&CK framework, giving immediate insight into attacker tactics and progression.
* Automated Response: Implemented rule-based and threshold-triggered playbooks to isolate systems, revoke credentials, and generate structured incident reports.
* Visualization Layer: Built a React dashboard displaying live alerts, threat severity scoring, and incident timelines for quick decision-making.


### 🏥 MedInsight AI

Intelligent clinical decision support system for symptom-based diagnosis

Developed an end-to-end machine learning system that transforms patient symptoms and clinical text into ranked diagnostic insights with supporting research.

* Diagnostic Modeling: Trained a multi-label classification model across a wide range of diseases and symptoms to generate probability-ranked differential diagnoses.
* Clinical NLP Pipeline: Used transformer-based models (BERT) to extract structured medical entities from unstructured clinical input.
* Research Integration: Connected to external medical research APIs to retrieve relevant studies, treatment guidelines, and clinical data in real time.
* Automated Reporting: Generated structured outputs including clinical summaries, SOAP notes, and simplified patient explanations using LLMs.
Privacy-Focused Design: Built with data anonymization, audit logging, and optional local inference to align with healthcare data standards.

## 🤖 Technical Stack

Python, TypeScript, JavaScript, SQL, BashMachine Learning & AIPyTorch, TensorFlow, scikit-learn, Keras, Hugging Face, LangChainNLP & LLMsBERT, GPT-4, RAG pipelines, OpenAI APIBackendFastAPI, Node.js, REST APIs, PostgreSQL, RedisFrontendNext.js 14, React, Tailwind CSS, TypeScriptDevOps & CloudDocker, AWS, GCP, Vercel, GitHub Actions, Pandas, NumPy, Matplotlib, Seaborn, Jupyter

## 📚 Current Focus

I'm currently deepening my work in large language model fine-tuning, agentic AI systems, and building more robust evaluation frameworks for medical AI models. Always interested in projects that push AI into high-stakes, high-impact domains.

## 🔗 Let's Connect

Portfolio: https://anya-rajesh.vercel.app/

GitHub: @anyarajesh1

LinkedIn: http://linkedin.com/in/anya-raj

