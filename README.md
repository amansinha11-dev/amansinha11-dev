%-------------------------
% Resume in LaTeX
% Author : Aman Sinha
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{document}

%----------HEADING----------
\begin{center}
    {\Huge \scshape Aman Sinha} \\ \vspace{1pt}
    \small \raisebox{-0.1\height}\faPhone\ +91-XXXXXXXXXX ~ 
    \href{mailto:amansinha@example.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{amansinha@example.com}} ~ 
    \href{https://linkedin.com/in/amansinha}{\raisebox{-0.2\height}\faLinkedin\ \underline{linkedin.com/in/amansinha}}  ~
    \href{https://github.com/amansinha}{\raisebox{-0.2\height}\faGithub\ \underline{github.com/amansinha}}
    \vspace{-8pt}
\end{center}

%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Your University Name}{City, State}
      {Bachelor of Technology in Computer Science}{2022 -- 2026}
    \resumeSubheading
      {Your Higher Secondary School}{City, State}
      {Class XII (CBSE/ISC) -- Percentage/CGPA}{2020 -- 2022}
  \resumeSubHeadingListEnd

%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {CodeAlpha}{Feb 2026 -- May 2026}
      {Machine Learning Intern}{Remote}
      \resumeItemListStart
        \resumeItem{Selected as a \textbf{Machine Learning Intern} at CodeAlpha for the duration \textbf{5th February 2026 to 25th May 2026}, working on real-world AI/ML projects with mentorship and structured task evaluation.}
        \resumeItem{\textbf{Task 1 — Emotion Recognition from Speech:} Designed and developed a deep learning system to recognize human emotions (e.g., \textit{happy, angry, sad, neutral}) from speech audio using speech signal processing techniques.}
        \resumeItem{Extracted acoustic features such as \textbf{MFCCs (Mel-Frequency Cepstral Coefficients)}, Chroma, and Mel-Spectrograms using \texttt{Librosa} for robust feature representation.}
        \resumeItem{Implemented and benchmarked deep learning architectures including \textbf{CNN, RNN, and LSTM} models in TensorFlow/Keras, achieving competitive accuracy across multiple emotion classes.}
        \resumeItem{Trained and validated models on benchmark datasets — \textbf{RAVDESS, TESS, and EMO-DB} — using train/validation/test splits with data augmentation for improved generalization.}
        \resumeItem{\textbf{Task 2 — Emotion Recognition from Speech (Advanced):} Extended the baseline system with hybrid \textbf{CNN-LSTM} pipelines, hyperparameter tuning, and confusion matrix analysis to enhance classification performance.}
        \resumeItem{Deployed an end-to-end pipeline with audio preprocessing, real-time inference, and visualization of predicted emotion probabilities.}
      \resumeItemListEnd

  \resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{Speech Emotion Recognition System} $|$ \emph{Python, TensorFlow, Keras, Librosa, NumPy}}{}
          \resumeItemListStart
            \resumeItem{Built a deep learning model to classify emotions from raw audio using MFCC features and an LSTM-based architecture.}
            \resumeItem{Achieved high classification accuracy on the RAVDESS and TESS datasets with custom preprocessing and augmentation.}
            \resumeItem{Implemented a Streamlit-based UI for uploading audio files and visualizing predicted emotions in real time.}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Project 2 Title} $|$ \emph{Tech Stack: Python, Flask, MongoDB}}{}
          \resumeItemListStart
            \resumeItem{Brief description of the project — replace with your actual project details.}
            \resumeItem{Highlight key features, impact, and technologies used.}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Project 3 Title} $|$ \emph{Tech Stack: React, Node.js, Express}}{}
          \resumeItemListStart
            \resumeItem{Brief description of the project — replace with your actual project details.}
            \resumeItem{Highlight measurable outcomes (e.g., users, performance improvements).}
          \resumeItemListEnd
    \resumeSubHeadingListEnd

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: Python, C/C++, Java, SQL, JavaScript, HTML/CSS} \\
     \textbf{Libraries/Frameworks}{: TensorFlow, Keras, PyTorch, Scikit-learn, Librosa, NumPy, Pandas, Matplotlib, OpenCV} \\
     \textbf{Developer Tools}{: Git, GitHub, VS Code, Jupyter Notebook, Google Colab, Docker} \\
     \textbf{Domains}{: Machine Learning, Deep Learning, Speech Signal Processing, Data Analysis, NLP} \\
     \textbf{Databases}{: MySQL, MongoDB, PostgreSQL}
    }}
 \end{itemize}

%-----------CERTIFICATIONS-----------
\section{Certifications \& Achievements}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Machine Learning Internship} -- CodeAlpha (Feb 2026 -- May 2026) \\
     \textbf{Add other certifications}: e.g., Coursera ML by Andrew Ng, AWS, Google Cloud, etc. \\
     \textbf{Achievements}: Hackathon wins, coding competition ranks, scholarships, etc.
    }}
 \end{itemize}

%-------------------------------------------
\end{document}
