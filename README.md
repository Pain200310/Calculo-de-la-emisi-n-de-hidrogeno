\documentclass[12pt]{article}
\usepackage{amsmath}
\usepackage{amsfonts}
\usepackage{amssymb}
\usepackage{booktabs}
\usepackage{siunitx}
\usepackage{geometry}

\geometry{a4paper, margin=2.5cm}

\title{Cálculo del Espectro de Emisión del Hidrógeno}
\author{}
\date{}

\begin{document}

\maketitle

\section{Series Espectroscópicas del Hidrógeno}

\subsection{Serie de Lyman ($n_1 = 1$, ultravioleta)}

\textbf{Transición $1 \rightarrow 2$ (Lyman-$\alpha$):}
\begin{align*}
\frac{1}{\lambda} &= R_H \left( \frac{1}{1^2} - \frac{1}{2^2} \right) = R_H \left( 1 - \frac{1}{4} \right) = R_H \times \frac{3}{4} \\
&= (1.097 \times 10^7) \times \frac{3}{4} = 8.2275 \times 10^6 \, \text{m}^{-1} \\
\lambda &= \frac{1}{8.2275 \times 10^6} \approx 1.215 \times 10^{-7} \, \text{m} = \boxed{121.5 \, \text{nm}}
\end{align*}

\textbf{Transición $1 \rightarrow 3$ (Lyman-$\beta$):}
\begin{align*}
\frac{1}{\lambda} &= R_H \left( 1 - \frac{1}{3^2} \right) = R_H \left( 1 - \frac{1}{9} \right) = R_H \times \frac{8}{9} \\
&= (1.097 \times 10^7) \times \frac{8}{9} \approx 9.751 \times 10^6 \, \text{m}^{-1} \\
\lambda &= \frac{1}{9.751 \times 10^6} \approx 1.026 \times 10^{-7} \, \text{m} = \boxed{102.6 \, \text{nm}}
\end{align*}

\subsection{Serie de Balmer ($n_1 = 2$, visible)}

\textbf{Transición $2 \rightarrow 3$ (H-$\alpha$):}
\begin{align*}
\frac{1}{\lambda} &= R_H \left( \frac{1}{2^2} - \frac{1}{3^2} \right) = R_H \left( \frac{1}{4} - \frac{1}{9} \right) = R_H \times \frac{5}{36} \\
&= (1.097 \times 10^7) \times \frac{5}{36} \approx 1.524 \times 10^6 \, \text{m}^{-1} \\
\lambda &= \frac{1}{1.524 \times 10^6} \approx 6.56 \times 10^{-7} \, \text{m} = \boxed{656 \, \text{nm}}
\end{align*}

\textbf{Transición $2 \rightarrow 4$ (H-$\beta$):}
\begin{align*}
\frac{1}{\lambda} &= R_H \left( \frac{1}{2^2} - \frac{1}{4^2} \right) = R_H \left( \frac{1}{4} - \frac{1}{16} \right) = R_H \times \frac{3}{16} \\
&= (1.097 \times 10^7) \times \frac{3}{16} \approx 2.057 \times 10^6 \, \text{m}^{-1} \\
\lambda &= \frac{1}{2.057 \times 10^6} \approx 4.86 \times 10^{-7} \, \text{m} = \boxed{486 \, \text{nm}}
\end{align*}

\textbf{Transición $2 \rightarrow 5$ (H-$\gamma$):}
\begin{align*}
\frac{1}{\lambda} &= R_H \left( \frac{1}{2^2} - \frac{1}{5^2} \right) = R_H \left( \frac{1}{4} - \frac{1}{25} \right) = R_H \times \frac{21}{100} \\
&= (1.097 \times 10^7) \times \frac{21}{100} \approx 2.3037 \times 10^6 \, \text{m}^{-1} \\
\lambda &= \frac{1}{2.3037 \times 10^6} \approx 4.34 \times 10^{-7} \, \text{m} = \boxed{434 \, \text{nm}}
\end{align*}

\subsection{Serie de Paschen ($n_1 = 3$, infrarrojo cercano)}

\textbf{Transición $3 \rightarrow 4$:}
\begin{align*}
\frac{1}{\lambda} &= R_H \left( \frac{1}{3^2} - \frac{1}{4^2} \right) = R_H \left( \frac{1}{9} - \frac{1}{16} \right) = R_H \times \frac{7}{144} \\
&= (1.097 \times 10^7) \times \frac{7}{144} \approx 5.333 \times 10^5 \, \text{m}^{-1} \\
\lambda &= \frac{1}{5.333 \times 10^5} \approx 1.875 \times 10^{-6} \, \text{m} = \boxed{1875 \, \text{nm}}
\end{align*}

\textbf{Transición $3 \rightarrow 5$:}
\begin{align*}
\frac{1}{\lambda} &= R_H \left( \frac{1}{3^2} - \frac{1}{5^2} \right) = R_H \left( \frac{1}{9} - \frac{1}{25} \right) = R_H \times \frac{16}{225} \\
&= (1.097 \times 10^7) \times \frac{16}{225} \approx 7.798 \times 10^5 \, \text{m}^{-1} \\
\lambda &= \frac{1}{7.798 \times 10^5} \approx 1.282 \times 10^{-6} \, \text{m} = \boxed{1282 \, \text{nm}}
\end{align*}

\subsection{Serie de Brackett ($n_1 = 4$, infrarrojo medio)}

\textbf{Transición $4 \rightarrow 5$:}
\begin{align*}
\frac{1}{\lambda} &= R_H \left( \frac{1}{4^2} - \frac{1}{5^2} \right) = R_H \left( \frac{1}{16} - \frac{1}{25} \right) = R_H \times \frac{9}{400} \\
&= (1.097 \times 10^7) \times \frac{9}{400} \approx 2.468 \times 10^5 \, \text{m}^{-1} \\
\lambda &= \frac{1}{2.468 \times 10^5} \approx 4.05 \times 10^{-6} \, \text{m} = \boxed{4050 \, \text{nm}}
\end{align*}

\subsection{Serie de Pfund ($n_1 = 5$, infrarrojo lejano)}

\textbf{Transición $5 \rightarrow 6$:}
\begin{align*}
\frac{1}{\lambda} &= R_H \left( \frac{1}{5^2} - \frac{1}{6^2} \right) = R_H \left( \frac{1}{25} - \frac{1}{36} \right) = R_H \times \frac{11}{900} \\
&= (1.097 \times 10^7) \times \frac{11}{900} \approx 1.341 \times 10^5 \, \text{m}^{-1} \\
\lambda &= \frac{1}{1.341 \times 10^5} \approx 7.46 \times 10^{-6} \, \text{m} = \boxed{7460 \, \text{nm}}
\end{align*}

\end{document}
