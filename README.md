# GPU Spectral Modeling Synthesizer
 
## Objective
The objective of this research project is to implement a spectral modeling synthesizer using NVIDIA CUDA for hardware acceleration. Performance will be compared with the results in the [original paper from SCREAM Lab at National Cheng Yung University.](https://www.scopus.com/record/display.uri?eid=2-s2.0-85139270895&origin=inward&txGid=f18559f78eb8f0ed1c6515e62b429e34) The synthesizer will be packaged in a VST3 plugin for use in music production.

## Background
Software synthesizers that use the CPU can hit a performance cap with certain complex algorithms. In a music project that can potentially have hundreds of software synthesizers, overloading the CPU can cause audible skips and pops during production. Using the GPU to synthesize audio will reduce system load and potentially create higher quality software synthesizers.
