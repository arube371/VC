# VC
\documentclass[11pt,a4paper]{article}

%----------------------------------------------------------------------------------------
%	PACKAGES
%----------------------------------------------------------------------------------------
\usepackage[left=0.8in,top=0.8in,right=0.8in,bottom=0.8in]{geometry} 
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage[default]{sourcesanspro} 
\usepackage{xcolor}      
\usepackage{titlesec}    
\usepackage{enumitem}    
\usepackage{parskip}     

%----------------------------------------------------------------------------------------
%	COLORS & STYLES
%----------------------------------------------------------------------------------------
\definecolor{titleblue}{HTML}{00199e} 
\definecolor{subtitleblue}{HTML}{2ec1e0} 
\definecolor{darktext}{HTML}{222222} 

\color{darktext}
\linespread{0.9} 
\setlength{\parskip}{0.1em} 

\titleformat{\section}{\Large\bfseries\color{titleblue}}{}{0em}{} 
\titlespacing*{\section}{0pt}{0.7em}{0.15em}

\newcommand{\blueitem}[1]{\textcolor{subtitleblue}{\textbf{#1}}}

\setlist[itemize]{label=\textbullet, leftmargin=*, noitemsep, topsep=0pt, parsep=0pt}

%----------------------------------------------------------------------------------------
%	DOCUMENT CONTENT
%----------------------------------------------------------------------------------------
\begin{document}

%--- HEADER ---
{\Huge \textbf{\textcolor{titleblue}{KIDEGANONO LAWRENCE}}} \vspace{0.2em}

City, UGANDA \\
Mobile: +256775194689 \\
Email: lawrenceopiobalente@gmail.com \\
GitHub: https://KIDEGANONO LAWRENCE.github.io/portfolio \\
Nationality: UGANDAN

\vspace{0.4em}

%--- PERSONAL PROFILE ---
\section*{Personal Profile}
Motivated Bachelor of Science in Information Technology student at Uganda Christian University with strong skills in Hardware, Printer installatin, and systems administration. Energetic and sporty, bringing discipline, teamwork, and resilience to both academic and professional pursuits. Committed to applying ICT knowledge to practical solutions while growing as a well-rounded leader.

%--- EDUCATION ---
\section*{Education}

\blueitem{2025-UP TO DATE: Bachelors of Science in Information Technology} \\
\textit{UGANDA CHRISTIAN UNIVERSITY, MUKONO} \\
Full academic scholarship \\
\vspace{0.3em}

\blueitem{2023-2024: UGANDA ADVANCED CERTIFICATE OF EDUCATION} \\
\textit{BOSTON HIGH SCHOOL MPALA, ENTEBBE} \\
\vspace{0.3em}

\blueitem{2011-2017: PRIMARY LEAVING EDUCATION} \\
\textit{PAORINHER NURSERY AND PRIMARY SCHOOL, PATONGO T/C AGAGO DISTRICT} \\
\vspace{0.3em}



%--- EXPERIENCE ---
\section*{Experience}

\blueitem{February 2026-April 2026: Recess workshop} \\
\textit{Ankrah Audiotorium}
\begin{itemize}
    \item Benchmarked deployment performance of state-of-the-art foundation models on physical hardware.
    \item Investigated novel techniques for in-context policy adaptation in unstructured environme
\end{itemize}

\vspace{0.3em}

\blueitem{Sept 2023 -- May 2024: Software Engineering Intern} \\
\textit{Tech Company, Location}
\begin{itemize}
    \item Programmed C\# and C++ middleware for automated hardware validation systems.
    \item Optimized legacy GUI modules, resulting in improved system response times during testing.
    \item Collaborated with the systems team to integrate firmware updates for semiconductor equipment.
\end{itemize}

%--- PUBLICATIONS ---
\section*{Academic Publications}

\blueitem{Geometry-Aware VLA Architecture: Infusing 3D Context into Vision-Language-Action Models.} Under review. [arXiv] \\
\textit{\textbf{Your Name}, Co-Author 1, Co-Author 2, Co-Author 3.}

\vspace{0.2em}

\blueitem{Self-Supervised World Modeling for Robotic Skill Acquisition.} Under review. [arXiv] \\
\textit{Co-Author 1, \textbf{Your Name}, Co-Author 2.}

\vspace{0.2em}

\blueitem{Hybrid Neural Networks for Robust Speech Emotion Classification.} International Conference on ML. \\
\textit{\textbf{Your Name}, Co-Author 1, Co-Author 2.}

%--- PROJECTS ---
\section*{Projects/Research}

\blueitem{Autonomous Agricultural Manipulation System | 2025} \\
\textit{University Robotics Lab}
\begin{itemize}
    \item Developed a point-cloud-based pipeline for object identification and harvesting in occluded scenarios.
    \item Implemented collision-aware motion planning, reducing accidental contact with obstacles by over 65\%.
    \item Integrated the system using NVIDIA Isaac Sim and successfully validated on a physical robotic arm.
\end{itemize}

%--- SKILLS ---
\section*{Skills}
Python, C/C++, Linux (Ubuntu), ROS/ROS2, PyTorch, NVIDIA Isaac Sim, MATLAB \\
Languages: English (Fluent), Arabic (Native)

%--- REFERENCES ---
\section*{References}

\begin{minipage}[t]{0.48\textwidth}
    \textbf{Reference Name 1} \\
    Principal Investigator \\
    Department of Robotics \\
    University or Institute Name \\
    Email: reference1@example.com
\end{minipage}%
\hfill
\begin{minipage}[t]{0.48\textwidth}
    \textbf{Reference Name 2} \\
    Senior Research Scientist \\
    Computer Vision Group \\
    University or Institute Name \\
    Email: reference2@example.com
\end{minipage}

\end{document}
