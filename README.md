# Ionospheric Echo Detection Using Semantic Segmentation

We aim to replicate the experiments described in the paper "Ionospheric Echo Detection in Digital Ionograms Using
Convolutional Neural Networks" from the Advancing Earth and Space Science Journal submissions 2021.

### Abstract
An ionogram is a graph of the time that a vertically transmitted wave takes to return to the
earth as a function of frequency. Time is typically represented as virtual height, which is the time divided
by the speed of light. The ionogram is shaped by making a trace of this height against the frequency of the
transmitted wave. Along with the echoes of the ionosphere, ionograms usually contain a large amount of
noise and interference of different nature that must be removed in order to extract useful information. In
the present work, we propose a method based on convolutional neural networks to extract ionospheric
echoes from digital ionograms. Extraction using the CNN model is compared with extraction using
machine learning techniques. From the extracted traces, ionospheric parameters can be determined and
electron density profile can be derived.

### Results 
<p align="center">
  <img src="assets/descarga (1).png" alt="Image 1" width="300px"/>
  <img src="assets/descarga (2).png" alt="Image 2" width="300px"/>

  <img src="assets/descarga (3).png" alt="Image 1" width="300px"/>
  <img src="assets/descarga (4).png" alt="Image 2" width="300px"/>
</p>

### Curated Data
- [data](https://drive.google.com/file/d/1N_gQyYZBL1HjNAJS7dITAPCiT5ZU-UlO/view?usp=sharing)
- [masks](https://drive.google.com/file/d/1-74mrE-ZlC5HeRKVuaCp7ryTyS4RUfEj/view?usp=sharing)

### References
- [Ionospheric Echo Detection in Digital Ionograms Using Convolutional Neural Networks](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2020RS007258)
- [Fully Convolutional Networks for Semantic Segmentation](https://arxiv.org/pdf/1411.4038)
- [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/pdf/1505.04597)
