<a href="https://abdullahyamin.github.io">
  <img src="assets/banner.svg" width="100%" alt="Abdullah Yamin, Artificial Intelligence Engineer">
</a>

<p align="center">
  <a href="https://abdullahyamin.github.io"><img src="https://img.shields.io/badge/View_my_portfolio-abdullahyamin.github.io-7ee0c3?style=for-the-badge&labelColor=12161e" alt="View my portfolio at abdullahyamin.github.io"></a>
</p>

## About me

I'm **Abdullah Yamin**, an **Artificial Intelligence Engineer** with a background in AI Engineering at Bahçeşehir University in Istanbul.

I build retrieval-augmented and multi-agent LLM systems, then test them hard enough to know whether they can be trusted. I'm drawn to problems where a wrong answer has a real cost: clinical decisions, official rules people rely on, and misinformation.

**How I work**

- **Show the source.** My assistants cite the document and article behind every claim.
- **Privacy by default.** Local models and synthetic data whenever people's personal data is involved.
- **Measure, then claim.** Benchmarks, ablations and error analysis come first, and I report the misses along with the wins.
- **Fail safely.** An honest "I don't know" beats a confident wrong answer.

## Featured work

**[ClinicalBridge](https://github.com/abdullahyamin/Clinical-Bridge-)** · multi-agent clinical decision support<br>
Four local LLM agents turn a remote patient-monitoring alert into a clinician-ready brief with a full audit trail. Evaluation caught the model writing a detail into patient summaries that wasn't in their records, and a sentence-level grounding validator took the **safety pass rate from 80% to 100%**.<br>
<sub>LangChain · Ollama (Llama 3.1 8B) · ChromaDB · Pydantic · runs locally on fictional patients</sub>

**[Bahçe-sihir](https://github.com/abdullahyamin/bahce-sihir)** · bilingual RAG assistant for university regulations<br>
Answers students' questions in Turkish or English from official university documents, citing the document and article for every claim. Finding a silent reranker cut-off lifted **precision@5 from 0.31 to 0.71**, and fixing a FAISS–PyTorch threading clash helped cut **latency from 30s+ to 6–10s**. **Zero hallucinations** on a hand-checked 15-question test. Team capstone.<br>
<sub>FastAPI · Gemini · sentence-transformers · BM25 · cross-encoder reranking · React · Docker</sub>

**[Fake-news detection, audited for bias](https://github.com/abdullahyamin/fake-news-detection-with-built-in-bias-analysis.)** · NLP and interpretability<br>
DistilBERT (**99.6% accuracy**) against a TF-IDF baseline on 44,898 articles, followed by a three-stage audit of what the models actually learned. The most influential words turned out to be about style, not substance: high accuracy isn't the same as understanding.<br>
<sub>PyTorch · Hugging Face Transformers · scikit-learn · LIME · Streamlit</sub>

**[Customer-churn MLOps pipeline](https://github.com/abdullahyamin/customer-churn-mlops-)** · production machine learning<br>
Schema-validated data in, a monitored model behind an API out: MLflow tracking and model registry, Optuna tuning, FastAPI and batch inference, PSI/KS drift monitoring, Docker, and CI that lints, tests and runs the whole pipeline.<br>
<sub>scikit-learn · MLflow · Optuna · FastAPI · Docker · GitHub Actions</sub>

## Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-12161e?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-12161e?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Hugging_Face-12161e?style=for-the-badge&logo=huggingface&logoColor=white" alt="Hugging Face">
  <img src="https://img.shields.io/badge/LangChain-12161e?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/Ollama-12161e?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama">
  <img src="https://img.shields.io/badge/Gemini-12161e?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini">
  <img src="https://img.shields.io/badge/scikit--learn-12161e?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/FastAPI-12161e?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/MLflow-12161e?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLflow">
  <img src="https://img.shields.io/badge/Docker-12161e?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub_Actions-12161e?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/pytest-12161e?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest">
  <img src="https://img.shields.io/badge/TypeScript-12161e?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-12161e?style=for-the-badge&logo=react&logoColor=white" alt="React">
  <img src="https://img.shields.io/badge/Next.js-12161e?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/PostgreSQL-12161e?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
</p>

---

<p align="center">
  <b>The full story behind each project is on my portfolio: <a href="https://abdullahyamin.github.io">abdullahyamin.github.io</a></b>
</p>
