\documentclass[10pt,a4paper,ragged2e]{altacv}

\includegraphics[width=4.8in, height=0.8in]{DaiictLogo.jpg}
% Change the page layout if you need to
\geometry{left=1.1cm,right=11cm,marginparwidth=8.6cm,marginparsep=1.2cm,top=0.5cm,bottom=1.1cm}

% Change the font if you want to, depending on whether

\ifxetexorluatex
  % If using xelatex or lualatex:
  \setmainfont{Carlito}
\else
  % If using pdflatex:
  \usepackage[utf8]{inputenc}
  \usepackage[T1]{fontenc}
  \usepackage[default]{lato}
\fi


\definecolor{VividPurple}{HTML}{000000}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{2E2E2E}
\colorlet{heading}{VividPurple}
\colorlet{accent}{VividPurple}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}

% Change the bullets for itemize and rating marker
% for \cvskill if you want to
\renewcommand{\itemmarker}{{\small\textbullet}}
\renewcommand{\ratingmarker}{\faCircle}

%% sample.bib contains your publications
\addbibresource{sample.bib}

\begin{document}
\name{YOUR NAME}
\tagline{B.Tech, Information and Communication Technology} %%you can change as per your specialisation and course

\begin{fullwidth}
\makecvheader
\end{fullwidth}

\cvsection[page1sidebar]{Education}

\cvevent{\textbf{Dhirubhai Ambani Institute of Information and Communication Technology (DA-IICT)}}{CPI: }{July 2019 -- Present}{Gandhinagar, Gujarat}

\cvevent{\textbf{Class 12th School} (GHSEB)}{Percentage: \%}{2017 -- 2019}{Gandhinagar, Gujarat}

\cvevent{\textbf{Class 10th School} (GSEB)}{Percentage: \%}{2016 -- 2017}{Gandhinagar, Gujarat}


\cvsection{SKILLS}

\large
\textbf{Area(s) of Interest :} DSA, Android Development, etc.\\
\smallskip \smallskip 
\textbf{Programming Languages :} C, C++, Java, etc. \\
\smallskip \smallskip
\textbf{Tools and Technologies :} tech1, tech2, tools\\
\smallskip \smallskip
\textbf{Technical Electives :} tech1, tech2, tools
\smallskip \smallskip


\cvsection {Positions\\\smallskip of Responsibility }
\cvevent{\Large TITLE }{ 3/4 words title description}{ April 2021 -- Present}{} \smallskip 

\cvevent{\Large TITLE }{ 3/4 words title description}{ April 2021 -- Present}{} \smallskip 

\cvsection{Interests}
\large • Interest 1 \\ \smallskip
• Interest 2 \\ \smallskip
• Interest 3 \\ \smallskip

\clearpage

\end{document}
