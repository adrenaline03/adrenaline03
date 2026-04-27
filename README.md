## Hi, I'm Nalin 👋

AI/ML Engineer focused on **RAG and LLM systems**. Recently shipped production document-intelligence pipelines at **ARX (Dubai)** and built SQL data infrastructure for a SEBI-regulated credit rating agency.

Currently building **Nifty-Lens**, a volatility intelligence platform for the Indian markets, and exploring how to make ML systems more reliable in production.

🏆 BlackRock HackKnight'24 Finalist — Top 10 of 2000+

---

### 🚀 Featured Project

**[Nifty-Lens: Volatility Intelligence Platform](https://nifty-lens.streamlit.app)** &nbsp; · &nbsp; *PostgreSQL · XGBoost · Streamlit · Plotly*

End-to-end analytics platform for the NIFTY 50, built around a question I cared about: *can a model meaningfully separate calm markets from turbulent ones?*

- **Data layer** — PostgreSQL backend with 6 materialized views and 2 stored procedures, powering an ML pipeline that computes 12 engineered technical indicators across 59,763 rows of historical data.
- **Model** — XGBoost volatility-regime classifier with time-series cross-validation. Hits **67.8% accuracy** (vs 33% random baseline) on a 3-class problem, and **86% accuracy on high-confidence predictions** covering 40% of the test set, with calibrated probabilities verified across confidence tiers.
- **Key finding** — Switching the target from next-day to next-5-day volatility produced a **29-percentage-point accuracy lift** from a single-line code change — a larger gain than any hyperparameter tuning, and consistent with the volatility clustering literature.
- **Interface** — 5-page Streamlit dashboard with an interactive portfolio analyzer.

→ **[Live Demo](https://nifty-lens.streamlit.app)** · [Repo](https://github.com/adrenaline03/nifty-lens)

---

### 📫 Reach Me

- **Email** — [nalin.singhal03@gmail.com](mailto:nalin.singhal03@gmail.com)
- **LinkedIn** — [nalin-singhal](https://www.linkedin.com/in/nalin-singhal-553b6a24a/)
- **Resume** — *available on request*
