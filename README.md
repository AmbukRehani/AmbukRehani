# Hello, I'm Ambuk Rehani 👋


[![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/AmbukRehani)

![Profile Views](https://komarev.com/ghpvc/?username=AmbukRehani)


## AI Engineer | Backend Engineer | Lifelong Learner

---

### About Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ambuk-rehani/)

🔍 AI Engineer and Backend Engineer with 5+ years of experience building production AI systems, data pipelines, and scalable backend platforms across EdTech, Consulting/CPG, and Industrial Automation. I take AI from proof of concept to production, translating business problems into revenue-critical systems that enterprises trust for high-stakes decisions.

### What I Do
- 🤖 **Agentic AI Systems & RAG Architecture**: Designing and shipping production agentic pipelines with LangGraph orchestration, hybrid retrieval (dense + sparse with reranking), and text-to-SQL over validated templates.
- 📊 **Production LLM Engineering & Evaluation**: Building evaluation frameworks with RAGAS, precision/recall analysis, and hallucination detection so AI systems earn enterprise trust, not just demo well.
- 🛠️ **ETL & Data Platform Engineering**: Building production Databricks ETL with medallion architecture, idempotent incremental loads, and harmonized datasets across heterogeneous sources.
- ☁️ **Backend API Design & Distributed Systems**: Crafting FastAPI/Flask services, event-driven pipelines (Kafka), and cloud-native deployments on AWS, Docker, and Kubernetes.

### Professional Experience

**EAB — AI Engineer (Jul 2024 – Present)**
- Built a production agentic conversational analytics platform enabling 80+ partner universities to query complex enrollment and financial data in natural language, contributing $1M+ in product revenue.
- Architected a LangGraph-based agent that extracts parameters from natural language to populate pre-validated SQL templates with cross-encoder reranking, lifting deterministic query accuracy from ~10% to 95%.
- Designed the RAG pipeline (Pinecone dense + sparse hybrid retrieval) powering AI-driven insights from previously non-queryable regulatory data, saving 2,100+ analyst hours annually.
- Implemented MCP integrations for secure agent access to enterprise tools; the pattern was extended into an Atlassian integration adopted by 200+ engineers internally.

**Nagarro — Software Engineer (Jun 2018 – Jul 2022)**

*Client: Siemens*
- Built the editorial workflow engine for Siemens' mission-critical industrial equipment documentation: a multi-stage review pipeline (owner → technical → commercial reviewer) with RBAC, track changes, and version history, publishing to a catalog portal used by clients like Renault for purchase decisions.
- Scaled the B2B content platform to 5,000+ daily active users on Python, Flask, and AWS; modernized legacy SOAP architecture to REST APIs and improved PostgreSQL read performance by 30%.

*Client: McKinsey (Reckitt Benckiser)*
- Founding data engineer on the engagement: rebuilt 12+ fragile notebook pipelines into production Databricks ETL (Nielsen POS, retailer feeds, APIs, S3 → Parquet) with medallion architecture, cutting pipeline failure rate to under 2%.
- Unified 5 heterogeneous data sources into harmonized Parquet datasets covering 30K+ SKUs at a 98%+ match rate, feeding the ML pricing models and Power BI dashboards behind Reckitt's pricing, promo, and trade decisions.

### My Projects
Here are some of the projects I've worked on:
1. [Migration-Insights-Understanding-U.S.-Immigration-Dynamics](https://github.com/ambuk/Migration-Insights-Understanding-U.S.-Immigration-Dynamics)): -
- Developed an analytical platform to study US immigration trends using AWS S3 Buckets, Apache Airflow and Apache Spark.
- Introduced AWS EMR clusters to compute data-heavy operations capable of handling 100 times the current data.
- Scheduled Airflow DAG daily to frequently update the data on S3 buckets to be further queried for different analytical Purposes
  **Tech Stack** : (AWS) S3 buckets, Apache Airflow, Apache Spark, AWS EMR clusters, AWS IAM, SQL.

2. [SoundScape Analytics Platform](https://github.com/ambuk/SoundScape-Analytics-Platform):
- Designed an analytics platform for audiophiles who plan to buy/sell headphones using an End-to-End ELT pipeline and analytics dashboard by loading audio products data into AWS Services (S3, Redshift, RDS)
- Utilized Terraform to connect multiple AWS Services and automate the pipeline process and implemented Docker to containerize Airflow Server, scheduler and workers.
- Displayed powerful insights such as consumer preferences, market positioning and product development using Metabase dashboard.
  **Tech Stack** : AWS (S3, Redshift, RDS), Airflow, Terraform, Docker, Metabase

3. [Youtube-User-Comments-Semantic-Analysis](https://github.com/ambuk/Youtube-User-Comments-Semantic-Analysis)
- Built machine learning models in Spark to classify if users are cat or dog owners based on 100k comments on Youtube videos.
- Preprocessed data by removing missing values and labeled part of users based on their comments.
- Processed users' comments via RegexTokenizer and Word2Vec in SparkML.
- Trained Logistic Regression and Random Forest models and tuned hyperparameters and selected the best model with 0.85 accuracy based on 5-fold cross-validation.
- Explored topics important to cat and dog owners by plotting WordCloud.
  **Tech Stack** : Apache Spark, Word2Vec, Spark MLlib

4. [University Recommendation System](https://github.com/ambuk/University-Recommendation-System)
- Built a website with JavaScript and Bootstrap to provide top 10 university recommendations as a response to various input parameters from potential students.
- Developed a REST API in Golang and preprocessed Kaggle datasets using Python scripts to set up a visualization framework using Elasticsearch and Kibana.
- Hosted the website on a Kubernetes cluster to ensure fault-tolerance and reliability
 **Tech Stack** : Python, HTML, CSS, Javascript, Go, Elasticsearch, Kibana

5. [2048-game-playing-AI-bot-master](https://github.com/ambuk/2048-game-playing-AI-bot-master)
- Developed an AI bot that could play against and beat a human in a two-player 2048 tile game.
- Utilized adversarial search algorithms, MinMax, Expecti MinMax, Alpha Beta Pruning to develop the bot.
  **Tech Stack** : Python


### Tools & Technologies
- **AI/LLM**: RAG, LangChain/LangGraph, Agentic AI, GPT-4o (Vision), Pinecone, Embeddings & Reranking, Text-to-SQL, RAGAS, MCP
- **Programming**: Python (FastAPI, Flask, Pandas), SQL, Go, JavaScript/TypeScript
- **Data Engineering**: Databricks, Snowflake, dbt, ETL, Parquet, Kafka
- **Databases**: PostgreSQL, MySQL, Vector Databases (Pinecone)
- **Cloud & DevOps**: AWS (EC2, S3, Lambda, EKS), Docker, Kubernetes, Git, CI/CD

### What I'm Looking For
🌱 Open to full-time opportunities in the United States (on-site, hybrid, or remote) in roles such as AI Engineer, Applied AI Engineer, Agentic AI Engineer, Backend Engineer, and Software Engineer.

### Let's Connect

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rehaniambuk@gmail.com)

Looking forward to collaborating on production AI and backend systems!
