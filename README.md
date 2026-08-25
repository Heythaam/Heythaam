<h1 align="center">Haithem Hammami</h1>
<h3 align="center">💻 Développeur Full-Stack & MLOps | 🎓 Étudiant Ingénieur à ESPRIT</h3>

<p align="center">
  <a href="mailto:haithem.hammami@esprit.tn"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/heytham-hammami-6a9733248/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

---

Étudiant ingénieur en 3e année à **ESPRIT** (Tunisie), spécialisé en **génie logiciel**, avec une double expertise en développement **Java/Spring Boot** et en **MLOps**. Expérience concrète en conception d'architectures microservices, pipelines CI/CD et déploiement sur Kubernetes. À la recherche d'un **stage de fin d'études**.

🔹 Conception de pipelines MLOps end-to-end (Airflow, MLflow, DVC, FastAPI)  
🔹 Développement d'applications B2B complexes avec Angular & Spring Boot  
🔹 Maîtrise des workflows DevOps (Docker, Jenkins, Kubernetes)

---

## 🛠️ Stack Technique

### Frontend
<p>
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/SCSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
</p>

### Backend
<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white" alt="Spring Security"/>
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white" alt="Hibernate"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
</p>

### Machine Learning & MLOps
<p>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/XGBoost-AA4A44?style=for-the-badge&logo=xgboost&logoColor=white" alt="XGBoost"/>
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLflow"/>
  <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white" alt="Airflow"/>
  <img src="https://img.shields.io/badge/DVC-945DD6?style=for-the-badge&logo=dvc&logoColor=white" alt="DVC"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana"/>
</p>

### DevOps & Outils
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white" alt="SonarQube"/>
</p>

### Base de données
<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
</p>

---

## 💼 Expérience Professionnelle

### 🤖 Stage MLOps — TALYS *(Juil 2026 – Août 2026)*

Pipeline MLOps end-to-end de **détection de fraude bancaire** sur 6,3M de transactions (PaySim).

**✨ Réalisations clés :**
- Comparaison de 5 modèles ML (LogisticRegression, DecisionTree, RandomForest, XGBoost, LightGBM) avec suivi MLflow — **RandomForest retenu** (F1 = 0.88, ROC-AUC = 0.9998)
- Orchestration complète via **Apache Airflow** : quality gate, ingestion, prétraitement, validation, entraînement et monitoring de dérive
- Déploiement via **API REST FastAPI** conteneurisée, avec observabilité temps réel (Prometheus, Grafana, Streamlit)
- Pipeline **CI/CD GitHub Actions** 4 étapes : lint/tests → DAG Airflow → build Docker → déploiement automatique
- Versioning des données avec **DVC**, qualité de code zéro erreur (flake8/pylint 10.00/10)

**🔧 Stack :** Python, scikit-learn, XGBoost, LightGBM, MLflow, DVC, FastAPI, Airflow, Docker, Prometheus, Grafana, GitHub Actions

---

## 🚀 Projets Académiques

### 📚 [JungleInEnglish — Plateforme E-learning](https://github.com/Heythaam)

Plateforme d'apprentissage de l'anglais basée sur une **architecture microservices**.

**✨ Fonctionnalités clés :**
- Architecture microservices Spring Boot & Spring Cloud, sécurisée via **Keycloak (OAuth2)**
- Intégration de **LLM (Gemini)** pour la génération de contenu pédagogique personnalisé
- Pipeline DevOps complet : CI/CD Jenkins, Docker, Kubernetes, SonarQube

**🔧 Technologies :** Spring Boot, Angular, MySQL, Flask, Gemini, Jenkins, Docker, Kubernetes, SonarQube

---

## 📊 Statistiques GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Heythaam&show_icons=true&theme=react&hide_border=true&bg_color=0D1117" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Heythaam&layout=compact&theme=react&hide_border=true&bg_color=0D1117" alt="Top Languages" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=heythaam&theme=react&hide_border=true&background=0D1117" alt="GitHub Streak"/>
</p>

---

## 🌍 Langues

- 🇹🇳 **Arabe** — Langue maternelle
- 🇫🇷 **Français** — Courant (B2)
- 🇬🇧 **Anglais** — Professionnel — TOEIC 810/990 *(Novembre 2025)*

---

## 📫 Contact

<p align="center">
  💼 Ouvert aux opportunités de <strong>stage de fin d'études</strong> et de collaboration sur des projets innovants !
</p>

<p align="center">
  📧 <a href="mailto:haithem.hammami@esprit.tn">haithem.hammami@esprit.tn</a> | 
  💼 <a href="https://www.linkedin.com/in/heytham-hammami-6a9733248/">LinkedIn</a> |
  📱 +216 93 647 848
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=heythaam&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views"/>
</p>

<p align="center">⭐ N'hésitez pas à explorer mes projets et à me contacter pour toute collaboration !</p>
