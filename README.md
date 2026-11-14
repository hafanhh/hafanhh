# Hi, I'm Alice (Ha Anh) 👋

**Data Analyst · Vibe Coder · Agentic AI Builder** | Vietnam 🇻🇳

I analyse business data and build applications on large language models (LLMs). My projects include a search assistant that calls functions, a question-answering pipeline that cites and verifies its answers, and tools that ask for approval before changing data. I build with AI coding assistants such as Claude Code.

My background is in International Business, with two postgraduate degrees from the UK. I started in data analysis (SQL, dashboards, statistics), then moved into machine learning, data pipelines and LLM applications.

📫 [alice.hoang1909@gmail.com](mailto:alice.hoang1909@gmail.com) · [LinkedIn](https://www.linkedin.com/in/alicehoang190996/)

---

## LLM skills

Seven areas of LLM application work, each shown in the repositories under Featured projects: function calling, retrieval-augmented generation (RAG), answer verification, structured output, human approval, evaluation and logging, and APIs and applications.

- **Function calling:** the Gemini model decides when to call a search function over my Notion library. I run the function myself to control cost, and I restrict the model to tags that exist in the database.
- **Retrieval-augmented generation (RAG):** dense search, BM25 and hybrid ranking, scored on hand-written questions that include unanswerable ones.
- **Answer verification:** each answer carries citations. A second LLM pass verifies them, and the system refuses to answer when verification fails. The weaknesses of this method are recorded in the repository notes.
- **Structured output:** Pydantic and JSON schemas for answers, verification results and query rewriting.
- **Human approval:** the bot writes to Notion only after I press Confirm, and it never deletes data.
- **Evaluation and logging:** evaluation sets, token and request counters per question, and per-conversation logs.
- **APIs and applications:** Gemini API, Notion API, Telegram Bot API, FastAPI backends, and a React front end.

---

## Featured projects

Four repositories: one data pipeline and three applications built on the Gemini API. Each row states what the project does and the technology it uses.

| Project | What it does | Stack |
|---|---|---|
| [**Logistics Data Pipeline**](https://github.com/hafanhh/masan-logistics-pipeline) | A simulation of an enterprise data pipeline on the public OLIST Brazil e-commerce dataset. Joins three sources (orders, customers, geolocation), cleans them with automated quality checks, and produces delivery key performance indicators (KPIs) by state, month and delay severity. | PySpark, Medallion architecture (Bronze/Silver/Gold), Parquet, Docker, pytest |
| [**Novel Search Bot**](https://github.com/hafanhh/ngontinhlib-bot) | A Telegram bot that answers natural-language questions about my novel library. Gemini calls a search function with filters it chooses, the bot queries Notion, and `/add` and `/edit` write to Notion only after I press Confirm. Every request is logged with token usage. | Python, Gemini function calling, Notion API, Telegram |
| [**Story RAG Assistant**](https://github.com/hafanhh/RAG-truyen-bot) | A learning project: question answering with citations over a Vietnamese web novel, with LLM verification and a refusal rule. I compared dense search, BM25 and hybrid search on 19 hand-written questions. Hybrid search placed at least one evidence passage in the top 5 for 18 of 19 questions, against 15 of 19 for dense search alone. | Python, Gemini embeddings, Chroma, BM25, Pydantic |
| [**AI Platform Demo for Food and Beverage Operations**](https://github.com/hafanhh/financial-agent-app-demo) | A scripted demo of three AI modules for a food and beverage chain: demand forecasting, customer segmentation with approval-gated emails, and a financial question-answering agent with confidence markers, source citations and document upload. | React, Vite, FastAPI, Gemini API |

---

## Tools

- **Languages:** Python, SQL, R
- **AI and LLM:** Gemini API, function calling, structured output, embeddings, RAG, Chroma, prompt design, Claude Code
- **Data and ML:** Pandas, NumPy, PySpark, scikit-learn, Keras, PyTorch
- **BI and visualisation:** Tableau, Power BI, Excel, Matplotlib, Seaborn
- **Development:** Docker, FastAPI, React, Git
