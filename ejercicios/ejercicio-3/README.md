# Ejercicio 3

Crear el documento LaTeX a partir del pdf [Ejercicio-3.pdf](https://github.com/next-security-lab/latex-101/blob/master/ejercicios/ejercicio-3/Ejercicio-3.pdf)

**TAREA**: Añadir las imágenes en el documento de la manera indicada.

```latex
\documentclass{article}
\usepackage[utf8]{inputenc}
% Añadir paquetes graphicx & lipsum

\title{Taller \LaTeX{} -- Ejercicio 3}
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
% Introducir el código para añadir la imagen.
\section{Figura}
\subsection{Figura con caption \& label}
% Introducir el código para añadir la figura y poder referenciarla
\section{Referenciar figura}
% Introducir la referencia a la figura anterior, te puede ser útil el comando \ref.

\end{document}
```
