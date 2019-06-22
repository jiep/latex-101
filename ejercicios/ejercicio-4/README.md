# Ejercicio 4

Crear el documento LaTeX a partir del pdf [Ejercicio-4.pdf](https://github.com/next-security-lab/latex-101/blob/master/ejercicios/ejercicio-4/Ejercicio-4.pdf).

**TAREA**: Añadir la tabla en el documento.

```latex
\documentclass{article}
\usepackage[utf8]{inputenc}
% Añadir paquete para fórmulas graphicx & lipsum

\title{Taller LaTeX -- Ejercicio 4}
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
% Añadir el código de la tabla del pdf, usar el paquete booktabs.

\end{document}
```
