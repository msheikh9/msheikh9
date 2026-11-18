# Mutwalli Alsheikh

Computer Science student at United Arab Emirates University focused on **AI/ML and backend engineering**. I build retrieval models, LLM agents, and ML pipelines, with an emphasis on measuring what works.

**Expected graduation:** August 2027 · **Available:** Summer 2027 internships · **U.S. citizen — no sponsorship required**

**[Resume](https://github.com/msheikh9/msheikh9/raw/main/Mutwalli_Alsheikh_Resume.pdf)** · **[LinkedIn](https://linkedin.com/in/mutwa11i)** · **[Email](mailto:alsheikhmutwalli@gmail.com)**

## Selected projects

### [FinRetriever](https://github.com/msheikh9/FinRetriever)
Financial document retrieval over **49 SEC 10-K filings and 10,137 traceable passages**. Fine-tuned BGE-base across three seeds on 678 synthetic query–passage pairs, then combined it with BM25, reciprocal rank fusion, and company/fiscal-year metadata. Mean MRR@10 increased from **0.266 (pretrained) to 0.665 (fine-tuned) to 0.851 (hybrid)** on **93 synthetic validation questions**. Includes leakage checks, checkpoint verification, reproducible experiments, and 1,287 tests passing in a fresh clone. Independent human relevance evaluation remains incomplete.

### [AutoPilot](https://github.com/msheikh9/AutoPilot) · [Live demo](https://auto-pilot-vert.vercel.app)
LLM agent platform with six tools, human approval gates, failure recovery, retrieval-backed memory, and replayable WebSocket traces. Combines a FastAPI backend with a Next.js interface, PostgreSQL, and Redis. Completed **22/26 tasks on a custom benchmark** at $0.84 total inference cost; 565 tests across 35 modules.

### [Market Regime Forecasting](https://github.com/msheikh9/market-regime-stock-predictor)
Walk-forward ML evaluation across **1,260 out-of-sample trading days and five folds**. Compared LightGBM models with simple baselines, corrected transaction costs understated by 62x and leakage at fold boundaries, and added 96 tests. The classifier performed near chance (**ROC-AUC 0.502**), a finding documented alongside the backtest results.

### [Adaptive Duelist AI](https://github.com/msheikh9/adaptive-duelist-ai)
Combat AI sandbox combining Markov chains and Random Forest predictions with a shared simulation engine, deterministic replay, and a REST API. Across **400 matched-seed games per tier**, the full system reduced mean time to defeat opponents by **72% (3,559 to 980 ticks)**. Ablations traced the main gain to the scripted reaction layer; 1,063 tests cover the engine and ML pipeline.

## How I work

I build benchmarks, baselines, ablations, and regression tests alongside the implementation. I document evaluation limits and negative results so that engineering decisions follow the evidence.

**ML & retrieval:** Python · PyTorch · Hugging Face Transformers · sentence-transformers · scikit-learn · LightGBM · BM25 · Qdrant

**Applications & infrastructure:** TypeScript · FastAPI · React · Next.js · PostgreSQL · Redis · Docker · GitHub Actions
