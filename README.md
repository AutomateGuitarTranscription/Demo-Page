<!-- ---
title: "End-to-End Automated Guitar Transcription"
permalink: /
author: "David Kurzendörfer and Christian Hepting"
layout: default
--- -->




<!-- # End-to-End Automated Guitar Transcription with Deep Learning
## subtitle -->



This is the demo page for the practical machine learning course at the university of Tuebingen **End-to-End Automated Guitar Transcription with Deep Learning**

## Abstract
We propose an end-to-end automated guitar transcription method that generates a human-readable transcription from guitar sound to tablature notation. We incorporate knowledge from guitar transcription models of the previous years and address their issues. Most previous work on tablature transcription doesn't tackle onset estimation. The main contribution of this paper is the conjunction of frame-level tablature estimation and true onset estimation, enabling the generation of MIDI files and tablature. We employ a multi-task learning setup, in which frame-level tablature estimation and frame-level onset estimation are performed simultaneously. The model architecture consists of a tablature and an onset stack, that both contain convolutional layers, transformer blocks, and feedforward networks. We train and evaluate our method on GuitarSet. We demonstrate that our method is competitive with baseline tablature transcription models, while achieving a high onset estimation performance.


<!-- ### Training Data Sample
Audio are sampled from training split with different timbre in each column. -->

<!-- |   |DI|Marshall|Fender-twins|Mesa|
|1.|<audio src="Guitar_Transcription_sample/Training/0701_3_c_DI.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0701_3_c_marshall.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0701_3_c_ft.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0701_3_c_mesa.wav" controls="" preload=""></audio>|
|2.|<audio src="Guitar_Transcription_sample/Training/0503_1_a_DI.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0503_1_a_marshall.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0503_1_a_ft.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0503_1_a_mesa.wav" controls="" preload=""></audio>|



### Realistic Data Transcription

|Source|Proposed model|
|<audio src="Guitar_Transcription_sample/RealData/clip1.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/RealDataTranscription/clip1.wav" controls="" preload=""></audio>|
|<audio src="Guitar_Transcription_sample/RealData/clip2.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/RealDataTranscription/clip2.wav" controls="" preload=""></audio>|
|<audio src="Guitar_Transcription_sample/RealData/clip3.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/RealDataTranscription/clip3.wav" controls="" preload=""></audio>|
|<audio src="Guitar_Transcription_sample/RealData/clip4.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/RealDataTranscription/clip4.wav" controls="" preload=""></audio>|
|<audio src="Guitar_Transcription_sample/RealData/clip5.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/RealDataTranscription/clip5.wav" controls="" preload=""></audio>| -->




<!-- ### Dataset
<a href="https://drive.google.com/drive/folders/1ZEy5dytEDquxyf_WYDhKgadSCgPsq_tD?usp=sharing">Google Drive Link</a> -->

<!-- ### Contact
Yu-Hua Chen f08946011@ntu.edu.tw -->
