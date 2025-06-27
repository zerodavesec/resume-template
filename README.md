# Resume Template in LaTeX

\documentclass[a4paper,10pt]{article}
\usepackage{geometry}
\usepackage{fontawesome}
\geometry{left=0.5in, right=0.5in, top=0.5in, bottom=0.5in}

\usepackage{titlesec}
\titleformat{\section}{\large\bfseries}{}{0em}{}[\titlerule]
\titleformat{\subsection}{\bfseries}{}{0em}{}

\usepackage{enumitem}
\setlist[itemize]{left=5pt,label={$\bullet$}}

\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    filecolor=magenta,      
    urlcolor=blue,
}

\usepackage{multicol}
\usepackage{parskip}

\begin{document}

\begin{center}
    {\LARGE \bfseries John Doe} \\
    \vspace{2mm}
    \href{mailto:john.doe@example.com}{john.doe@example.com} \quad
    \faLinkedin \ \href{https://www.linkedin.com/in/johndoe}{linkedin.com/in/johndoe} \quad
    \faPhone \ +1-234-567-8901 \quad
    New York, NY
\end{center}

\vspace{3mm}

\section{Professional Summary}

Cybersecurity professional with 5+ years of experience in threat detection, incident response, and security automation. Skilled in endpoint protection, detection engineering, and securing cloud environments. Adept at scripting, infrastructure troubleshooting, and collaborating across teams to enhance security postures.

\vspace{2mm}

\section{Work Experience}

\textbf{Detection Engineer | \textit{CyberSafe Inc.}} \hfill \textbf{Mar 2023 – Present}
\begin{itemize}
    \item Designed and implemented Python-based integrations for threat intelligence and alert enrichment.
    \item Built and maintained detection-as-code pipelines using GitHub Actions and CI/CD workflows.
    \item Created and tested detection rules mapped to the MITRE ATT\&CK framework across various platforms.
    \item Utilized Docker environments to simulate attacks and validate detection logic.
    \item Led initiatives to automate response playbooks, reducing mean time to resolution (MTTR).
\end{itemize}

\vspace{2mm}

\textbf{Endpoint Security Analyst | \textit{SecureTech Solutions}} \hfill \textbf{Jan 2021 – Feb 2023}
\begin{itemize}
    \item Conducted threat research on ransomware and created blocklists to prevent endpoint infections.
    \item Investigated incidents using forensic data, log analysis, and behavioral indicators.
    \item Managed endpoint policy configurations across Linux/macOS/Windows to maintain compliance.
    \item Created custom detection rules and automated remediation scripts in Python.
    \item Served as Linux/macOS SME and authored internal documentation for common incident scenarios.
\end{itemize}

\vspace{2mm}

\textbf{Cloud Security Support Engineer | \textit{NetGuard Technologies}} \hfill \textbf{Aug 2019 – Dec 2020}
\begin{itemize}
    \item Advised clients on secure cloud deployments and container security best practices.
    \item Provided technical support for endpoint protection in virtualized (VMware/AWS) environments.
    \item Conducted root cause analysis of technical security issues and documented resolutions.
    \item Worked closely with security and development teams to ensure secure platform integration.
    \item Used tools like Wireshark and TCPDump for incident diagnostics and network forensics.
\end{itemize}

\vspace{2mm}

\section*{Previous Roles}
\textbf{IT Support Specialist} | \textit{Innovatech Systems} \hfill May 2018 – Jul 2019 \\
\textbf{Technical Support Analyst} | \textit{GlobalHelpdesk Co.} \hfill Jan 2016 – Apr 2018

\vspace{2mm}

\section{Education}
\textbf{B.Sc. in Cybersecurity and Digital Forensics | \textit{University of Techville}} \hfill 2020 – 2022
\begin{itemize}
    \item Coursework: Network Security (A), Malware Analysis (A), Penetration Testing (B+)
    \item Capstone: Investigated rootkits and developed a sandboxed malware analysis tool
\end{itemize}

\vspace{0.5em}
\textbf{A.A.S. in Information Systems | \textit{Tech Community College}} \hfill 2016 – 2018

\vspace{1mm}

\section{Certifications}
\begin{itemize}
    \item Certified Ethical Hacker (CEH) \hfill 2024
    \item CompTIA Security+ \hfill 2023
    \item AWS Certified Security – Specialty \hfill 2023
    \item Cisco Certified Network Associate (CCNA) \hfill 2022
\end{itemize}

\vspace{3mm}

\section{Technical Skills}
Detection Engineering \textbullet{} Threat Intelligence \textbullet{} Incident Response \textbullet{} Automation \textbullet{} Endpoint Security \textbullet{} SIEM \textbullet{} Python \textbullet{} Bash \textbullet{} Linux/macOS \textbullet{} Docker \textbullet{} AWS \textbullet{} MITRE ATT\&CK \textbullet{} Git/GitHub \textbullet{} Network Forensics

\section{Core Competencies}
Security Operations \textbullet{} Troubleshooting \textbullet{} Documentation \textbullet{} Threat Hunting \textbullet{} Collaboration \textbullet{} Root Cause Analysis \textbullet{} Vulnerability Management \textbullet{} Cloud Security \textbullet{} Communication \textbullet{} Process Improvement

\section{Hobbies \& Interests}
\begin{itemize}
    \item \textbf{Homelabbing}: Deploying virtual labs to simulate attacks and test defenses.
    \item \textbf{Open-Source Contribution}: Participating in GitHub security projects and submitting PRs.
    \item \textbf{Tech Blogging}: Writing about cybersecurity tools and best practices.
    \item \textbf{Hiking and Photography}: Enjoying nature and capturing landscapes on weekends.
\end{itemize}

\end{document}
