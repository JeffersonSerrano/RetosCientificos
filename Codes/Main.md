\documentclass[spanish,notitlepage,letterpaper,11pt]{article} % para artÌculo en castellano



\usepackage[utf8]{inputenc} % Acepta caracteres en castellano
\usepackage[T1]{fontenc} % font encoding
\usepackage[spanish]{babel} % silabea palabras castellanas
\usepackage[none]{hyphenat} 
\usepackage{amsmath}
\usepackage{amsfonts}
\usepackage{amssymb}
\usepackage[colorlinks=true,urlcolor=blue,linkcolor=blue]{hyperref} % navega por el doc
\usepackage{graphicx}
\usepackage{geometry} % See geometry.pdf to learn the layout options.
\geometry{letterpaper}  % ... or a4paper or a5paper or ... 
%\geometry{landscape}  % Activate for for rotated page geometry
%\usepackage[parfill]{parskip} % Activate to begin paragraphs with an empty line rather than an indent
\usepackage{epstopdf}
\usepackage{fancyhdr} % encabezados y pies de pg
\usepackage{lineno}
%\linenumbers

\pagestyle{fancy} 
\chead{\bfseries Hidro Cañon} 
\lhead{} % si se omite coloca el nombre de la seccion
\rhead{fecha del doc} 
\lfoot{\it Damian, Jefferson y Stiven} 
\cfoot{Universidad Industrial de Santander} 
\rfoot{\thepage} 

\voffset = -0.25in 
\textheight = 8.0in 
\textwidth = 6.5in
\oddsidemargin = 0.in
\headheight = 20pt 
\headwidth = 6.5in
\renewcommand{\headrulewidth}{0.5pt}
\renewcommand{\footrulewidth}{0,5pt}
\DeclareGraphicsRule{.tif}{png}{.png}{`convert #1 `dirname #1`/`basename #1 .tif`.png}

\begin{document}
\title{Informe final: Hidro Cañon}
\author{\textbf{Damian Steven Ospina \thanks{email:\texttt{damian2201296@correo.uis.edu.co  } }}\\
\textbf{Jefferson Serrano Duran \thanks{email:\texttt{jefferson22007956@correo.uis.edu.co} }}\\
\textbf{Stiven Contreras \thanks{email:\texttt{stiven@correo.uis.edu.co}}}\\
\textit{Universidad Industrial de Santander}\\
\textit{Calle - 9 Cra. 27, Bucaramanga, Santander}}\\
\date{\today}
\maketitle
\tableofcontents
\begin{abstract}
En este trabajo realizamos el experimento conocido como HidroCañon, cuyo propósito fue analizar cómo diferentes factores influyen en la energía cinética transferida a una pelota contenida en un vaso al ser lanzado desde cierta altura. Para ello, variamos tres parámetros: la altura de lanzamiento, la altura de llenado del líquido en el vaso y la densidad del líquido. Utilizamos una base diseñada para garantizar lanzamientos con condiciones iniciales aproximadamente reproducibles. Los resultados confirmaron que al aumentar la densidad del líquido, la altura de llenado y la altura de lanzamiento, se incrementa la energía cinética transferida a la pelota, lo que permite que esta alcance alturas mayores. Este comportamiento está alineado con las predicciones teóricas y refuerza la relación entre las variables estudiadas y el fenómeno observado.
\end{abstract}

\section{Introducción}
El HidroCanon consiste investigar cómo se transfiere la energía cinética de un vaso en caída libre a una pelota contenida en su interior. Este tipo de experimentos es una herramienta clave para explorar conceptos como la conservación de la energía y las interacciones entre fluidos y sólidos.

El problema específico abordado consiste en llenar un vaso con diferentes líquidos (agua, solución salina, alcohol, aceite y varsol diluido), lanzarlo desde distintas alturas y analizar cómo estos factores afectan la fracción máxima de energía cinética que puede transferirse a la pelota. Este experimento tiene antecedentes en el Torneo Internacional de Física (International Physicists' Tournament, IPT), donde se plantearon investigaciones similares que exploraron la influencia de variables como la forma del recipiente. Sin embargo, dichos estudios no analizaron detalladamente cómo la densidad del líquido afecta el fenómeno.

Varios factores entran en juego en este sistema. La energía potencial del vaso, dada por $E=mgh$ depende de la masa total del sistema (incluyendo tanto el líquido como la pelota) y la altura desde la que cae el recipiente. Como los líquidos más densos tienen mayor masa por unidad de volumen, su energía potencial es más alta, lo que implica que al caer, el vaso con líquidos más densos tiene mayor energía disponible para transferir a la pelota. Este proceso de conversión de energía potencial en energía cinética se transfiere parcialmente a la pelota al impactar el suelo.

Además, la interacción de la pelota con el líquido es influenciada por diversos factores. La fuerza de empuje, según el principio de Arquímedes, depende de la densidad del líquido y afecta el comportamiento de la pelota durante la caída. A mayor densidad del líquido, la fuerza de empuje es mayor, lo que puede alterar la trayectoria de la pelota dentro del vaso. Por otro lado, la tensión superficial también juega un papel, aunque en este experimento resultó ser despreciable, ya que realizamos pruebas donde la influencia de la tensión superficial fue mínima.

Nuestro enfoque se centra en estudiar la influencia de la densidad del líquido sobre la transferencia de energía, complementando los estudios previos. Sin embargo, cabe destacar que la viscosidad del líquido también puede afectar significativamente la dinámica del sistema, como se observó en los experimentos con varsol, donde la alta viscosidad impidió que la pelota rebotara adecuadamente. Esto sugiere que un estudio más detallado que varíe de manera independiente los parámetros de densidad y viscosidad podría proporcionar una comprensión más completa de su influencia en la transferencia de energía.

\section{Metodología}
\label{Metodologia}
El experimento comenzó con intentos manuales de lanzar el vaso desde una altura de un metro, buscando garantizar una caída perpendicular al suelo. Sin embargo, este método presentó varios problemas que comprometían la consistencia y reproducibilidad de los datos:  

\begin{itemize}
    \item \textbf{Inconsistencia en el impacto:} La base del vaso no siempre impactaba de manera coplanar con el suelo, lo que generaba datos inconsistentes y provocaba pérdida de líquido experimental.  
    \item \textbf{Rotura del vaso:} Las fuerzas generadas por el impacto desde la altura designada frecuentemente rompían los vasos, dificultando la repetibilidad del experimento.  
    \item \textbf{Intentos de estabilización:}  
    \begin{itemize}
        \item Se pegó una moneda al centro de la base del vaso utilizando silicona para añadir estabilidad y favorecer una caída vertical. Sin embargo, la moneda se despegaba fácilmente, y la masa adicional incrementó la tasa de rotura del vaso.  
        \item Se sustituyó la silicona por pegante instantáneo para mejorar la fijación, pero esto no fue efectivo, pues se continuaba rompiendo.  
        \item Se reforzaron los vasos con cinta adhesiva, reduciendo levemente su fragilidad estructural, aunque las inconsistencias en los datos persistieron.  
    \end{itemize}
\end{itemize}  

Dado que los lanzamientos manuales y las modificaciones al vaso no resolvieron los problemas identificados, se optó por construir una base soltadora que garantizara lanzamientos consistentes y repetibles.  

Inicialmente se diseñó una base usando madera y palos de balso, fijada a un soporte vertical sin embargo esta estructura resultó ser frágil, rompiéndose a mitad de las mediciones. Finalmente se diseño una base más estable y precisa para los lanzamientos. Esta base fue fabricada con los recursos disponibles en el laboratorio y se compuso de una estructura sólida que asegura la caída vertical del vaso, minimizando los errores humanos.

La base se compone de una pata pesada que sostiene una vara vertical, la cual sirve como guía de altura y como soporte para la base lanzadora. un mecanismo de rueda con libertad de movimiento, que está conectada a una pala en el que se coloca el vaso. El diseño permite que, al liberar la rueda, la pala caiga en caída libre, soltando el vaso desde una altura específica de manera controlada. La base garantiza que el vaso caiga verticalmente, asegurando que los lanzamientos sean consistentes y repetibles. El vaso se coloca sobre el punto de lanzamiento, Figura 1(2), y se asegura visualmente que esté completamente horizontal antes de ser soltado.

\begin{figure}[h]
    \centering
    \includegraphics[width=0.4\linewidth]{Base.png}
    \caption{Configuración experimental utilizada para la caída controlada del vaso. (1) Rueda giratoria . (2) Soporte donde se sostiene el vaso antes de su liberación}
    \label{fig:enter-label}
\end{figure}


\subsection{Parámetros Experimentales}

Los parámetros establecidos para variar durante el experimento fueron los siguientes:

\begin{itemize}
    \item \textbf{Altura de lanzamiento}: 30 cm, 40 cm y 50 cm.
    \item \textbf{Volumen de líquido}: 83.62 ml, 119.80 ml y 154 ml.
    \item \textbf{Líquidos y sus respectivas densidades}: 
    \begin{itemize}
        \item Agua (1 g/ml),
        \item Agua salada (1.19 g/ml),
        \item Alcohol (0.79 g/ml),
        \item Aceite (0.92 g/ml),
        \item Biovarsol (1.02 g/ml).
    \end{itemize}
\end{itemize}

\begin{figure}[h]
    \centering
    % Primera imagen
    \begin{minipage}[t]{0.32\textwidth}
        \centering
        \includegraphics[width=\textwidth]{WhatsApp Image 2024-12-02 at 5.01.13 PM.jpeg} 
        \caption{Alcohol}
        \label{fig:imagen1}
    \end{minipage}
    \hfill
    % Segunda imagen
    \begin{minipage}[t]{0.32\textwidth}
        \centering
        \includegraphics[width=\textwidth]{WhatsApp Image 2024-12-02 at 5.02.12 PM.jpeg} 
        \caption{Aceite}
        \label{fig:imagen2}
    \end{minipage}
    \hfill
    % Tercera imagen
    \begin{minipage}[t]{0.32\textwidth}
        \centering
        \includegraphics[width=\textwidth]{WhatsApp Image 2024-12-02 at 4.57.26 PM.jpeg} 
        \caption{Agua}
        \label{fig:imagen3}
    \end{minipage}
\end{figure}
Para cada combinación de parámetros, se realizaron 5 mediciones. En total, se obtuvieron 225 registros de datos, los cuales fueron grabados utilizando una cámara de alta velocidad con una frecuencia de 120 fotogramas por segundo. La cámara fue colocada en un ángulo adecuado y en un plano estable para garantizar la calidad de las tomas, permitiendo un análisis preciso mediante el programa Tracker.


El uso de la base lanzadora fue importante para minimizar los errores humanos, tales como la variabilidad en el ángulo de caída y la velocidad inicial. Estos factores son críticos, ya que un ángulo incorrecto puede causar que la pelota se desplace lateralmente, lo que dificultaría su medición precisa. Además, si el vaso no cae verticalmente, se pierde el líquido, lo cual es especialmente relevante dado el costo de los líquidos utilizados en el experimento. Otro problema importante que se abordó fue la tasa de rotura de los vasos, que se debía principalmente a la altura de lanzamiento y al ángulo de caída. Este inconveniente se resolvió al reducir la altura de lanzamiento y al utilizar la base lanzadora.




\end{document}  
