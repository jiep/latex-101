# Ejercicio 5

```latex
\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage{lipsum}
\usepackage{graphicx}
\usepackage{booktabs}


\title{Taller LaTeX -- Ejercicio 5}
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
\subsection{Parte 1.2}
\lipsum[5]
\section{Parte 2}
\lipsum[8]

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

\section{Imágenes y figuras}
\section{Imagen centrada}
\subsection{Imagen centrada de 7cm de ancho}
\begin{center}
\includegraphics[width=7cm]{perro.png}
\end{center}
\section{Figura}
\subsection{Figura con caption \& label}
\begin{figure}[htbp!]
\centering \includegraphics[width=3cm]{perro.png}
\caption{Perrito}
\label{fig:perro}
\end{figure}
\section{Referenciar figura}
\lipsum[8]~\ref{fig:perro}

\section{Tablas}
\begin{table}[htbp!]
\centering
\begin{tabular}{@{}llr@{}}
\toprule
\multicolumn{2}{c}{Item} &           \\ \midrule
Animal     & Description & Price (\$) \\ \midrule
Gnat       & per gram    & 13.65     \\
           & each        & 0.01      \\
Gnu        & stuffed     & 92.50     \\
Emu        & stuffed     & 33.33     \\
Armadillo  & frozen      & 8.99      \\ \bottomrule
\end{tabular}
\end{table}

\section{Bibliografía}
La página web de Donald Knuth se puede encontrar en~\cite{knuthwebsite}.
\bibliographystyle{plain}
\bibliography{biblio}
\end{document}
```
