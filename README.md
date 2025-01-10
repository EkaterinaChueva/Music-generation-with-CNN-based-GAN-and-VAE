by Erica Brisigoti and Ekaterina Chueva.

This is a repository for the final project of Neural Networks and Deep Learning course at the University of Padua, taught by prof. Jacopo Pegoraro in a.y. 2023-2024.

The goal of the project was to implement CNN-based models in Pytorch in order to generate music piano rolls.

As the main resource for GAN architecture we used [MidiNet: A Convolutional Generative Adversarial Network for Symbolic-domain Music Generation, by Li-Chia Yang, Szu-Yu Chou, Yi-Hsuan Yang](https://arxiv.org/pdf/1703.10847), the VAE architecture
was done from scratch.

The dataset used for this project is the [MAESTRO MIDI Dataset](https://magenta.tensorflow.org/datasets/maestro), which was obtained by recording the performances of many pianists with Yamaha Disklaviers at the International e-Piano Competition,
for a total over 200 hours of paired audio and MIDI recordings.

## **The files in this directory are**:
1) <code>NNDL_Brisigotti_Chueva.ipynb</code>: a jupyter notebook with the code of the project;
2) <code>NNDL_report_Brisigotti_Chueva.pdf</code>: an article-like description of the project.

## **Content of the project**

The general pipeline of the project is shown below:
![Pipeline](https://github.com/EkaterinaChueva/Music-generation-with-CNN-based-GAN-and-VAE/blob/main/pipeline.png)


### 1) Pre-processing of the MIDI files

The pre-processing part consisted of the following steps:

#### 1.1) Representing MIDI files in the form of piano rolls

#### 1.2) Separating melody and chords, focusing on melody only

#### 1.3) Data augmentation (optional)

### 2) NN (GAN or VAE)

### 3) Qualitative and quantative evaluation of GAN and VAE (with and without data augmentation)

## Results

We found that among seen models CNN-based GAN was better in terms of both qualitative and quantative evaluation, and data augmentation did not improve significantly the performance for these particular architectures and considered number of training epochs.
