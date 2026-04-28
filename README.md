# AI Engineer | Product manager
- Telegram: [@Int9ns9](https://t.me/Int9ns9)
- GitHub: [1NT9NS9](https://github.com/1NT9NS9)
- Site: [fastable.ru](http://fastable.ru)

---

# Professional activity
## 1) [AI system for sales call analysis](https://github.com/1NT9NS9/ai-call-qa-sales)
- **Project:** AI system for sales call analysis.
- **Task:** Automate post-call reviews and build an applied agent/RAG/backend workflow for teams working with post-call reviews, call quality control, and sales communication analysis.
- **What I did:** Designed and implemented an `audio -> speech-to-text -> embeddings -> retrieval -> LLM analysis -> structured output -> API/webhook` pipeline in Async Python. Used the HF test set (Hugging Face); built a retrieval layer on pgvector for a knowledge base of 13 directions and 130+ documents, added embeddings, configured orchestration, and tool use via LangChain. Implemented API Contract, typing, Schema Validation, acceptance criteria, and test coverage for the core logic. Configured Timeout Handling, Retry Logic, Rate Limits, Webhook Processing, and a fallback chain for failures or invalid structured output. Implemented a FastAPI backend, a PostgreSQL data model, and local deployment via Docker Compose.
- **Result:** Built a system that generated structured results on an internal test set in an average of ~4 seconds per run and automated key stages of post-call review: transcription, context retrieval, scorecard, and next-best-action generation.
- **Stack:** Python, Async Python, FastAPI, LangChain, RAG, pgvector, PostgreSQL, Structured Output, Function Calling, Schema Validation, Embeddings, REST API, Webhooks, Docker, Docker Compose, Timeout Handling, Retry Logic, Fallback.


## 2) AI system for comparing hypotheses [1](https://github.com/1NT9NS9/agentic-01) [2](https://github.com/1NT9NS9/agentic-02-open)
- **Project:** AI system for comparing hypotheses.
- **Task:** Build a reproducible multi-agent workflow for running multiple agent roles, performing judgement comparisons based on business criteria, and storing run artifacts.
- **What I did:** Designed an async-first workflow using Async Python and FastAPI within the logic of `hypothesis input -> context normalization -> parallel agent runs -> structured outputs -> judgement flow -> final report -> API/dashboard`. Implemented parallel execution of up to 10 agent roles, collection of results by the orchestrator layer, and final aggregation via LLM-as-a-Judge. Integrated OpenAI and Gemini, normalized responses via Pydantic, added typing, Schema Validation, API Contract, Timeout Handling, Rate Limits, Cost Control, Redis caching, Retry Logic, and fallback between providers. Saved run artifacts in md files, retained the Human-in-the-Loop stage for manual review of intermediate results, and added test coverage for the key logic of data transfer between workflow stages.
- **Result:** Built a system that, on an internal test set, allowed reproducible comparison of hypotheses across 5+ business criteria sets via judgement flow, saved artifacts from all runs, and reduced the manual assembly of the initial review to a single workflow run with an average full run time of approximately 8 seconds. The workflow automated hypothesis transmission to agents, context provisioning, collection of intermediate estimates, and final result summation.
- **Stack:** Python, Async Python, FastAPI, OpenAI API, Gemini API, Pydantic, Structured Output, Workflow Orchestration, LLM-as-a-Judge, API Contract, Schema Validation, Redis, Caching, Timeout Handling, Retry Logic, Fallback, React, Vite, pytest, Git.

## 3) [An AI product for processing and structuring news feeds](https://github.com/1NT9NS9/fast-news-ai.git)
- **Project:** An AI product for processing and structuring news feeds.
- **Task:** Reduce user information overload by automating filtering, deduplication, clustering, and summarization of news.
- **What I did:** Designed a multi-step pipeline: `news channels -> ingestion -> deduplication -> chunking -> embeddings -> clustering/retrieval -> LLM summarization -> digest delivery`. Implemented news feed processing with deduplication and clustering based on embeddings + cosine similarity, added a retrieval contour to incorporate relevant context into the final digest. Manually calibrated result quality thresholds and performed manual quality calibration of the final output. I built an orchestration in Async Python, used typing, and added Schema Validation, API Contract, Timeout Handling, Rate Limits, Redis caching, and test coverage for key processing logic. I refined integrations, took external API limitations into account, and optimized the cost of LLM calls by controlling context volume.
- **Result:** Launched the product from scratch and reached 100 MAU; automated news processing from 100+ channels and reduced the time it took to obtain the final summary in 7 days from approximately 300 minutes of manual reading to ~30 seconds of final results.
- **Stack:** Python, Async Python, Gemini API, PostgreSQL, Redis, Python Telegram Bot, Embeddings, Cosine Similarity, Chunking, Retrieval, Schema Validation, API Design, Timeout Handling, Rate Limit Handling, Docker, Docker Compose, CI/CD, VPS, Hosting.

## 4) [AI assistant for market data analysis](https://github.com/1NT9NS9/finance-ai)
- **Project:** AI assistant for market data analysis.
- **Task:** Build an applied AI service that helps users work with financial and macroeconomic data through a user-friendly interface and RAG logic.
- **What I did:** Implemented the pipeline `market data APIs -> normalization -> tables/features -> retrieval/context enrichment -> LLM analysis -> structured interpretation -> web UI/API`, in which market and macroeconomic data via the API were converted to a tabular format, supplemented with relevant context, and analyzed by a model. I took over the backend and web interface in Python, refined the LLM integrations, added application checks, a custom flow from request to result, and logic for issuing signal interpretations in a user-friendly format.
- **Result:** Delivered the AI ​​service to a working release with a user-defined flow from request to signal interpretation based on market data.
- **Stack:** Python, Flask, React, JavaScript, RAG, SQLite, Pandas, Scikit-learn, Docker, Docker Compose, CI/CD, VPS, Hosting.

## 5) [Machine learning projects](https://github.com/1NT9NS9/1NT9NS9/blob/main/README(finance).md)

---

# Technical Skills

## Programming Languages
- Python / SQL / TS / JS

## Data Analysis and Visualization
- Pandas, NumPy — data processing and analysis
- Matplotlib, Seaborn — exploratory and presentation visualization

## Machine Learning Frameworks and Algorithms
- Scikit-learn — classic algorithms
- XGBoost, LightGBM, CatBoost — gradient boosting

## Deep Learning and NLP
- PyTorch — neural network development
- LSTM — sequence modeling
- Hugging Face Transformers — modern NLP pipelines

## LLM Development
- Gemini (Antigravity, CLI) Claude code (CLI, IDE, Cloud), Codex (CLI, IDE, Cloud)
- OpenAI (GPT-5.5), AIStudio (Gemini-3.1 Pro), ClaudeAI (Sonnet4.7)

## DevOps and tools
- GitHub/Action(Linter, Build, Test, Typecheck), Docker/Compose, Deployment (hosting/domain), WSL, Antigravity, Cursor, PyCharm
- Google cloud, VertexAI (SDK, API), Tg bots, Sandbox (vercel, e2b), Firecrawl, N8n, Lovable, OpenRouter, ElevenLabs etc
- Agentic system: Cline, Memory bank, Context/Prompt/Concept Engineering, Tools, Multi-Agent Orchestration


