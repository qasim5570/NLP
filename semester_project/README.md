This contains the semester project for NLP, which has the following features:


PHASE 1 — Foundation (Weeks 1–3)
  • Study transformer attention in PyTorch (build a tiny one)
  • Train Word2Vec on SEC 10-K filings
  • Extract Gemma 2B embeddings for the same corpus
  • Visualize and compare → this IS your "how transformers encode meaning" deliverable

PHASE 2 — Fine-Tuning (Weeks 4–6)
  • Set up Kaggle/Colab with PEFT + bitsandbytes
  • LoRA fine-tune Gemma 2B on FinQA dataset
  • Log loss curves, compare before/after outputs
  • This IS your "how fine-tuning changes behavior" deliverable

PHASE 3 — RAG Pipeline (Weeks 7–9)
  • Connect Financial API, fetch data, chunk and embed it
  • Store in ChromaDB (vector store)
  • Build retrieval → prompt injection → Gemma answer pipeline
  • This IS your "grounding in external knowledge" deliverable

PHASE 4 — LangGraph Agent (Weeks 10–11)
  • Wrap Phase 2 + Phase 3 into a LangGraph graph
  • Define nodes: query parser, API fetcher, retriever, analyzer
  • Add a basic retry loop on low-confidence answers

PHASE 5 — Evaluation (Week 12)
  • Build 50-question benchmark from financial Q&A
  • Run RAGAS metrics: faithfulness, answer relevancy
  • Ablation: base vs. fine-tuned vs. fine-tuned+RAG
  • This IS your "evaluate LLM systems rigorously" deliverable
