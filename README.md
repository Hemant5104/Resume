    %-------------------------
% Resume in Latex
% Author
% License : MIT
%------------------------

%---- Required Packages and Functions ----

\documentclass[a4paper,11pt]{article}
\usepackage{latexsym}
\usepackage{xcolor}
\usepackage{float}
\usepackage{ragged2e}
\usepackage[empty]{fullpage}
\usepackage{wrapfig}
\usepackage{lipsum}
\usepackage{tabularx}
\usepackage{titlesec}
\usepackage{geometry}
\usepackage{marvosym}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\usepackage{cfr-lm}
\usepackage[T1]{fontenc}
\setlength{\multicolsep}{0pt} 
\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}
\geometry{left=1.4cm, top=0.8cm, right=1.2cm, bottom=1cm}
% Adjust margins
%\addtolength{\oddsidemargin}{-0.5in}
%\addtolength{\evensidemargin}{-0.5in}
%\addtolength{\textwidth}{1in}
\usepackage[most]{tcolorbox}
\tcbset{
	frame code={}
	center title,
	left=0pt,
	right=0pt,
	top=0pt,
	bottom=0pt,
	colback=gray!20,
	colframe=white,
	width=\dimexpr\textwidth\relax,
	enlarge left by=-2mm,
	boxsep=4pt,
	arc=0pt,outer arc=0pt,
}

\urlstyle{same}

\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-7pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item{
    \textbf{#1}{\hspace{0.5mm}#2 \vspace{-0.5mm}}
  }
}

\newcommand{\resumePOR}[3]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1}\hspace{0.3mm}#2 & \textit{\small{#3}} 
    \end{tabular*}
    \vspace{-2mm}
}

\newcommand{\resumeSubheading}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#4}} \\
        \textit{\footnotesize{#3}} &  \footnotesize{#2}\\
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeProject}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#3}} \\
        \footnotesize{\textit{#2}} & \footnotesize{#4}
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}
% \renewcommand{\labelitemii}{$\circ$}
\renewcommand{\labelitemi}{$\vcenter{\hbox{\tiny$\bullet$}}$}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*,labelsep=0mm]}
\newcommand{\resumeHeadingSkillStart}{\begin{itemize}[leftmargin=*,itemsep=1.7mm, rightmargin=2ex]}
\newcommand{\resumeItemListStart}{\begin{justify}\begin{itemize}[leftmargin=3ex, rightmargin=2ex, noitemsep,labelsep=1.2mm,itemsep=0mm]\small}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}\vspace{2mm}}
\newcommand{\resumeHeadingSkillEnd}{\end{itemize}\vspace{-2mm}}
\newcommand{\resumeItemListEnd}{\end{itemize}\end{justify}\vspace{-2mm}}
\newcommand{\cvsection}[1]{%
\vspace{2mm}
\begin{tcolorbox}
    \textbf{\large #1}
\end{tcolorbox}
    \vspace{-4mm}
}
\newcolumntype{L}{>{\raggedright\arraybackslash}X}%
\newcolumntype{R}{>{\raggedleft\arraybackslash}X}%
\newcolumntype{C}{>{\centering\arraybackslash}X}%
%---- End of Packages and Functions ------

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%
%%%%%% DEFINE ELEMENTS HERE %%%%%%%
\newcommand{\name}{Hemant Srivastava} % Your Name
\newcommand{\course}{Computer Science and Engineering} % Your Program
\newcommand{\role}{MERN Stack Developer} % Your Roll No.
\newcommand{\phone}{8546074033} % Your Phone Number
\newcommand{\emaila}{hemantsrivas51@gmail.com} %Email 1

\begin{document}
\fontfamily{cmr}\selectfont
%----------HEADING-----------------

{
\begin{tabularx}{\linewidth}{L r} \\
  \textbf{\Large \name} & {\raisebox{0.0\height}{\footnotesize \faPhone}\ +91-\phone}\\
  { \role } & \href{mailto:\emaila}{\raisebox{0.0\height}{\footnotesize \faEnvelope}\ {\emaila}} \\
  Bachelor of Technology & \href{https://github.com/Hemant5104}{\raisebox{0.0\height}{\footnotesize \faGithub}\ {Hemant5104}} \\  
  {Lovely Professional University, Phagwara} & \href{www.linkedin.com/in/hemantsri/}{\raisebox{0.0\height}{\footnotesize \faLinkedin}\ {Hemant Srivastava}}
\end{tabularx}
}


%-----------EDUCATION-----------
\section{\textbf{Education}}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Bachelor of Technology in Computer Science and Engineering}{CGPA: 7.91}
      {Lovely Professional University, Phagwara}{2023-2027}
  \resumeSubHeadingListEnd
\vspace{-5.5mm}
%
%-----------PROJECTS-----------------
\section{\textbf{Personal Projects}}
\resumeSubHeadingListStart
    \resumeProject
      {PawGuide AI based Chatbot for Pet Care Assistance} %Project Name
      {A website-based Pet Care Assistance ChatBot, implemented using a Gemini API.} %Project Name, Location Name
      {} %Event Dates

      \resumeItemListStart
        \item {Facilitating users' logins to websites without having to remember their credentials}
        \item {Facilitates users' save their pet information, past activities and medical diagnostics. }
        \item {Technology Used: Python, TypeScript, FastAPI.}
    \resumeItemListEnd
    \vspace{-2mm}
    
    \resumeProject
      {Wixvent} %Project Name
      {A PHP based web application that allows users to create and manage their events. } %Project Name, Location Name
      {} %Event Dates

      \resumeItemListStart
        \item {Facilitating users' logins to websites without having to remember their credentials}
        \item {Implemented a secure admin panel in PHP for managing events, user registrations, and database operations }
        \item {Technology Used: JavaScript, PHP, MySQL, XAMPP.}
    \resumeItemListEnd
    \vspace{-2mm}

%     \resumeProject
%       {Job Portal Website} %Project Name
%       {Daily and weekly updated Job Postings.} %Project Name, Location Name
%       {} %Event Dates

%       \resumeItemListStart
%         \item {Developed a full-stack Job Portal Website using HTML, CSS \& Javascript to enable seamless job listings and user management.}
%         \item {Implemented features for job applications, user authentication, and data handling to ensure a smooth and secure experience.}
%         \item {Technology Used : JavaScript , CSS, HTML.
% }
%     \resumeItemListEnd
      
  \resumeSubHeadingListEnd
\vspace{-8.5mm}


%-----------EXPERIENCE-----------------
\section{\textbf{Experience}}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Open Source Contributor}{Online}
      {Jalpaiguri Winter Of Code}{Jan - March 2024}
      
      \resumeItemListStart
    \item {Participated in JWOC '24 as an open-source contributor, working on two web-based projects: Openpedia and Wellness Wave.}
    \item {Improved user interface by redesigning key webpages in Openpedia, a platform offering curated guides for open-source programs.}
    \item {Developed and integrated features in Wellness Wave, including a responsive footer, BMI calculator, and structured health workplan using HTML, CSS, and JavaScript.}
    \item {Collaborated with project maintainers and contributors on GitHub, applying version control and Agile development practices in a real-world environment.}
    \resumeItemListEnd
    
    \vspace{-3.0mm}
    
    \resumeSubheading
      {HeadStarter AI Fellowship}{Online}
      {HeadStarter AI}{July - Sept 2024}
      
      \resumeItemListStart
    \item {Gained practical experience in building AI-driven solutions, working on real-world projects and use cases}
    \item {Collaborated with a cohort of driven peers and industry mentors to explore advanced topics in machine learning and deep learning}
    \resumeItemListEnd
    
    \vspace{-3.0mm}
      
  \resumeSubHeadingListEnd
\vspace{-5.5mm}







%-----------Technical skills-----------------
\section{\textbf{Technical Skills and Interests}}
 \begin{itemize}[leftmargin=0.05in, label={}]
    \small{\item{
     \textbf{Languages}{: Java,PHP,C/C\texttt{++}, Python, Javascript, HTML,CSS } \\
     \textbf{Libraries }{: C++ STL, Python Libraries, ReactJs }\\ 
     \textbf{Web Dev Tools}{: Nodejs, VScode, Git, Github } \\ 
     \textbf{Frameworks}{: ReactJs,Tailwind CSS } \\
     \textbf{Cloud/Databases}{:MongoDb, Azure , Relational Database(MySql) } \\  
     \textbf{Relevent Coursework}{: Data Structures \& Algorithms, Operating Systems, Object Oriented Programming, Database Management System, Software Engineering,Computer Networks,Computer Architecture. } \\ 
     \textbf{Areas of Interest}{: Web Design and Development, Cloud Security,Machine Learning.} \\
     \textbf{Soft Skills}{: Problem Solving, Self-learning, Presentation, Adaptability} \\
    }}
 \end{itemize}
 \vspace{-16pt}



%-----------Positions of Responsibility-----------------
\section{\textbf{Positions of Responsibility/Achievements}}
\vspace{-0.4mm}
\resumeSubHeadingListStart
\resumePOR{Gold Microsoft Student Ambassador } % Position
    {Microsoft Student Ambassador } %Club,Event
    {Aug - Present} %Tenure Period \\
    \resumeItemListStart
    \item {Selected as a Gold Microsoft Student Ambassador, representing the student tech community and promoting Microsoft technologies on campus.}
    % \item {Conducted workshops and events on topics like Azure, GitHub, and web development, fostering peer learning and engagement with ober 300\texttt{+} attendees.}
    \resumeItemListEnd
\resumePOR{Event Manager } % Position
    {Microsoft Achievers' Club } %Club,Event
    {April - Present} %Tenure Period \\
    \resumeItemListStart
    \item {Coordinated workshops, webinars, and hackathons focused on Microsoft technologies, enhancing student engagement and technical learning with over 500\texttt{+} participants.}
    % \item {Collaborated with team members to manage logistics and promotions, ensuring successful and impactful events.}
    \resumeItemListEnd
    \resumePOR{Top 20 in JWOC'24 } % Position
    {Jalpaiguri Winter of Code} %Club,Event
    {} %Tenure Period \\
    \resumeItemListStart
    \item {Ranked among Top 20 participants in JWOC'24 with over 10\texttt{+} accepted pull requests.}
    \resumeItemListEnd
\resumeSubHeadingListEnd
\vspace{-5mm}




% %-----------Achievements-----------------
% \section{\textbf{Achievements}}
% \vspace{-0.4mm}
% \resumeSubHeadingListStart
% \resumePOR{Achievement } % Award
%     {description} % Event
%     {Event dates} %Event Year
    
% \resumePOR{Achievement } % Award
%     {description} % Event
%     {Event dates} %Event Year
% \resumeSubHeadingListEnd
% \vspace{-5mm}



%-------------------------------------------
\end{document}
