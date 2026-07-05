# semanticnaming

Reproducibility

To facilitate reproducibility, all source code, configuration files, and deployment scripts will be publicly released upon publication. The repository will include:
- Source code for semantic caption generation
- Quantized GGUF model configuration
- NDN semantic naming implementation
- Smartphone application source code
- Experimental datasets and evaluation scripts
- Performance profiling utilities
The experimental workflow consists of the following steps:
- Install the quantized Moondream2 GGUF model and \texttt{llama.cpp} runtime.
- Launch the Android application to capture and stream road-scene images.
- Execute the semantic caption generation module.
- Apply the semantic event extraction algorithm.
- Automatically generate hierarchical NDN names.
- Store generated semantic metadata in the local semantic cache.
- Retrieve semantic information using NDN Interest packets.
