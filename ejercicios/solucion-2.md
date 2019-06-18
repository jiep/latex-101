# Ejercicio 2

Tratar de crear las siguientes formulas en el documento proporcionado:

```latex
\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage{lipsum}
\usepackage{amsmath}

\title{Taller LaTeX -- Ejercicio 2}
\author{Tu nombre}
\date{26 de junio de 2019}

\begin{document}

\maketitle

\tableofcontents
\newpage

\section{Introduction}
\lipsum[10]
\section{Parte 1}
\lipsum[1]
\subsection{Parte 1.1}
\lipsum[2]
\subsubsection{Parte 1.1.1}
\lipsum[3]

\section{Modo matemático}
\subsection{Fórmula 1}
$$ E = m c^2 $$
\subsection{Fórmula 2}
$$ F = \dfrac{m_1 \cdot m_2}{r^2} $$
\subsection{Fórmula 3}
 $$ \hat f(\zeta) = \int_{-\infty}^{+\infty} f(x) \ e^{2\pi i x \zeta} \mathrm{dx} $$
\end{document}
```
