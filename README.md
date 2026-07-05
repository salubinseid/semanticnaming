# semanticnaming

\subsection{Reproducibility}

To facilitate reproducibility, all source code, configuration files, and deployment scripts will be publicly released upon publication. The repository will include:

\begin{itemize}
\item Source code for semantic caption generation
\item Quantized GGUF model configuration
\item NDN semantic naming implementation
\item Smartphone application source code
\item Experimental datasets and evaluation scripts
\item Performance profiling utilities
\end{itemize}

The experimental workflow consists of the following steps:

\begin{enumerate}
\item Install the quantized Moondream2 GGUF model and \texttt{llama.cpp} runtime.
\item Launch the Android application to capture and stream road-scene images.
\item Execute the semantic caption generation module.
\item Apply the semantic event extraction algorithm.
\item Automatically generate hierarchical NDN names.
\item Store generated semantic metadata in the local semantic cache.
\item Retrieve semantic information using NDN Interest packets.
\end{enumerate}

The complete implementation, installation instructions, and experimental scripts will be available at:

\begin{center}
\texttt{https://github.com/XXXX/semantic-iov-edge}
\end{center}
