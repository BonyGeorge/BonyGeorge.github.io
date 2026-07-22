---
layout: default
---

<h1>Abanoub</h1>

<div class="summary">
Computer Science graduate and a current MSc in Artificial Intelligence candidate with a strong foundation in technical support and enterprise infrastructure. Hands-on experience designing end-to-end MLOps pipelines, generative AI solutions (RAG, LangChain), and predictive models. Proven ability to translate complex data into actionable business solutions and maintain 100% customer satisfaction in high-stakes environments.
</div>

## SKILLS & TECHNOLOGIES

*   **Programming & Tools:** Python, Java, C++, JavaScript, Git, Linux, REST APIs
*   **Generative AI:** LLM fundamentals, Prompt Engineering, RAG, LangChain, LangGraph, Vertex AI Studio
*   **Cloud & MLOps:** AWS, Databricks (Vector Indexing, Delta Sharing), GCP, Azure, Virtualization, Airflow, Kubernetes
*   **Machine Learning:** Deep Learning (CNNs, YOLO, ResNet), Model Evaluation, TensorFlow, Keras
*   **Data Science:** Data Manipulation, Tableau, Power BI, Matplotlib, Seaborn

## WORK EXPERIENCE

<div class="clearfix">
    <h3>AI Engineering Intern</h3>
    <span class="date">June 2026 – September 2026</span>
</div>
**Bio-Techne**
*   Slashed questionnaire turnaround time from days to near-real-time by designing an end-to-end AI document processing pipeline for the Customer Care team.
*   Built a scalable batch ingestion system in Databricks, utilizing OCR and hierarchical chunking to parse, embed, and store massive volumes of technical manuals and guides.
*   Deployed a secure online Retrieval-Augmented Generation (RAG) architecture (incorporating PyMuPDF and Llama Guard) to extract and validate questions from customer PDFs.
*   Engineered a hybrid search and dynamic re-ranking engine that evaluated candidate answers against full document context, using confidence thresholds to guarantee high-accuracy output.

<div class="clearfix">
    <h3>Technical Support Engineer</h3>
    <span class="date">May 2022 – January 2025</span>
</div>
**Arrow Electronics** *(via VMware transition)*
*   Resolved critical virtualization escalations across both VMware and Arrow Electronics, consistently maintaining a 100% customer satisfaction score throughout a major corporate acquisition and transition period.
*   Provided expert operation, sustainment, and diagnostic support for complex enterprise virtualization environments.
*   Deployed and managed hands-on labs across various VMware products, including Aria Operations, NSX, and Site Recovery Manager (SRM).
*   Partnered with the University Relations team at VMware to interview and evaluate senior computer science students for incoming internship cohorts.
*   **Certifications:** VCIX-DCV (2023–2024), VCAP-DCV Design (2023), VCP-DCV (2022–2023).

<div class="clearfix">
    <h3>Data Scientist & Business Analyst Intern</h3>
    <span class="date">January 2022 - February 2022</span>
</div>
**The Sparks Foundation**
*   Developed a predictive Linear Regression model using Python (Pandas, Matplotlib) to analyze and forecast student study hours based on historical datasets.

## TECHNICAL PROJECTS

*   **Distributed AI Inference System:** Architected an asynchronous inference system using Airflow, SQS, S3, and Kubernetes.
*   **Medical Imaging Triage:** Designed a high-level system architecture for an automated medical imaging triage and detection platform.
*   **Student GPA Prediction (HSLS:09):** Built an end-to-end ML pipeline predicting student GPA categories leveraging feature selection, dimensionality reduction (LDA), and ensemble models.
*   **Reddit Movie Sentiment Platform:** Engineered the system architecture and backend assumptions for a dynamic sentiment analysis homepage.

## GITHUB PROJECTS

<div class="github-projects">
{% assign pinned_projects = site.github.public_repositories | sort: 'stargazers_count' | reverse | slice: 0, 8 %}
{% for repo in pinned_projects %}
    <article class="repo-card">
        <h3><a href="{{ repo.html_url }}" target="_blank" rel="noreferrer">{{ repo.name }}</a></h3>
        <p>{{ repo.description | default: "No description provided yet." }}</p>
        <p class="repo-meta">{{ repo.language | default: "Code" }}{% if repo.stargazers_count %} · {{ repo.stargazers_count }} stars{% endif %}{% if repo.forks_count %} · {{ repo.forks_count }} forks{% endif %}</p>
    </article>
{% endfor %}
{% if pinned_projects.size == 0 %}
    <p>Public repositories will appear here after your first GitHub Pages build with repository metadata.</p>
{% endif %}
</div>

## EDUCATION

*   **MSc in Artificial Intelligence** - University of St. Thomas (Current)
*   **BSc in Computer Science** - Misr International University (2021)

## CERTIFICATIONS

*   **Cloud & Architecture:** Azure Solutions Architect Expert, AWS Cloud Quest GenAI, Databricks Fundamentals
*   **Data & AI:** Databricks Building Retrieval Agents, Datacamp LLM/LangChain, AWS Machine Learning (Udacity), IBM Data Science Professional
*   **Google Skills Boost:** Multiple badges including Generative AI Fundamentals, Vertex AI Studio, and Responsible AI.

## PUBLICATION

*   **Detection of Wild Oats based on Support Vector Machine Algorithms** - MIUCC Conference for International Mobile Intelligent and Ubiquitous Computing (2021)
*   **Wild Oats Dataset:** Built and published a custom dataset for wild oats detection on Kaggle.

## CURRENTLY LEARNING

*   Advanced Generative AI systems
*   LLM applications
*   MLOps and scalable ML pipelines
*   AI model deployment on cloud platforms

## LANGUAGES

*   **Arabic:** Native
*   **English:** Fluent

## CONNECT

*   **GitHub:** [github.com/{{ site.github_username }}](https://github.com/{{ site.github_username }})
*   **LinkedIn:** [abanoubgeorge](https://www.linkedin.com/in/abanoubgeorge/)
*   **Email:** [{{ site.email }}](mailto:{{ site.email }})