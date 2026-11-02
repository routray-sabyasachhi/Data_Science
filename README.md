# Data Science Learning Roadmap

A structured path from computing foundations to reproducible, responsible data products. Each numbered subject has an index `README.md`; every numbered topic folder contains its own checklist, concepts, exercises, implementation requirement, outcomes, and completion criteria. Existing `title.md` guides, references, and course PDFs remain available as supplementary material.

## Complete roadmap and sequence

1. [Computing and Tools](./01-Computing-and-Tools/README.md) — terminal, Git, environments, notebooks, files.
2. [Python](./02-Python/README.md) — programming foundations followed by NumPy, pandas, and visualization libraries.
3. [Mathematics](./03-Mathematics/README.md) — algebra, linear algebra, calculus, probability, optimization.
4. [Statistics and Probability](./04-Statistics-and-Probability/README.md) — description, inference, study design, Bayesian thinking.
5. [SQL and Databases](./05-SQL-and-Databases/README.md) — relational modeling, querying, analytics, performance.
6. [Data Collection and Engineering](./06-Data-Collection-and-Engineering/README.md) — sourcing, quality, formats, pipelines, governance.
7. [Exploratory Analysis and Visualization](./07-Exploratory-Analysis-and-Visualization/README.md) — question-led exploration, charts, dashboards, reporting.
8. [Machine Learning](./08-Machine-Learning/README.md) — leakage-safe supervised and unsupervised modeling.
9. [Deep Learning and AI](./09-Deep-Learning-and-AI/README.md) — neural networks, vision, NLP, generative AI, reinforcement learning.
10. [Time Series and Experimental Methods](./10-Time-Series-and-Experimental-Methods/README.md) — forecasting, experiments, causal reasoning.
11. [Big Data and Cloud](./11-Big-Data-and-Cloud/README.md) — distributed systems, Spark, containers, cloud.
12. [Deployment and MLOps](./12-Deployment-and-MLOps/README.md) — model packaging, serving, testing, monitoring, governance.
13. [Communication and Product Analytics](./13-Communication-and-Product-Analytics/README.md) — stakeholder questions, metrics, product analysis, decisions.
14. [Responsible Data Science](./14-Responsible-Data-Science/README.md) — privacy, fairness, governance, human oversight.
15. [Projects and Portfolio](./15-Projects-and-Portfolio/README.md) — end-to-end projects and case studies.

## Prerequisite relationships

```text
01 Computing and Tools ──> 02 Python ──> 06 Data Engineering ──> 07 EDA/Visualization
                         ├─> 05 SQL ──────────────────────────┘
                         └─> 03 Mathematics ──> 04 Statistics ──> 08 Machine Learning
                                                              ├─> 09 Deep Learning
                                                              └─> 10 Time Series/Experiments
06 Data Engineering ──> 11 Big Data/Cloud ──> 12 Deployment/MLOps
07 EDA + 13 Communication + 14 Responsible Practice ──> 15 Portfolio
```

This is a dependency guide, not a rigid gate. Start statistics and mathematics early and revisit them while modeling. SQL and visualization can be studied alongside Python. Responsible practice and communication apply throughout, not only at the end.

## Recommended progression

### Core path

Complete subjects 01–08 in order, while studying subject 13 and 14 principles from the beginning. Build small artifacts in each subject. At minimum, become comfortable with Python, SQL, tabular data cleaning, descriptive statistics, visualization, train/test validation, and model evaluation before moving to advanced AI.

### Advanced and role-dependent branches

- **Deep learning / AI:** subject 09 after mathematics and classical ML.
- **Experiments / causal analysis / forecasting:** subject 10 after statistics and regression.
- **Large-scale data engineering:** subject 11 after SQL and subject 06.
- **Production ML:** subject 12 after ML and software quality; cloud topics help but are not always required.
- **Product analytics:** subject 13 can be brought forward for analyst roles.
- **Research track:** deepen proofs, statistical inference, optimization, causal assumptions, and paper reproduction in subjects 03, 04, 08, 09, and 10.

### A repeatable study loop

1. Follow the numbered folders inside each subject index.
2. Read the linked reference list in the root [reference.md](./reference.md); choose one main book per subject and use official docs for tools.
3. Complete the checklist and implementation exercise in each topic README.
4. Track progress in [PROGRESS.md](./PROGRESS.md).
5. Build progressively larger projects; explain data provenance, assumptions, validation, limitations, and decisions.

## Existing materials

- [Subject references: books and websites](./reference.md)
- [Original roadmap notes](./Roadmap.md)
- [Python course materials](./Python/) — existing PDFs preserved.
- Original subject `title.md` files remain in each subject folder as overview notes.
