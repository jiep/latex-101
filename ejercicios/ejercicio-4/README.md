# Ejercicio 3

Crear el documento LaTeX a partir del pdf Ejercicio-4.pdf

Añadir la tabla en el documento.

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

\section{Tabla}
\subsection{Imagen centrada de 7cm de ancho}
% Introducir el código para añadir la imagen.
\section{Figura}
\subsection{Figura con caption \& label}
% Introducir el código para añadir la figura y poder referenciarla
\section{Referenciar figura}
% Introducir la referencia a la figura anterior, te puede ser útil el comando \ref.

\end{document}
```
