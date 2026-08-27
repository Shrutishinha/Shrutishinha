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
