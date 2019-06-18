# Ejercicio 3

Añadir las imágenes en el documento de la manera indicada.

```latex
\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage{lipsum}
\usepackage{graphicx}

\title{Taller LaTeX -- Ejercicio 3}
\author{Tu nombre}
\date{26 de junio de 2019}

\begin{document}

\maketitle

% Añadir código necesario para crear un índice.
\tableofcontents
\newpage

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

\end{document}
```
