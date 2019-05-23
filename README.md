# MFCC-speech-recognition

This repository contains an easy-to-train machine learning architecture that
can recognize speech commands on low-end, commodity hardware in real-time.

Specifically, the architecture uses "Mel-frequency cepstral coefficients" as
input features to a small neural network, achieving "near state-of-the-art"
classification accuracy.

Importantly, this implementation has an inference time of ~10 microseconds on
a desktop CPU for 0.1 s of input sound. In other words, it could run in
real-time on systems up to 10,000x slower than our desktop CPU.

A more comprehensive description of the architecture and its performance can
be read [here](report/DeepHark.pdf).

This project was originally hosted
[here](https://github.com/deephark/DeepHark).
