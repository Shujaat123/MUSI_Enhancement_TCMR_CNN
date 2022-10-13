# MUSI_Enhancement_TCMR_CNN
Medical Ultrasound Image Speckle Reduction and Resolution Enhancement Using Texture Compensated Multi-Resolution Convolution Neural Network

1.   First a sample image breast US (BUS) Dataset B [1] image is downlaoded from http://goo.gl/SJmoti
2.   To generate low-resolution version of sample image using *bicubic-interpolation* original image is first reduced to to *64x64* size and then it is increase to *256x256* size to match model input.
3.   The low-resolution version of a sample image is placed in [BUS_64x64] folder
4.   A working example on sample BUS image is available as a colab-notebook (see MUSI_Enhancement_TCMR_CNN.ipynb)

[1] Yap, Moi Hoon, Gerard Pons, Joan Marti, Sergi Ganau, Melcior Sentis, Reyer Zwiggelaar, Adrian K. Davison, and Robert Marti. "*Automated breast ultrasound lesions detection using convolutional neural networks*." IEEE journal of biomedical and health informatics 22, no. 4 (2017): 1218-1226.
