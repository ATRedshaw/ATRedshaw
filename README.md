# Hello, I’m Alex 👋

**Data Scientist / Machine Learning Engineer**
Senior Associate at PwC, **Microsoft Certified Azure Data Scientist Associate** and **Microsoft Certified Azure AI Engineer Associate**, building applied ML, AI and analytics products.


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge\&logo=python\&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/sql-4479A1?style=for-the-badge\&logo=postgresql\&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge\&logo=numpy\&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge\&logo=scikit-learn\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge\&logo=PyTorch\&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge\&logo=scipy\&logoColor=white)
![MLflow](https://img.shields.io/badge/mlflow-0194E2.svg?style=for-the-badge\&logo=mlflow\&logoColor=white)
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge\&logo=microsoftazure\&logoColor=white)
![Azure AI](https://img.shields.io/badge/Azure%20AI-0078D4?style=for-the-badge\&logo=microsoftazure\&logoColor=white)
![Docker](https://img.shields.io/badge/docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge\&logo=onnx\&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge\&logo=flask\&logoColor=white)
![Streamlit](https://img.shields.io/badge/streamlit-FF4B4B?style=for-the-badge\&logo=streamlit\&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge\&logo=react\&logoColor=%2361DAFB)
![Power BI](https://img.shields.io/badge/power%20bi-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)

I build data and machine learning systems that turn messy real-world data into models, forecasts, dashboards and products people can actually use. My work spans Python and SQL data pipelines, scikit-learn forecasting, Azure-based LLM/RAG workflows, statistical modelling, optimisation, full-stack analytics apps and user-facing visualisations.

My strongest interests are applied machine learning, probabilistic modelling, sports analytics, AI-assisted workflows, forecasting, optimisation and making technical outputs understandable to non-technical users.

Further write-ups on my work can be found [here](https://atredshaw.com/).

---

## Core expertise

I specialise in applied data science and machine learning engineering, with experience across:

* Building robust Python and SQL data pipelines for complex, real-world datasets.
* Training, evaluating and packaging predictive models using scikit-learn and related tooling.
* Applying LLMs and RAG to document extraction, retrieval and workflow automation problems.
* Developing forecasting, optimisation and simulation models for operational and decision-support use cases.
* Turning modelling outputs into dashboards, web apps and interactive tools.
* Communicating model assumptions, uncertainty and limitations clearly to technical and non-technical stakeholders.

---

## Professional experience

At PwC, I work in Technology Data & Analytics / Cyber & Forensics as a hands-on data and AI practitioner. My work includes:

* Building reusable Python and SQL workflows for high-volume financial-services data reconciliation.
* Developing scikit-learn forecasting models for operational demand, revenue and sales-pipeline planning.
* Contributing to Azure-based RAG/LLM workflows for extracting structured information from unstructured documents.
* Applying NLP and sentiment analysis to survey and free-text datasets.
* Producing dashboards, model walkthroughs, methodology notes and senior stakeholder materials.

I’m particularly interested in the point where data science stops being a notebook and becomes a repeatable, explainable, useful system.

---

## Certifications

* [Microsoft Certified: Azure AI Engineer Associate (AI-102)](https://learn.microsoft.com/api/credentials/share/en-gb/AlexRedshawUK-7850/A925928DDD97389E?sharingId=C183137B04FE9A8C)
* [Microsoft Certified: Azure Data Scientist Associate (DP-100)](https://learn.microsoft.com/api/credentials/share/en-us/AlexRedshawUK-7850/3D296666B7DA157C?sharingId=C183137B04FE9A8C)
* [Microsoft Certified: Azure AI Fundamentals (AI-900)](https://learn.microsoft.com/api/credentials/share/en-gb/AlexRedshawUK-7850/67A0F1144119022E?sharingId=C183137B04FE9A8C)

---

## Selected projects

### xG Plotter / Interactive xG Predictor

A browser-based football Expected Goals model and visualisation tool. The project trains custom xG models from historical shot data, exports scikit-learn pipelines to ONNX, and runs inference directly in the browser through ONNX Runtime Web.

**Highlights**

* Scraped and processed shot-level football data across major European leagues.
* Engineered spatial and contextual features including shot distance, angle, situation and shot type.
* Trained logistic regression model variants and compared probability quality using Brier score and calibration analysis.
* Exported models to ONNX for static, backend-free browser inference.
* Built an interactive frontend for single-shot prediction, heatmaps and match xG plotting.

**Tech:** Python, pandas, NumPy, scikit-learn, SciPy, ONNX, ONNX Runtime Web, JavaScript, HTML Canvas, GitHub Pages

---

### Theme Park Queue Modelling

An end-to-end data science project for forecasting theme park crowd levels from historical queue-time data. It combines browser automation, SQLite persistence, external feature enrichment, model training and an interactive Streamlit dashboard.

**Highlights**

* Scraped historical queue-time charts using Playwright and stored millions of ride observations in SQLite.
* Built a park-level crowd target using percentile-ranked average daily queue times.
* Engineered calendar, holiday, opening-hours, weather and park identity features.
* Trained and tuned a Random Forest regressor using scikit-learn and Bayesian search.
* Built a Streamlit dashboard for future-date predictions, uncertainty bands, feature importance and CSV export.

**Tech:** Python, pandas, scikit-learn, scikit-optimize, Playwright, SQLite, Streamlit, Plotly, Meteostat, Open-Meteo

---

### Predict the Ball

A full-stack Premier League table prediction game with private leagues, live scoring, standings snapshots and an Elo-based season projection model.

**Highlights**

* Built a Flask and React web app with user accounts, email verification, password reset, private leagues and leaderboards.
* Developed a football results pipeline using football-data.co.uk and Fantasy Premier League data.
* Tuned an Elo rating model with walk-forward validation and log-loss.
* Ran Monte Carlo simulations to estimate final table position probabilities.
* Integrated model projections into the backend so forecasts update alongside standings snapshots.
* Deployed with Docker, GitHub Actions and an Oracle VM / Nginx setup.

**Tech:** Python, Flask, SQLAlchemy, Alembic, pandas, NumPy, SciPy, React, Vite, Tailwind CSS, Docker, GitHub Actions, Nginx

---

### Contextual AAC Research Bench

A browser-based research prototype comparing a conventional folder-based AAC interface with a vision-augmented, LLM-generated contextual suggestion feed.

**Highlights**

* Built an experiment interface to compare static vocabulary navigation with image-conditioned AI word suggestions.
* Integrated a multimodal LLM through Groq to generate structured JSON vocabulary suggestions from scene images.
* Logged event-level interaction data, including clicks, typing, tab switches, similarity scores and AI latency.
* Analysed task-level metrics in Python, including WPM, duration, selection ratio and physical interaction cost.
* Early results showed the vision-assisted mode reduced interactions and improved communication rate in the processed sample.

**Tech:** JavaScript, HTML, CSS, Python, pandas, SciPy, Matplotlib, Groq API, multimodal LLMs

---

### FPL Challenge Optimiser

An optimisation engine for Fantasy Premier League Challenge that adjusts expected player points for weekly rule changes and solves constrained squad-selection problems.

**Highlights**

* Modelled weekly FPL Challenge rules as expected-value transformations over player projections.
* Used PuLP to solve integer linear programmes for squad and captain selection.
* Implemented rule modules for multipliers, threshold bonuses, event probabilities and challenge-specific constraints.
* Compared predicted optimal lineups with hindsight-optimal lineups using actual points.
* Built a static frontend to review predicted selections, actual outcomes, optimal lineups, rank progression and match rates.

**Tech:** Python, pandas, NumPy, PuLP, SciPy, YAML, JSON, JavaScript, Chart.js, GitHub Pages

---

## Technical toolkit

**Languages:** Python, SQL, JavaScript, Java
**Data & ML:** pandas, NumPy, scikit-learn, SciPy, PyTorch, MLflow, Matplotlib, Plotly
**AI / LLMs:** Azure AI, Azure OpenAI, RAG, prompt engineering, structured extraction, embeddings, vector search concepts, Groq API
**Optimisation & simulation:** PuLP, integer linear programming, Monte Carlo simulation, Elo models, probabilistic forecasting
**Apps & APIs:** Flask, Streamlit, React, Vite, Tailwind CSS, REST APIs
**Databases & storage:** SQLite, SQL Server, SQLAlchemy, CSV/JSON pipelines
**Cloud & DevOps:** Azure, Docker, GitHub Actions, Nginx, GitHub Pages
**BI & visualisation:** Power BI, Tableau, Matplotlib, Plotly, Chart.js

---

## Current focus

* Strengthening my applied ML engineering portfolio.
* Building more robust forecasting, optimisation and simulation projects.
* Developing Azure AI and RAG workflows following AI-102 certification.
* Improving project documentation, reproducibility, testing and deployment practice.
* Exploring data science applications in sport, accessibility, theme parks and real-world operational planning.

---

## Let’s connect

I’m always happy to talk about data science, machine learning, sports analytics, AI engineering or applied modelling problems.

You can find me on [LinkedIn](https://www.linkedin.com/in/alex-redshaw-a21711323/) or read more about my projects on my [portfolio site](https://atredshaw.com/).
