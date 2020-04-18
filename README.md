# Deep-learning-based-Text-to-speech-TTS-Papers
Various Text-to-speech (TTS) papers based on Deep-learning


----
## Mel-spectrogram Generator

### [Autoregressive]

#### **RNN**

* **Char2Wav** (J. Soleto et. al., Feb. 2017., Motreal., [paper](https://mila.quebec/wp-content/uploads/2017/02/end-end-speech.pdf))
* **Tacotron** (Y. Wang et. al., Mar. 2017., Google, [arxiv](https://arxiv.org/pdf/1703.10135.pdf))
* **Tacotron 2** (H. Tachibana et.al., Dec. 2017., Google, [arxiv](https://arxiv.org/pdf/1710.08969.pdf))



#### **CNN**
* **Deep Voice 3** (W.Ping et. al., Oct. 2017., Baidu, [arxiv](https://arxiv.org/pdf/1710.07654.pdf))
* **Deep Convolutional Text-to-speech** (J. Shen et.al., Oct. 2017., [arxiv](https://arxiv.org/pdf/1710.08969.pdf))



#### **Transformer**
* **Transformer TTS** (N. Li et. al., Sep. 2018., Microsoft, [arxiv](https://arxiv.org/pdf/1809.08895.pdf))


### [Non-autoregressive]
#### **CNN**
* **ParaNet** (K. Peng et. al., May. 2019., Baidu, [arxiv](https://arxiv.org/pdf/1905.08459.pdf))

#### **Transformer**
* **Fast Speech** (Y. Ren et. al., May. 2019., Microsoft, [arxiv](https://arxiv.org/pdf/1905.09263.pdf))
* **Align TTS** (Z. Zeng et. al., Mar. 2020., Ping An Tech., [arxiv](https://arxiv.org/pdf/2003.01950.pdf))

### [Attention Improvement]
* **Monotonic Attention** (C. Raffel et. al., Jun. 2017., Google Brain, [arxiv](https://arxiv.org/pdf/1704.00784.pdf))
* **Monotonic Chunkwise Attention** (C.C. Chiu et. al., Dec. 2017., Google Brain, [arxiv](https://arxiv.org/pdf/1712.05382.pdf))
* **Stepwise Monotonic Attention** (M. He et. al., Jun. 2019., Microsoft, [arxiv](https://arxiv.org/pdf/1906.00672.pdf)) 
* **Location-relative Attention Mechanisms for Robust Long-form Speech Synthesis** (E. Battenberg et. al., Oct. 2019., Google, [arxiv](https://arxiv.org/pdf/1910.10288.pdf)) 


### [Training Algorithm]
* **A New GAN-based Training Algorithm** (H. Guo. et. al., Apr. 2019., Microsoft, [arxiv](https://arxiv.org/pdf/1904.04775.pdf))



----
## Neural Vocoder
### [Autoregressive Model]

* **WaveNet** (A. V. Oord et. al., Sep. 2016., Deep Mind, [arxiv](https://arxiv.org/pdf/1609.03499.pdf))
* **SampleRNN** (S. Mehri et. al., Dec. 2016, Montreal, [arxiv](https://arxiv.org/pdf/1612.07837.pdf))

### [Inverse Autoregressive Flow Model]
* **Parallel WaveNet** (A. V. Oord et. al., Nov. 2017., Deep Mind, [arxiv](https://arxiv.org/pdf/1711.10433.pdf))
* **WaveGlow** (R. Prenger et. al., Nov. 2018., NVIDIA, [arxiv](https://arxiv.org/pdf/1811.00002.pdf))
* **FlowWaveNet** (S. Kim et. al., Nov. 2018., SNU, [arxiv](https://arxiv.org/pdf/1811.02155.pdf))


### [Generative Adversarial Network]
* **WaveGAN** (C.Donahue et. al., Feb. 2018., UCSD, [arxiv](https://arxiv.org/pdf/1802.04208.pdf))
* **GAN-TTS** (M. Binkowski, Sep. 2019., Google, [arxiv](https://openreview.net/pdf?id=r1gfQgSFDr))
* **Parallel WaveGAN** (R. Yamamoto et. al., Oct. 2019., Naver, [arxiv](https://arxiv.org/pdf/1910.11480.pdf))
---

## Style Modeling
### [Style Token]
* **Uncovering Latent Style Factors for Expressive Speech Synthesis** (Y. Wang et. al., Nov. 2017., Google, [arxiv](https://arxiv.org/pdf/1711.00520.pdf))
* **GST Tacotron** (Y. Wang et. al., Mar. 2018., Google, [arxiv](https://arxiv.org/pdf/1803.09017.pdf))
* **TP-GST Tacotron** (D. Santon et al., Aug. 2018., Google, [arxiv](https://arxiv.org/pdf/1808.01410.pdf))


### [Generative Adversarial Network]
* **TTS-GAN** (S. Ma et. al., Apr. 2019., Microsoft, [paper](https://openreview.net/pdf?id=ByzcS3AcYX))
* **Learning to Speak Fluently in a Foreign Language: Multilingual Speech Synthesis and Cross-Language Voice Cloning** (Y. Zhang et. al., Jul. 2019., Google, [arxiv](https://arxiv.org/pdf/1907.04448.pdf)) 
* **Disentangling Correlated Speaker and Noise for Speech Synthesis via Data Augmentation and Adversarial Factorization** (W.N. Hsu et. al., Sep. 2019., Google, [paper](https://openreview.net/pdf?id=Bkg9ZeBB37))
### [Mutual Information]
* **Unsupervised Style and Content Separation by Minimizing Mutual Information for Speech Synthesis**  (T.Y. Hu et. al., Mar. 2020., CMU & Apple, [arxiv](https://arxiv.org/pdf/2003.06227.pdf))

### [Data-Efficient]
* **Semi-supervised Training for Improving Data Efficiency in End-to-end Speech Synthesis** (Y.A. Chung et. al., Aug. 2018., MIT & Google, [arxiv](https://arxiv.org/pdf/1808.10128.pdf))
