# Mutwalli Alsheikh

AI/ML engineer building LLM agent systems, retrieval pipelines, and evaluated ML models. CS @ United Arab Emirates University, graduating Dec 2027. Detroit, MI.

**[Resume](https://github.com/msheikh9/msheikh9/raw/main/Mutwalli_Alsheikh_Resume.pdf)** · **[LinkedIn](https://linkedin.com/in/mutwa11i)** · alsheikhmutwalli@gmail.com

## Projects

**[AutoPilot](https://github.com/msheikh9/AutoPilot)** — Autonomous LLM agent platform: ReAct planning over 6 tools, human approval gates, failure classification, WebSocket trace replay. 564 tests. **[Live demo](https://auto-pilot-vert.vercel.app)**

**[RAG Filing Analyst](https://github.com/msheikh9/rag-filing-analyst)** — Local RAG over SEC 10-K filings. Hybrid BM25 + dense retrieval raised Hit@1 from 0.76 to 0.92 on a hand-verified gold set (paired bootstrap, p=0.001). Measured cross-encoder reranking and left it disabled.

**[Market-Regime Pipeline](https://github.com/msheikh9/market-regime-stock-predictor)** — Walk-forward backtesting with honest reporting: no predictive edge found (ROC-AUC 0.504), a cost bug and target leak found and locked down with 96 mutation-tested assertions.

**[Adaptive Duelist AI](https://github.com/msheikh9/adaptive-duelist-ai)** — Real-time opponent modeling with a 3-tier ablation over 400 seeded matches per tier; instrumentation traced 100% of top-tier actions to a hand-written reaction layer, not the learned planner. 1,063 tests.

## How I work

Every project above reports measured results against baselines — including the negative ones. Three of the four contain findings I published instead of hiding: a reranker that didn't help, a model that loses to a rolling mean, a predictor below its majority-class floor.

**Stack:** Python · TypeScript · PyTorch · scikit-learn · LightGBM · FastAPI · Qdrant · PostgreSQL · Docker · GitHub Actions
