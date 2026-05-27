# Hello, I'm Abhay :sparkles: # TonyStark

I'm a **Data Engineer** and **AI Enthusiast** based in Vancouver.

I build production-grade **CDC pipelines**, **medallion lakehouses**, and **streaming systems** on **Databricks** and **Snowflake**.  

I also create open-source AI tools — from intelligent LLM routers to career intelligence platforms powered by knowledge graphs.

## :memo: My Work
**What I work on**:bug: 

- Warehouse-native ELT — Snowflake, dbt, external stages, storage integrations
- Lakehouse streaming — Delta Lake, Structured Streaming, Change Data Feed, DLT
- Pipeline orchestration — Apache Airflow, Databricks Workflows, DAG design
- Data quality — DLT expectations, validation gates, quarantine patterns
- Dimensional modeling — SCD Type 2, fact/dim schemas, CDC upsert logic

Some cool gifs regarding my areas of interests:
| **Gradient Descent**<br>(Optimization in action — pure Manim elegance) | **Backpropagation**<br>(How neural nets actually learn) |
|-----------------------------------------------------------------------|---------------------------------------------------------|
| <img src="https://i.redd.it/10msjwkgp9o91.gif" height="300" alt="Gradient Descent — 3Blue1Brown / Manim style animation"> | <img src="https://machinelearningknowledge.ai/wp-content/uploads/2019/10/Backpropagation.gif" height="300" alt="Backpropagation animation"> |




### 💻 Deep Dive into my Github Portfolio Projects { https://iamabhaydawar-github-io.vercel.app/ }
### 🚀 Agentic Engineering Projects

| **Project** | **Description** |
|-------------|-----------------|
| **[DevRadar](https://github.com/iamabhaydawar/devradar)** · AI Career Intelligence Platform | AI-powered career intelligence platform for Indian developers. Maps personal tech stacks into a **live knowledge graph**, intelligently matches users to top startups, surfaces relevant hackathons, identifies skill gaps, and delivers personalized learning roadmaps + career chat. Built with **React 18 (Vite)**, **Node.js + Express**, **Groq (primary AI)** + Claude fallback, and **HydraDB** for persistent memory. Features vis-network graph visualization, 4-step onboarding, 3 light themes, and graceful degradation.<br><br>`React` · `Node.js` · `Groq` · `Claude` · `HydraDB` |
| **[Zombie CLI](https://github.com/iamabhaydawar/zombie-cli)** · LLM Routing Engine | Multi-specialist AI routing engine that decomposes queries into subtasks and dispatches each to the best narrow model — **Claude for code**, **DeepSeek R1 for math**, **Perplexity Sonar for research**, **Gemini Flash for summarization**, **GPT-4o for structured output**, **Grok-3 for fact-checking**. Built on **LangGraph** with parallel/sequential execution, automatic fallback routing, and a cross-family **verification loop** with retry.<br><br>`Python` · `LiteLLM` · `Typer` · `Pydantic` |
| **[MnemOS](https://github.com/iamabhaydawar/MnemOS)** · Agentic OS with Persistent Memory | A **visual workflow builder for desktop AI agents** running in a fully containerized virtual desktop. Agents carry memory across sessions via **HydraDB**, recover from failures automatically, and adapt strategy based on past runs. Extends a browser-automation engine with four primitives: **Remember**, **Recall**, **Recover**, and **Plan** nodes — enabling graph-enhanced semantic retrieval and LLM-guided retry logic. Built for the *"Agents Under Pressure"* hackathon.<br><br>`Python` · `FastAPI` · `React` · `Groq` · `HydraDB` · `Playwright` · `Docker` |

### 🛠 Data Engineering Projects

| **Project** | **Description** |
|-------------|-----------------|
| **[UPI Transactions CDC Streaming](https://github.com/iamabhaydawar/UPI_Transactions_CDC_Streaming_Analytics)** · Databricks | Production **Change Data Capture** pipeline using **Delta Lake Change Data Feed**. Handles INSERT/UPDATE/DELETE via a multiplier pattern (`+1`, `-1`, `0`) for idempotent merchant aggregations. Hourly metrics via Delta **MERGE** upserts with `processing_log` monitoring. |
| **[HealthCare DLT Medallion Pipeline](https://github.com/iamabhaydawar/HealthCare_DLT_Medallion_Pipeline)** · Databricks DLT | Patient admission analytics across **Bronze → Silver → Gold** medallion layers on **Delta Live Tables**. Streaming ingestion with **EXPECT** constraints (`pk_not_null`, `required_fields`, `has_diagnosis`) and **ON VIOLATION DROP ROW**. Three gold tables for admission trends, diagnosis prevalence, and demographics. |
| **[Ecomm Event-Driven Pipeline](https://github.com/iamabhaydawar/Ecomm_event_driven_dbx_Pipline)** · Databricks Workflows | Eight-stage pipeline triggered by **file arrival** across 5 source systems. Staging → validation → enrichment → Delta **MERGE**. **SCD Type 2** on customer dimension. Idempotent and re-runnable with automated file archival. |
| **[News Data Analysis](https://github.com/iamabhaydawar/Snowflake_news_data_analysis_project)** · Airflow + Snowflake + GCS | End-to-end pipeline: **NewsAPI → GCS → Snowflake** orchestrated by **Apache Airflow**. Daily DAG with pagination, Parquet landing via storage integration, and schema-inferred raw table feeding `summary_news` and `author_activity` views. |
| **[Snowflake Customer DML Medallion](https://github.com/iamabhaydawar/snowflake_customer_dml_Medallion_architecture)** · Snowflake Medallion Architecture | End-to-end **Bronze → Silver → Gold** medallion architecture on Snowflake with incremental **Change Data Load**, DML upserts, and schema evolution. Optimized for customer analytics using efficient merge operations, data quality checks, and production-grade incremental loading patterns. |
| **[Travel Booking SCD2 Warehouse](https://github.com/iamabhaydawar/Travel_Booking_SCD2_Warehouse_Project)** · Databricks Data Warehouse | Production data engineering pipeline for travel booking analytics implementing **SCD Type 2** to track historical changes in customers, trips, and bookings across **Bronze → Silver → Gold** layers. Includes PyDeequ data quality validation, audit logging, Z-Order optimization, surrogate keys, and parameterized Databricks workflows.<br><br>`PySpark` · `Delta Lake` · `PyDeequ` · `Databricks` |
| **[Car Rental Batch Ingestion](https://github.com/iamabhaydawar/Car_Rental_Batch_ingestion_Snowflake_Project)** · Airflow + Snowflake Pipeline | Cloud-native batch processing pipeline for car rental analytics. Orchestrated by **Apache Airflow** with **Google Cloud Dataproc** and **PySpark** transformations. Implements **SCD Type 2** for customer dimension management and loads into a star-schema data warehouse on Snowflake for BI-ready analytics.<br><br>`Apache Airflow` · `Dataproc` · `PySpark` · `Snowflake` · `GCS` |

