# Mutwalli Alsheikh

AI/ML engineer building LLM agents, retrieval systems, and evaluation-driven ML pipelines. B.S. Computer Science at United Arab Emirates University, graduating Dec 2027. Detroit, MI. U.S. citizen.

**[Resume](https://github.com/msheikh9/msheikh9/raw/main/Mutwalli_Alsheikh_Resume.pdf)** · **[LinkedIn](https://linkedin.com/in/mutwa11i)** · **[Email](mailto:alsheikhmutwalli@gmail.com)**

## Projects

**[AutoPilot](https://github.com/msheikh9/AutoPilot)** — ReAct-style LLM agent over 6 tools with approval gates, failure recovery, and replayable WebSocket traces. Scored 22/26 tasks on a self-designed benchmark at $0.84 total inference; 564 tests. **[Live demo](https://auto-pilot-vert.vercel.app)**

**[RAG Filing Analyst](https://github.com/msheikh9/rag-filing-analyst)** — Fully local RAG over SEC 10-K filings. Hybrid BM25 + dense retrieval raised Hit@1 from 0.76 to 0.92 and nDCG@10 from 0.83 to 0.96 on a 50-query hand-verified set (paired bootstrap, p=0.001). Cross-encoder reranking added no significant gain at 15x latency and remained disabled.

**[Market-Regime Pipeline](https://github.com/msheikh9/market-regime-stock-predictor)** — Five-fold walk-forward forecasting over 1,260 out-of-sample trading days. Found no predictive edge (ROC-AUC 0.504); a 20-day rolling mean led annualized return/volatility. Fixed transaction costs understated 62x and target leakage at fold boundaries, protected by 96 assertions validated with mutation testing.

**[Adaptive Duelist AI](https://github.com/msheikh9/adaptive-duelist-ai)** — Real-time opponent modeling using Markov-chain and Random Forest predictions. A 3-tier ablation over 400 identically seeded matches per tier traced the performance gain to the hand-written reaction layer, not the learned predictor; 1,063 tests.

## How I work

I treat evaluation as part of the implementation: benchmarks, baselines, ablations, statistical tests, and regression tests are built into the projects above. When a more complex method does not beat the baseline, I document the result and let it drive the engineering decision.

**Stack:** Python · TypeScript · PyTorch · scikit-learn · LightGBM · FastAPI · React · Next.js · Qdrant · PostgreSQL · Redis · Docker · GitHub Actions
