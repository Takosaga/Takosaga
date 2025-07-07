# 👨🏻‍💻 Gonzalo Gamez

**`Making data make sense`**

- 🔭 I finished working on my [Master's Thesis](https://github.com/Takosaga/master_thesis)
- 🌱 I finished studying for a [Master of Natural Sciences in Computer Science](https://tsi.lv/study_programmes/double-degree-in-computer-sciencedata-analytics-and-artificial-intelligence/) with a specialisation in Data Analytics and Artificial Intelligence at Transport and Telecommunication Institute
- 💬 Ask me about my teaching experiences
- ⚡ Fun fact: I cycled [200 miles](https://strava.app.link/907coShCZPb) (320 kms) in one day

## 🧰 Languages and Tools

<img align="left" alt="Python" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original-wordmark.svg" />
<img align="left" alt="Jupyter" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" />
<img align="left" alt="scikitlearn" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/scikitlearn/scikitlearn-original.svg" />
<img align="left" alt="mysql" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original-wordmark.svg" />
<img align="left" alt="PowerBI" width="50px" style="padding-right:10px;" src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" />
<img align="left" alt="Git" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain-wordmark.svg" />
<img align="left" alt="Linux" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />

<br />

---


## 💼 Examples of Work
---

### [Evaluating the Consistency of Explainable AI Methods in Hate Speech Detection](https://github.com/Takosaga/master_thesis)

Challenge: LIME and SHAP are XAI methods used to explain AI models that detect hatespeech. Which is better base on conistency metrics?
Results: SHAP provided consitent results compared to LIME, so recommendation is to use SHAP.

Developed research to evaluate the consistency of Explainable Artificial Intelligence (XAI) methods in hate speech detection across multiple social media platforms. This master's thesis project addresses transparency needs in content detection by systematically comparing LIME and SHAP explanation techniques using rigorous quantitative methodologies.

Results demonstrate that SHAP outperforms LIME in explanation stability, achieving perfect or near-perfect scores across all three consistency metrics (Jaccard similarity, Spearman's ρ, and Kendall's τb). While LIME exhibited moderate consistency with scores between 0.65-0.80, SHAP maintained reproducibility with scores of 1.0 across different random seeds.

* Multi-Platform Data Integration: Aggregated and standardized hate speech datasets from Twitter, YouTube, Reddit, and Gab, ensuring diverse representation across different social media contexts and target demographics.
* XAI Implementation: Integrated LIME and SHAP explanation frameworks with CardiffNLP's RoBERTa-based hate speech detection model, developing controlled experimental setups to isolate stochasticity effects on explanation consistency.
* Statistical Evaluation: Applied multiple consistency metrics including Jaccard Similarity, Spearman Correlation, and Kendall Tau-b, demonstrating that SHAP provides significantly more consistent explanations than LIME across prediction scenarios.
* Visualization: Created heatmap visualizations and consistency matrices to represent explanation behavior, supporting both quantitative findings and intuitive understanding of XAI method performance.
* Key Skills: Explainable AI (LIME/SHAP), Statistical Analysis, Data Visualization, Research Methodology, Python

![](https://github.com/Takosaga/master_thesis/blob/main/reports/figures/Results.png)

---

### [Pārtikas cenu salīdzināšanas portāls / Portal for comparing the prices of groceries](https://github.com/Takosaga/groceryprices)

Challenge: Grocery brochures have sales in Latvia, manually comparing between stores is time consuming.
Results: We crated a grocery price comparison that used AI for OCR to be stored in a database, to be served with a React front-end interface and python backend.

Collaborated in the Women in Tech Hackathon 2025 to develop "AkcijuDraugs," a sales grocery price comparison application designed to help consumers make informed purchasing decisions by extracting and analyzing data from various grocery brochures.

* Strategic Workflow Design: Developing a system to effectively divide tasks among our team members, ensuring efficient collaboration.
* OCR Exploration & Database Creation: Investigating and implementing OCR techniques to extract data from grocery brochures, and building a database to store this crucial information.
* Team Collaboration & Management: Working closely with a multidisciplinary team, enhancing my remote and onsite team management skills
* Key Skills: Optical Character Recognition (OCR), Database Design, Solution Architecture, Team Management
  
![](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExZWljenJkajY0MXJkem0yb2I0eGNsZjR1bWEyNHVzMjBxMWhlZXR2NyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/T1OchynFoXc0nSN7O5/giphy.gif)

---

### [Automated Proliferation Assessment (Computer Vision for a Medical Use Case)](https://github.com/Takosaga/EHH-2025)

Challenge: It is time consuming to manually mark positive growth in cells to detech tumors.
Results: We labled and fine-tuned a YOLO model to detect growths in a given area selected in an area of a cell.

Developed during European Healthcare Hackathon 2025 in Prague, the project aims to address the challenges in assessing the Ki-67 protein—a key marker of cell proliferation used to determine tumor grade and aggressiveness.

* Worked in an unfamiliar field of the medical field in a different country
* Collaborated with team members that had skills sets of design and front end developement
* Learned backend skills to serve model to frontend
* Key Skills: Fast API, Rapid prototyping, Computer Vision models

[![Play](https://github.com/Takosaga/EHH-2025/blob/main/play.png)](https://youtu.be/4LtwRDbN2_M)

---

### [Teacher's Helper (Retrieval-Augmented Generation for Teaching Resources)](https://github.com/Takosaga/teachers_helper)

Challenge: There is plentiful resources to be used online and provided by school districts, how can a teacher pick the correct resource to use to teach a specific lesson?
Results: I created a slack chat bot that uses RAG to retrive relavant materials based on questions asked.

Developed during the AI for Connectivity Hackathon, this project addresses the challenge of retrieving high-quality teaching resources, especially in low-resource communities.

* Resolved undocumented API integration via experimentation and community efforts, addressing hardware 
compatibility by adjusting environment variables.
* Used smaller, cost-effective models with hybrid cloud/on-premise setups (including Slack 
integrations) to aid educators in resource-constrained areas.
* Used Docker for rapid prototyping with modular designs to quickly adapt tools and simplify 
outputs for teachers' use.
* Key Skills:  Docker, Ollama, Large Language Models (LLM), Retrieval-Augmented Generation (RAG)

![](https://github.com/Takosaga/teachers_helper/blob/main/bot_example.png)

---

### [Image Recognition to Detect Different Vehicle Types in Riga](https://github.com/Takosaga/ai_group_project)

Challenge: Detecting tracfic is possible but there is a variety of vehicles types in Riga, which types of vehicle types are there in traffic?
Results: We labeled and fine-tuned a YOLO model to detect different types of vehicles in Riga. 

Led a team to develop an AI model for classifying vehicle types in Riga, Latvia, enhancing urban traffic analysis.

* Coordinated project planning, data collection, and model development.
* Managed timelines and ensured effective team communication.
* Oversaw the development of the model for real-time traffic monitoring.
* Key Skills: Project Management, Team Leadership, AI Model Development.

![](https://github.com/Takosaga/ai_group_project/blob/main/reports/figures/results_unlabeled_20241127_122537.jpg)

---

### [Competitive Analysis for UWE Bristol](https://github.com/Takosaga/fall_24/tree/main/bi_and_data_viz)

Challenge: There are Guardian UK univerity ranking released every year, how can UWE improve and who should we target with our results compared versus UWE competitors?
Results: UWE should market towards international students with it's ranking and employability comparison to it competitors.

Developed an interactive dashboard to provide insights into business performance metrics.

* Utilized Power BI to create visualizations for sales and marketing data.
* Implemented data models to support real-time analytics.
* Key Skills: Power BI, Story telling, Data Visualization, Business Intelligence.

![](https://github.com/Takosaga/fall_24/blob/main/bi_and_data_viz/dashboard.png)

---

### [Big Data Analysis in Social Media](https://github.com/Takosaga/fall_24/tree/main/big_data/coursework_assignment)

Challenge: There is data available for TikTok and the influencer management group wishes to expand into YouTube using semi-structured data to see if views correlate with user engagment similar to TikTok.
Results: I created a dashboard that used data from an excel sheet and MangoDB that shows that for both TikTok and YouTube the more views a video has then the more engagment the video gets such as likes, shares, comments, etc.

Analyzed engagement trends across TikTok and YouTube to help influencer management groups optimize strategies.

* Developed a Streamlit dashboard for data visualization.
* Performed ETL operations and correlation analysis.
* Key Skills: Pandas, Data Cleaning, Streamlit.
  
![](https://github.com/Takosaga/fall_24/blob/main/big_data/coursework_assignment/reports/figures/etl.png)

---

### [Detecting Suspicious TikTok Content Creators](https://github.com/Takosaga/fall_24/tree/main/machine_learning_and_predictive_analytics/detecting_suspicious_tiktok_content_creators)

Challenge: There is a dataset with a variety of TikTok content creators and thier properties of thier videos, is it possible to see what shared attributes banned/warned creators have?
Results: The best performing and interpretable model I created was a decision tree, but was did not achieve satisfactory results to be deployed. Possible to use deep learning models and apply XAI to have an interpretable model to have better results.

Developed interpretable machine learning models to identify suspicious users based on behavior patterns.

* Created and optimized Logistic Regression and Decision Tree models.
* Resolved class imbalance with SMOTE and SMOTEENN.
* Key Skills: Model Selection, Model Tuning, Interpretable models.
  
![](https://github.com/Takosaga/fall_24/blob/main/machine_learning_and_predictive_analytics/detecting_suspicious_tiktok_content_creators/reports/figures/decision_tree.png)

---

### [Article Management System Project Planning](https://github.com/Takosaga/spring_24/tree/main/project_management)

Challenge: The company has recieved creating a article management system with the given requirements.
Results: Created a project planning document to develope an article management system. 

Developed a planning docuent to streamline article submissions and reviews for academic journals.

* Designed and implemented workflows using the Scrum framework with two-week sprints.
* Created a product backlog with user stories, story points, and Gantt charts for project planning.
* Applied QA/QC processes, risk management strategies, and cost analysis for project control.
* Key Skills: Agile Project Management, Scope Planning (WBS), Stakeholder Management, Risk Analysis, Quality Control.

![](https://github.com/Takosaga/spring_24/blob/main/project_management/work_breakdown_structure.png)

---

### [Database for Hotel & Transit Data for Walkable US Travel Options](https://github.com/Takosaga/fall_23/tree/main/modern_database_technologies)

Challenge: If you come from outside the US, it is expected for you to get around by vehicle, where in the US is it possible to walk or use transit?
Results: I created a relational database to be used to store related data to be used later with a back end.

Designed a relational database to evaluate walkability and public transit accessibility across US cities.

* Created a normalized schema with ERD and implemented it in SQL Server.
* Supported user queries for walkability scores and transit accessibility metrics.
* Key Skills: SQL, ERD Design, Data Modeling.
  
![](https://github.com/Takosaga/fall_23/blob/main/modern_database_technologies/ERD.png)

---

### [DC Walkability Analysis](https://github.com/Takosaga/us_walkability)

Challenge: We have data about walk, transit, and bike stores, how could we visualize this data?
Results: I used python to visualize walkable places in DC. 

Analyzed walkability metrics across Washington D.C. using Walk Score data to provide insights into urban mobility patterns.

* Developed geospatial visualizations of walkability metrics using interactive maps.
* Used data from [walkscore.com](https://www.walkscore.com/walkable-neighborhoods.shtml) by APIs
* Key Skills: Python, Juptyer Notebooks, Data Analysis, Geospatial Visualization.

![](https://github.com/Takosaga/us_walkability/blob/main/reports/figures/DC%20transitscore.png)



---
