# Alex Toohey

Data Science student at UC Berkeley. I work in machine learning, software engineering, and data infrastructure. From San Francisco.

[alextoohey.dev](https://alextoohey.dev) · [LinkedIn](https://www.linkedin.com/in/alextoohey1/) · [alex\_toohey@berkeley.edu](mailto:alex_toohey@berkeley.edu)

---

## Currently

Data Science Intern at **Visa** in Foster City, building an LLM-based merchant recommendation model fine-tuned on dataset pulled, processed, and transformed from 76+ billion payment transactions.

---

## Work

| | |
|:---|:---|
| **[Visa](https://www.visa.com/)** · Data Science Intern | Recommending merchants to cardholders is a language problem disguised as a payments problem. I extended Llama with 10,000+ new merchant tokens, domain-specific embedding initialization, and LoRA fine-tuning. 84% Recall@10, 88% NDCG@10, 210+ ablation studies, 6x above the strongest heuristic baseline on unseen merchants. Getting it there required a Spark ETL pipeline on Kubernetes that turns raw transactions into training sequences. |
| **[Databricks](https://www.databricks.com/)** · Software Engineer (Contract) | Databricks' Partner Demo Catalog ships 169 enterprise AI/ML partner solutions, and every one used to be verified by hand. I built the testing infrastructure that automates it: 350+ Pytest and Playwright tests covering 12+ resource types, with results streaming to a Delta table after every run. Verification time dropped 94% and the system caught 36+ production issues before partners ever saw them. |
| **[BART](https://www.bart.gov/)** · Software Engineer Intern | BART runs on production codebases that outlive their documentation. I built a fully local code intelligence platform that generates architecture docs and diagrams for 20,000+ line codebases in under two minutes, using Tree-Sitter/AST parsing across 8+ languages and a multi-stage validation pipeline that keeps the LLM grounded. 97.5% summary accuracy. Nothing leaves BART's own machines. |
| **[SubscriptionFlow](https://www.subscriptionflow.com/)** · AI/ML Engineer Intern | A summer in London at a YC (W22) startup. Support and success teams needed answers that lived in SQL they couldn't write, so I built a RAG-powered Text-to-SQL model with VannaAI, GPT-4o, and ChromaDB, trained on 500+ Q&A pairs, 140+ schemas, and 55+ docs. 75% fewer hallucinations, 92% faster retrieval. Also designed a 4-class churn prediction pipeline on AWS SageMaker so retention work could be targeted instead of guessed. |

---

## Projects

**[AskOski](https://askoski.berkeley.edu/)** · [repo](https://github.com/alextoohey/AskOski) · AskOski helps 45,000+ Berkeley students plan their academic paths. I built the ML and data pipeline behind it: Apache Airflow workflows that retrain models automatically from live student-information-system data, BERT-based course modeling, and sub-250ms response times.

**[EquiPath](https://equipath.streamlit.app/)** · [repo](https://github.com/alextoohey/EquiPath) · Most college search tools rank schools by prestige. For a first-generation student or a student-parent, that's the wrong question. EquiPath matches students to schools based on the constraints they actually face: financial aid, transfer rates, campus childcare, first-gen support. Built with scikit-learn and the Claude API. Won first place in the Educational Equity Track at Berkeley's Datathon for Social Good.

---

## Research & Writing

- **[Aurora anomaly detection](https://ssl_anomaly_aurora_research_poster.pdf)** · Space Sciences Laboratory @ UC Berkeley *(Fall 2025)* · Computer vision models for identifying rare auroral structures in nightly sky data.
- **[Sheriff elections & incarceration](https://Stanford_Sheriff_Election_Research_Poster.pdf)** · Stanford Medicine, Epidemiology & Population Health *(Spring 2025)* · Co-engineered the first national county sheriff election dataset, then built inferential models linking sheriff demographics to local incarceration rates.
- **[Diffusion steering via RL](https://github.com/AlexZhai21/DSSDiffusion)** · Data Science Society @ Berkeley *(Spring 2026)* · Using reinforcement learning to steer diffusion models toward legible text in generated images.
- **[The Art of the Underdog](https://sportsanalytics.studentorg.berkeley.edu/articles/art-of-underdog.html)** · Sports Analytics Group at Berkeley · What March Madness Cinderellas have in common, and which traits actually predict upset runs.
- **[The Battle of the Surfaces](https://sportsanalytics.studentorg.berkeley.edu/articles/battle-of-surfaces.html)** · Sports Analytics Group at Berkeley · A lifelong tennis player asks how much of the clay/grass/hard-court folklore holds up in the data.

---

## Teaching & Community

- **Data C8 (Foundations of Data Science)** · Teaching assistant and course developer for Berkeley's intro data science sequence
- **[Data Science Society at Berkeley](https://dssberkeley.com/)** · Project Manager, Technical Consultant, and Teaching Assistant
- **Sports Analytics Group at Berkeley** · Data Journalist, Editor, and Advisor
- **Code for Good** · Software Developer and Recruitment Chair

---

![Alex's GitHub Stats](https://github-readme-stats.vercel.app/api?username=alextoohey&show_icons=true&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=alextoohey&layout=compact&hide_border=true&langs_count=6)


<!--
**alextoohey/alextoohey** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
