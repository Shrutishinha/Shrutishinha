\documentclass[9.5pt,letterpaper]{article}
\usepackage[margin=0.42in,top=0.35in,bottom=0.35in]{geometry}
\usepackage{fontspec}
\usepackage{xcolor}
\usepackage{titlesec}
\usepackage{enumitem}
\usepackage{hyperref}
\usepackage{paracol}
\usepackage{tabularx}

\setmainfont{Liberation Sans}

\definecolor{navy}{HTML}{1F4E79}
\definecolor{darkgray}{HTML}{333333}
\definecolor{midgray}{HTML}{555555}

\hypersetup{colorlinks=true, urlcolor=navy, linkcolor=navy}
\pagestyle{empty}

\titleformat{\section}{\normalsize\bfseries\color{navy}}{}{0em}{}[\titlerule]
\titlespacing{\section}{0pt}{3pt}{2pt}

\newcommand{\heading}[2]{%
  \noindent\textbf{#1} \hfill {\footnotesize\color{midgray}#2}\par\vspace{0pt}}

\newcommand{\subheading}[3]{%
  \noindent{\bfseries #1} \hfill {\footnotesize\itshape\color{midgray}#2} ---
  {\footnotesize\itshape\color{midgray}#3}\par}

\setlist[itemize]{leftmargin=12pt, itemsep=0pt, topsep=0pt, parsep=0pt}

\newcommand{\stack}[1]{{\footnotesize\color{midgray}\textit{#1}}\par}

\begin{document}
\setlength{\parindent}{0pt}

% ---------- HEADER ----------
\begin{center}
  {\LARGE\bfseries\color{navy} SHRUTI SINHA}\\[2pt]
  {\footnotesize\color{darkgray} B.Tech CSE Student $\vert$ Data Analytics \& AI $\vert$ Full-Stack Development}\\[2pt]
  {\footnotesize
    New Delhi, India ~ $\vert$ ~ \href{mailto:sinha.shruti1009@gmail.com}{sinha.shruti1009@gmail.com} ~ $\vert$ ~ +91 84479 49424 ~ $\vert$ ~
    \href{https://linkedin.com/in/shruti-sinha-60b112270}{linkedin.com/in/shruti-sinha-60b112270} \\
    \href{https://github.com/Shrutishinha}{github.com/Shrutishinha} ~ $\vert$ ~
    \href{https://shrutishinha.github.io/portfolio}{shrutishinha.github.io/portfolio} ~ $\vert$ ~
    LeetCode: shruti1009 (250+ solved)
  }
\end{center}
\vspace{-10pt}

% ---------- SUMMARY ----------
\section*{Professional Summary}
B.Tech (CSE) student (Dronacharya College of Engineering, expected June 2027) with hands-on experience across data analytics, generative AI, and full-stack development. Delivered audit-dataset cleaning and Power BI reporting as a Data Analyst Intern, and shipped eight end-to-end projects spanning NLP, LLM integration, MERN development, and QA automation. Proficient in Python, SQL, Power BI, and Pandas/NumPy, with 250+ LeetCode problems solved. Seeking a Data Analytics / AI / Full-Stack internship.

% ---------- EDUCATION ----------
\section*{Education}
\heading{B.Tech, Computer Science \& Engineering --- Dronacharya College of Engineering, Gurugram --- CGPA: 8.1/10}{Expected Jun 2027}
\heading{Senior Secondary (XII), PCM --- CBSE --- 78.8\%}{2022}
\heading{Secondary (X) --- CBSE --- 80.8\%}{2020}

% ---------- SKILLS ----------
\section*{Technical Skills}
\begin{itemize}[leftmargin=0pt, itemsep=1pt]
  \item[] \textbf{Languages:} Python, SQL, R, Java, C++, C, HTML, CSS, TypeScript (basic)
  \item[] \textbf{Data \& Analytics:} Power BI (DAX), Tableau, Excel, Pandas, NumPy, MySQL, PostgreSQL, MongoDB Atlas, SQLAlchemy
  \item[] \textbf{AI / ML:} Scikit-learn, NLTK, SpaCy, Gemini API, OpenAI API, Prompt Engineering
  \item[] \textbf{Testing \& Automation:} Selenium, TestNG, Appium, JUnit5, Postman, LambdaTest, KaneAI
  \item[] \textbf{Tools \& Platforms:} Git, GitHub, AWS (EC2, S3, IAM), Streamlit, FastAPI, Jupyter, Linux (CLI), MERN Stack, JWT
\end{itemize}

% ---------- EXPERIENCE ----------
\section*{Experience}
\subheading{Data Analyst Intern --- UMS Certification Pvt. Ltd.}{Jun 2025 -- Aug 2025}{Remote}
\begin{itemize}
  \item Built Pandas + NumPy pipelines for data cleaning, anomaly detection, and EDA on certification and audit datasets.
  \item Designed Power BI dashboards (DAX, KPIs) for management reporting, translating raw data into stakeholder-ready insights.
  \item Automated repetitive validation scripts in Python, cutting manual processing effort significantly.
\end{itemize}

\subheading{Data Analytics Virtual Internship --- Tata Group (Forage)}{Jan 2025 -- Feb 2025}{Virtual}
\begin{itemize}
  \item Performed segmentation, cleaning, and visualization on business datasets, simulating real analyst workflows.
  \item Delivered structured, data-driven recommendations from large-scale industrial data.
\end{itemize}

\subheading{AWS Cloud Micro Internship --- Amazon Web Services (Forage)}{Feb 2025 -- Mar 2025}{Virtual}
\begin{itemize}
  \item Explored cloud infrastructure design (EC2, S3, IAM) and modeled scalable, efficient data workflows.
\end{itemize}

% ---------- PROJECTS ----------
\section*{Projects}

\textbf{HireTrack --- Personal Job Search OS} \hfill {\footnotesize\itshape\color{midgray}MERN $\cdot$ Gemini API $\cdot$ JWT $\cdot$ Adzuna/JSearch}
\begin{itemize}
  \item Full-stack job-tracking platform with drag-and-drop Kanban, AI skill-gap analyzer, resume parser, live job feeds, and offer comparison; evolved prototype into a production MERN app with JWT auth.
\end{itemize}

\textbf{Digital Learning Platform for Rural Schools} \hfill {\footnotesize\itshape\color{midgray}FastAPI $\cdot$ SQLite $\cdot$ SQLAlchemy $\cdot$ Streamlit}
\begin{itemize}
  \item Role-based e-learning platform (student/teacher access) with a low-bandwidth mode; backend built on FastAPI + SQLAlchemy ORM over SQLite for lightweight deployment in low-resource settings.
\end{itemize}

\textbf{NLP Sentiment Analysis Studio} \hfill {\footnotesize\itshape\color{midgray}Streamlit $\cdot$ FastAPI $\cdot$ Scikit-learn $\cdot$ NLTK $\cdot$ SpaCy}
\begin{itemize}
  \item Full-stack 9-page NLP dashboard (exploration, preprocessing, training, batch prediction); trained 5 classifiers on the 50K-review IMDB dataset ($\sim$87\% test accuracy) with real-time + batch inference via Joblib.
\end{itemize}

\textbf{AI Public Health Chatbot} \hfill {\footnotesize\itshape\color{midgray}Streamlit $\cdot$ Gemini \& OpenAI APIs $\cdot$ Scikit-learn $\cdot$ ReportLab}
\begin{itemize}
  \item Integrated Gemini and OpenAI APIs for symptom analysis and health Q\&A alongside a probability-based risk classifier; automated PDF health report generation via ReportLab.
\end{itemize}

\textbf{Additional Projects:} \textit{Resume Analyser} --- ATS keyword-scoring engine simulating recruiter shortlisting (Python, NLP, ML) $\vert$ \textit{Smart Attendance System} --- attendance tracking with ML-based prediction dashboards (Python, SQL, Power BI, Scikit-learn) $\vert$ \textit{Customer Churn Dashboard} --- churn \& retention analytics (Power BI, Python, Pandas, DAX) $\vert$ \textit{Cross-Browser \& Mobile Test Automation Suite} --- parallel test execution across browsers/devices via KaneAI/HyperExecute (Selenium, Java, TestNG, Appium, LambdaTest)

% ---------- CERTIFICATIONS ----------
\section*{Certifications}
Generative AI \& Prompt Engineering --- IBM SkillsBuild $\vert$ Generative AI Certification --- Infosys Springboard $\vert$ Tata Data Analytics Micro Internship --- Tata Group $\vert$ AWS Micro Internship --- Amazon Web Services $\vert$ C Programming --- IIT Bombay $\vert$ R Programming (Basic) $\vert$ Software Testing Fundamentals

% ---------- COMPETITIVE PROGRAMMING ----------
\section*{Competitive Programming}
250+ problems solved on LeetCode (handle: \href{https://leetcode.com/u/shruti1009/}{shruti1009}) across Arrays, Strings, Sliding Window, Greedy, and Dynamic Programming with 85\%+ accuracy.

% ---------- SOFT SKILLS ----------
\section*{Soft Skills}
Analytical Thinking $\vert$ Communication $\vert$ Report Writing $\vert$ Time Management $\vert$ Teamwork $\vert$ Adaptability

\end{document}
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&color=0:0d1117,30:1a0a2e,60:2d1b69,100:7c3aed&height=300&section=header&text=Shruti%20Sinha&fontSize=72&fontColor=e2d9f3&animation=fadeIn&fontAlignY=42&desc=Software%20Developer%20%7C%20Full-Stack%20%7C%20AI/ML%20%7C%20Analytics&descSize=17&descAlignY=62&descColor=a78bfa&stroke=7c3aed&strokeWidth=2"/>

</div>

<p align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3000&pause=1000&color=A855F7&center=true&vCenter=true&width=800&lines=Full-Stack+Developer;MERN+%7C+Java+%7C+Python;Data+Analytics+%7C+Power+BI+%7C+SQL;NLP+%26+LLM-powered+Applications;Automation+Testing+with+Selenium"/>

</p>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=2800&pause=900&color=7C3AED&center=true&vCenter=true&width=750&lines=Building+full-stack+apps+with+MERN+%26+AI+integrations;Data+Analyst+Intern+%40+UMS+Certification+Pvt.+Ltd.;8%2B+end-to-end+projects+across+NLP%2C+LLMs+%26+MERN;250%2B+DSA+problems+on+LeetCode+%E2%80%94+and+counting;442+contributions+%7C+IBM+%7C+AWS+%7C+Tata+%7C+IIT+Bombay+certified)](https://git.io/typing-svg)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

<br/>

## 〔 about me 〕

<img align="right" width="240" src="https://media.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif" style="border-radius:12px; margin-left:20px;"/>

```typescript
const shruti: Developer = {
  name        : "Shruti Sinha",
  location    : "New Delhi, India",
  degree      : "B.Tech CSE @ Dronacharya College, Gurugram (2027)",
  role        : "Software Developer | Data Analyst | AI/ML Enthusiast",
  experience  : "Data Analyst Intern @ UMS Certification Pvt. Ltd.",
  currentWork : "HireTrack — AI-powered job search OS (MERN)",
  shipped     : ["NLP Sentiment Studio", "AI Health Chatbot", "Rural EdTech Platform"],
  cp          : "250+ LeetCode problems | Arrays, DP, Greedy, Sliding Window",
  interests   : ["Full-Stack Dev", "NLP & LLMs", "Test Automation", "Data Analytics"],
  learning    : ["Docker & CI/CD", "Advanced Selenium", "Cloud (AWS)"],
  mantra      : "ship clean code, stay curious, keep building."
}
```

**What I'm up to:**
- 🚀 Building **HireTrack** — full-stack MERN job tracker with Gemini AI, Kanban pipeline & real-time job feeds
- 🧠 Shipped **NLP Sentiment Analysis Studio** — 9-page Streamlit + FastAPI dashboard, 5 ML classifiers on 50K IMDB reviews (~87% accuracy)
- 🩺 Built an **AI Public Health Chatbot** — Gemini + OpenAI powered symptom analysis with automated PDF health reports
- 🏫 Built a **Digital Learning Platform for Rural Schools** — FastAPI + SQLAlchemy backend with a low-bandwidth mode for constrained connectivity
- 📊 Ex-**Data Analyst Intern @ UMS Certification** — Python pipelines, Power BI dashboards, data integrity systems
- 🎯 Grinding **LeetCode** — 250+ problems across Arrays, DP, Greedy & Sliding Window (85%+ accuracy)
- 🏅 Certified by **IBM**, **AWS**, **Tata Group**, **Infosys Springboard** & **IIT Bombay**

<br clear="right"/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 〔 experience 〕

<table width="100%">
<tr>
<td width="6%" align="center">📌</td>
<td width="94%">

### Data Analyst Intern — [UMS Certification Pvt. Ltd.](https://www.umscertification.com)
**`Jun 2025 – Aug 2025`** &nbsp;|&nbsp; New Delhi, India

- 🔹 Processed & analyzed large certification datasets using **Python (Pandas)** and **Power BI**
- 🔹 Built **automated reporting pipelines** that significantly reduced manual effort across teams
- 🔹 Designed **data integrity checks** to flag anomalies before downstream reporting — improved accuracy & reliability
- 🔹 Delivered insights via interactive Power BI dashboards for business decision-making

`Python` `Pandas` `Power BI` `Data Pipelines` `DAX` `Excel`

</td>
</tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 〔 education 〕

<div align="center">

| 🎓 Degree | 🏫 Institution | 📅 Year |
|:----------|:--------------|:--------|
| **B.Tech — Computer Science & Engineering** | Dronacharya College of Engineering, Gurugram | 2023 – 2027 |
| **CBSE Senior Secondary (PCM)** | — | Mar 2022 |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 〔 certifications & achievements 〕

<div align="center">

| 🏅 Certificate | 🏢 Issuer | 🔖 Type |
|:--------------|:---------|:--------|
| **Generative AI & Prompt Engineering** | IBM SkillsBuild | AI / ML |
| **Generative AI Certification** | Infosys Springboard | AI / ML |
| **AWS Micro Internship** | Amazon Web Services | Cloud |
| **Tata Data Analytics Virtual Internship** | Tata Group | Analytics |
| **C Programming Training** | IIT Bombay | Core CS |
| **Software Testing Fundamentals** | — | QA / Testing |

</div>

<br/>

<div align="center">

```
🏆  250+ DSA problems solved on LeetCode
    Arrays · Strings · Sliding Window · Greedy · Dynamic Programming
    85%+ accuracy across all problem categories

🚀  8+ full-stack, AI/ML & automation projects shipped end-to-end
```

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 〔 tech stack 〕

<div align="center">

**⬡ Full-Stack Development**

![MongoDB](https://img.shields.io/badge/MongoDB-1a0a2e?style=flat-square&logo=mongodb&logoColor=a78bfa)
![Express](https://img.shields.io/badge/Express.js-1a0a2e?style=flat-square&logo=express&logoColor=a78bfa)
![React](https://img.shields.io/badge/React-1a0a2e?style=flat-square&logo=react&logoColor=a78bfa)
![Node.js](https://img.shields.io/badge/Node.js-1a0a2e?style=flat-square&logo=nodedotjs&logoColor=a78bfa)
![FastAPI](https://img.shields.io/badge/FastAPI-1a0a2e?style=flat-square&logo=fastapi&logoColor=a78bfa)
![Vite](https://img.shields.io/badge/Vite-1a0a2e?style=flat-square&logo=vite&logoColor=a78bfa)
![Tailwind](https://img.shields.io/badge/Tailwind-1a0a2e?style=flat-square&logo=tailwindcss&logoColor=a78bfa)
![JWT](https://img.shields.io/badge/JWT-1a0a2e?style=flat-square&logo=jsonwebtokens&logoColor=a78bfa)
![Axios](https://img.shields.io/badge/Axios-1a0a2e?style=flat-square&logo=axios&logoColor=a78bfa)

**⬡ Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-2d1b69?style=flat-square&logo=javascript&logoColor=e2d9f3)
![Java](https://img.shields.io/badge/Java-2d1b69?style=flat-square&logo=openjdk&logoColor=e2d9f3)
![Python](https://img.shields.io/badge/Python-2d1b69?style=flat-square&logo=python&logoColor=e2d9f3)
![C++](https://img.shields.io/badge/C++-2d1b69?style=flat-square&logo=cplusplus&logoColor=e2d9f3)
![SQL](https://img.shields.io/badge/SQL-2d1b69?style=flat-square&logo=mysql&logoColor=e2d9f3)
![TypeScript](https://img.shields.io/badge/TypeScript-2d1b69?style=flat-square&logo=typescript&logoColor=e2d9f3)
![HTML5](https://img.shields.io/badge/HTML5-2d1b69?style=flat-square&logo=html5&logoColor=e2d9f3)
![CSS3](https://img.shields.io/badge/CSS3-2d1b69?style=flat-square&logo=css3&logoColor=e2d9f3)

**⬡ AI / ML & NLP**

![Scikit-learn](https://img.shields.io/badge/scikit--learn-1a0a2e?style=flat-square&logo=scikitlearn&logoColor=a78bfa)
![NLTK](https://img.shields.io/badge/NLTK-1a0a2e?style=flat-square&logoColor=a78bfa)
![spaCy](https://img.shields.io/badge/spaCy-1a0a2e?style=flat-square&logo=spacy&logoColor=a78bfa)
![Gemini API](https://img.shields.io/badge/Gemini%20API-1a0a2e?style=flat-square&logo=google&logoColor=a78bfa)
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-1a0a2e?style=flat-square&logo=openai&logoColor=a78bfa)
![Streamlit](https://img.shields.io/badge/Streamlit-1a0a2e?style=flat-square&logo=streamlit&logoColor=a78bfa)

**⬡ Testing & Automation**

![Selenium](https://img.shields.io/badge/Selenium-1a0a2e?style=flat-square&logo=selenium&logoColor=a78bfa)
![TestNG](https://img.shields.io/badge/TestNG-1a0a2e?style=flat-square&logoColor=a78bfa)
![Appium](https://img.shields.io/badge/Appium-1a0a2e?style=flat-square&logoColor=a78bfa)
![Postman](https://img.shields.io/badge/Postman-1a0a2e?style=flat-square&logo=postman&logoColor=a78bfa)
![JUnit5](https://img.shields.io/badge/JUnit5-1a0a2e?style=flat-square&logo=junit5&logoColor=a78bfa)
![LambdaTest](https://img.shields.io/badge/LambdaTest-1a0a2e?style=flat-square&logoColor=a78bfa)

**⬡ Data & Analytics**

![Power BI](https://img.shields.io/badge/Power%20BI-2d1b69?style=flat-square&logo=powerbi&logoColor=e2d9f3)
![Tableau](https://img.shields.io/badge/Tableau-2d1b69?style=flat-square&logo=tableau&logoColor=e2d9f3)
![Pandas](https://img.shields.io/badge/Pandas-2d1b69?style=flat-square&logo=pandas&logoColor=e2d9f3)
![NumPy](https://img.shields.io/badge/NumPy-2d1b69?style=flat-square&logo=numpy&logoColor=e2d9f3)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-2d1b69?style=flat-square&logo=postgresql&logoColor=e2d9f3)
![Excel](https://img.shields.io/badge/Excel-2d1b69?style=flat-square&logo=microsoftexcel&logoColor=e2d9f3)

**⬡ Tools & Platforms**

![Git](https://img.shields.io/badge/Git-1a0a2e?style=flat-square&logo=git&logoColor=a78bfa)
![GitHub](https://img.shields.io/badge/GitHub-1a0a2e?style=flat-square&logo=github&logoColor=a78bfa)
![VS Code](https://img.shields.io/badge/VS%20Code-1a0a2e?style=flat-square&logo=visualstudiocode&logoColor=a78bfa)
![IntelliJ](https://img.shields.io/badge/IntelliJ-1a0a2e?style=flat-square&logo=intellijidea&logoColor=a78bfa)
![Linux](https://img.shields.io/badge/Linux%20CLI-1a0a2e?style=flat-square&logo=linux&logoColor=a78bfa)
![AWS](https://img.shields.io/badge/AWS-1a0a2e?style=flat-square&logo=amazonaws&logoColor=a78bfa)
![MongoDB Atlas](https://img.shields.io/badge/Atlas-1a0a2e?style=flat-square&logo=mongodb&logoColor=a78bfa)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-1a0a2e?style=flat-square&logoColor=a78bfa)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 〔 featured projects 〕

<div align="center">

<table>
<tr>
<td width="50%" valign="top">

### 🚀 [HireTrack](https://github.com/Shrutishinha/HireTrack)
> **Your Personal Job Search OS**

Full-stack MERN app with AI-powered skill gap analysis, Kanban pipeline, real-time job listings via Adzuna/JSearch APIs, Gemini AI integration, JWT auth & scalable MongoDB Atlas schemas.

`MongoDB` `Express` `React` `Node.js` `Gemini API` `JWT` `Tailwind` `Vite` `Axios`

</td>
<td width="50%" valign="top">

### 🧠 NLP Sentiment Analysis Studio
> **9-Page NLP Dashboard**

Full-stack dashboard covering data exploration, preprocessing, training & batch prediction. Trained 5 classifiers on the 50K-review IMDB dataset (~87% test accuracy) with real-time + batch inference via Joblib.

`Streamlit` `FastAPI` `Scikit-learn` `NLTK` `SpaCy` `Plotly`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🩺 AI Public Health Chatbot
> **Gemini + OpenAI Symptom Assistant**

Integrated Gemini and OpenAI APIs for symptom analysis and health Q&A alongside a probability-based risk classifier. Automated PDF health report generation via ReportLab.

`Streamlit` `Gemini API` `OpenAI API` `Scikit-learn` `ReportLab`

</td>
<td width="50%" valign="top">

### 🏫 Digital Learning Platform for Rural Schools
> **Role-Based EdTech Platform**

Role-based e-learning platform with separate student/teacher access and a low-bandwidth mode for constrained connectivity. Backend built on FastAPI + SQLAlchemy ORM over SQLite.

`FastAPI` `SQLite` `SQLAlchemy` `Streamlit`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 [Customer Churn Dashboard](https://github.com/Shrutishinha/Risk-Analysis-PowerBI-Dashboard)
> **Power BI + Python Analytics**

Interactive analytics dashboard to visualize churn patterns & retention metrics. Python used for preprocessing before Power BI ingestion.

`Power BI` `Python` `Pandas` `DAX` `Data Modelling`

</td>
<td width="50%" valign="top">

### 🤖 [Resume Analyser](https://github.com/Shrutishinha/Resume-Analyser)
> **ATS Keyword Scoring Engine**

Keyword-matching scoring system simulating recruiter shortlisting logic — outputs pass/fail reports with match % breakdowns.

`Python` `NLP` `ML` `HTML`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧪 [LambdaTest Search Automation](https://github.com/Shrutishinha/lambdatest-search-test)
> **Cross-Browser Test Suite**

Automated product search testing using KaneAI & HyperExecute on LambdaTest with parallel execution across browsers.

`Selenium` `Java` `TestNG` `LambdaTest` `Maven`

</td>
<td width="50%" valign="top">

### 📱 [Mobile Test Cases](https://github.com/Shrutishinha/lamda_mobile_testcases)
> **App Automation Framework**

Mobile automation tests generated using KaneAI — covering functional flows on the LambdaTest mobile grid.

`Appium` `Java` `KaneAI` `Mobile Testing`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📅 [Smart Attendance System](https://github.com/Shrutishinha/smart-attendance-system)
> **Analytics-Powered Tracking**

Attendance tracking with integrated analytics dashboards and ML-based prediction capabilities.

`Python` `SQL` `Power BI` `scikit-learn`

</td>
<td width="50%" valign="top">

</td>
</tr>
</table>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 〔 competitive programming 〕

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-250%2B%20Problems-7c3aed?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/shruti10/)

```
📌 Topics Mastered
  Arrays & Strings          ██████████  ✅
  Sliding Window            █████████░  ✅
  Greedy Algorithms         ████████░░  ✅
  Dynamic Programming       ███████░░░  🔄
  Trees & Graphs            ██████░░░░  🔄

🎯 Overall Accuracy: 85%+
```

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 〔 github stats 〕

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=Shrutishinha&color=7c3aed&style=flat-square&label=profile+views)
&nbsp;
![Followers](https://img.shields.io/github/followers/Shrutishinha?style=flat-square&color=7c3aed&labelColor=2d1b69&label=followers)
&nbsp;
![Contributions](https://img.shields.io/badge/contributions%20last%20year-442-7c3aed?style=flat-square)
&nbsp;
![GitHub Since](https://img.shields.io/badge/github%20since-2023-7c3aed?style=flat-square)
&nbsp;
![LeetCode](https://img.shields.io/badge/LeetCode-250%2B%20solved-7c3aed?style=flat-square&logo=leetcode&logoColor=white)

<br/><br/>

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Shrutishinha&show_icons=true&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=e2d9f3&icon_color=7c3aed&border_radius=12&count_private=true&include_all_commits=true"/>
&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shrutishinha&layout=compact&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=e2d9f3&border_radius=12&langs_count=7"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Shrutishinha&hide_border=true&background=0d1117&ring=7c3aed&fire=a78bfa&currStreakLabel=e2d9f3&sideLabels=a78bfa&currStreakNum=a78bfa&sideNums=e2d9f3&dates=7c3aed&border_radius=12"/>

</div>

---

## 〔 contribution graph 〕

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Shrutishinha&bg_color=0d1117&color=a78bfa&line=7c3aed&point=e2d9f3&area=true&area_color=2d1b69&hide_border=true&radius=6&custom_title=Contribution%20Activity"/>

</div>

---

## 〔 currently leveling up 〕

```
MERN Stack & Full-Stack     ██████████░   90%
NLP & LLM Integration       █████████░░   85%
Selenium & Test Automation  █████████░░   85%
Power BI & Data Analytics   ████████░░░   75%
DSA & Competitive Prog.     ████████░░░   75%
Docker & DevOps             █████░░░░░░   45%
Cloud (AWS Fundamentals)    ████░░░░░░░   40%
```

---

## 〔 soft skills 〕

<div align="center">

`🧩 Problem Solving` &nbsp; `📐 Analytical Thinking` &nbsp; `🔍 Attention to Detail` &nbsp; `🗣️ Communication` &nbsp; `🤝 Teamwork & Adaptability` &nbsp; `⏱️ Time Management`

</div>

---

## 〔 connect with me 〕

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Shruti%20Sinha-7c3aed?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shruti-sinha-60b112270)
&nbsp;
[![Email](https://img.shields.io/badge/Email-sinha.shruti1009%40gmail.com-7c3aed?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sinha.shruti1009@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-Shrutishinha-7c3aed?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shrutishinha)
&nbsp;
[![LeetCode](https://img.shields.io/badge/LeetCode-shruti10-7c3aed?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/shruti10/)

<br/>

![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:2d1b69,100:0d1117&height=130&section=footer&animation=twinkling&fontColor=a78bfa"/>

</div>
