# Deep-learning-based Text-to-speech-TTS Papers and resources 
Various Text-to-speech (TTS) papers and resources based on Deep-learning


----
## Data

### [Melspectrogram]
* **Speech Technology: A Practical Introduction, Topic: Spectrogram, Cepstrum and Mel-Frequency Analysis** (K. Prahallad., CMU, [slide](http://www.speech.cs.cmu.edu/15-492/slides/03_mfcc.pdf), [video](https://archive.org/details/SpectrogramCepstrumAndMel-frequency_636522))

----
## Mel-spectrogram Generator

### [Autoregressive]

#### **RNN**

* **Char2Wav** (J. Soleto et. al., Feb. 2017., Motreal., [paper](https://mila.quebec/wp-content/uploads/2017/02/end-end-speech.pdf))
* **Tacotron** (Y. Wang et. al., Mar. 2017., Google, [arxiv](https://arxiv.org/pdf/1703.10135.pdf))
* **Tacotron 2** (J. Shen et.al., Dec. 2017., Google, [arxiv](https://arxiv.org/pdf/1712.05884.pdf))



#### **CNN**
* **Deep Voice 3** (W. Ping et. al., Oct. 2017., Baidu, [arxiv](https://arxiv.org/pdf/1710.07654.pdf))
* **Deep Convolutional Text-to-speech** (H. Tachibana et. al., Oct. 2017., [arxiv](https://arxiv.org/pdf/1710.08969.pdf))



#### **Transformer**
* **Transformer TTS** (N. Li et. al., Sep. 2018., Microsoft, [arxiv](https://arxiv.org/pdf/1809.08895.pdf))


### [Non-autoregressive]
#### **CNN**
* **ParaNet** (K. Peng et. al., May. 2019., Baidu, [arxiv](https://arxiv.org/pdf/1905.08459.pdf))

#### **Transformer**
* **Fast Speech** (Y. Ren et. al., May. 2019., Microsoft, [arxiv](https://arxiv.org/pdf/1905.09263.pdf))
* **Align TTS** (Z. Zeng et. al., Mar. 2020., Ping An Tech., [arxiv](https://arxiv.org/pdf/2003.01950.pdf))
* **Fast Speech 2** (Y. Ren et. al., Jun. 2020., Microsoft, [arxiv](https://arxiv.org/pdf/2006.04558.pdf))

### [Graph Neural Networks]
* **Graph TTS** (A. Sun et. al., Mar. 2020., Ping An Tech., [arxiv](https://arxiv.org/pdf/2003.01924.pdf))


### [Attention Improvement]
* **Monotonic Attention** (C. Raffel et. al., Jun. 2017., Google Brain, [arxiv](https://arxiv.org/pdf/1704.00784.pdf))
* **Monotonic Chunkwise Attention** (C.C. Chiu et. al., Dec. 2017., Google Brain, [arxiv](https://arxiv.org/pdf/1712.05382.pdf))
* **Stepwise Monotonic Attention** (M. He et. al., Jun. 2019., Microsoft, [arxiv](https://arxiv.org/pdf/1906.00672.pdf)) 
* **Location-relative Attention Mechanisms for Robust Long-form Speech Synthesis** (E. Battenberg et. al., Oct. 2019., Google, [arxiv](https://arxiv.org/pdf/1910.10288.pdf)) 


### [Training Algorithm]
* **A New GAN-based Training Algorithm** (H. Guo. et. al., Apr. 2019., Microsoft, [arxiv](https://arxiv.org/pdf/1904.04775.pdf))


### [Data-Efficient]
* **Semi-supervised Training for Improving Data Efficiency in End-to-end Speech Synthesis** (Y.A. Chung et. al., Aug. 2018., MIT & Google, [arxiv](https://arxiv.org/pdf/1808.10128.pdf))
* **Sample Efficient Adaptive Text-to-Speech** (Y. Chen., Jan. 2019., DeepMind & Google, [arxiv](https://arxiv.org/pdf/1809.10460.pdf))


----
## Neural Vocoder
### [Autoregressive Model]

* **WaveNet** (A. V. Oord et. al., Sep. 2016., Deep Mind, [arxiv](https://arxiv.org/pdf/1609.03499.pdf))
* **SampleRNN** (S. Mehri et. al., Dec. 2016, Montreal, [arxiv](https://arxiv.org/pdf/1612.07837.pdf))

### [Inverse Autoregressive Flow Model]
* **Parallel WaveNet** (A. V. Oord et. al., Nov. 2017., Deep Mind, [arxiv](https://arxiv.org/pdf/1711.10433.pdf))
* **ClariNet** (W. Ping et. al., Jul. 2018., Baidu, [arxiv](https://arxiv.org/pdf/1807.07281.pdf))
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
* **Disentangling Correlated Speaker and Noise for Speech Synthesis via Data Augmentation and Adversarial Factorization** (W. N. Hsu et. al., Sep. 2019., Google, [paper](https://openreview.net/pdf?id=Bkg9ZeBB37))
### [Mutual Information]
* **Unsupervised Style and Content Separation by Minimizing Mutual Information for Speech Synthesis**  (T.Y. Hu et. al., Mar. 2020., CMU & Apple, [arxiv](https://arxiv.org/pdf/2003.06227.pdf))



## Dataset
### [English]

#### **ASR**
  * LibriSoeech dataset ([paper](http://www.danielpovey.com/files/2015_icassp_librispeech.pdf), [download](https://www.openslr.org/12)) (V. Panayotov et al., 2015)
    - total 2484 speakers, 1000+ hours
  * VocCeleb1 dataset ([paper](https://www.robots.ox.ac.uk/~vgg/publications/2017/Nagrani17/nagrani17.pdf) [download](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/)) (A. Nagrani et al., 2017)
    - 151,516 utterances, 1251 speakers, 352 hours
  * VoxCeleb2 dataset ([paper](https://www.robots.ox.ac.uk/~vgg/publications/2018/Chung18a/chung18a.pdf) [download](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/)) (J. S> Chung et al., 2018)
    - 1,128,246 utterances, 6112 speakers, 2442 hours

#### **TTS**
  * LJSpeech dataset [download](https://keithito.com/LJ-Speech-Dataset/) (Keith Ito and Linda Johnson, 2017)
    - single female speaker, 13100 samples, approximately 24 hours
  * CSTR VCTK Corpus ([download](http://www.udialogue.org/download/cstr-vctk-corpus.html) (C. Veaux et. al.))
    - 109 english speakers with various accents, 400 speeches per speaker
  * Blizzard dataset [download](https://www.cstr.ed.ac.uk/projects/blizzard/data.html)


### [Korean]
#### **ASR**
* 한국어 및 영어 음향모델 훈련용 음성 데이터 [download](https://aiopen.etri.re.kr/service_dataset.php?category=voice) (ETRI)
  - (Korean speech) 50 speakers * 100 speeches/speaker (total 5,000 speech samples) 
  - (English speech **pronounciated by Korean**) 50 speakers * 100 speech (total 5,000 speech samples)
* 음성인터페이스 개발을 위한 어린이 음성 데이터 [download](https://aiopen.etri.re.kr/service_dataset.php?category=voice) (ETRI)
  - 50 speakers * 100 speeches/speaker * 3 environments (total 16,200 speech samples)
  - speaker info: elementary school students (from 1st to 4th grade)
  - recorded from IPhone5, Samsung GalaxyS4, and microphones
* ClovaCall datset ([paper](https://arxiv.org/pdf/2004.09367.pdf) [download](https://github.com/clovaai/ClovaCall)) (Naver Corp.)
  - 140000+ speeches, 211+ hours of noisy and clean speech
* KSponSpeech [download](https://aihub.or.kr/aidata/105/download) (ETRI)
  - 2000 speakers, 1000+ hours, various topics(life, shopping, hobby, weather, etc..)
* Korean Read Speech Corpus (국립국어원)
  - 8 speakers, 120+ hours
* Zeroth-Korean [download](http://www.openslr.org/40/) (Lucas Jo and Wonkyum Lee)
  - 115 speakers, 52.8 hours, 22720 utterances in total
* Pansori TED x KR Corpus ([paper](https://arxiv.org/ftp/arxiv/papers/1812/1812.09798.pdf) [download](https://github.com/yc9701/pansori-tedxkr-corpus)) (Y. Choi and B. Lee) 
  - 3 hours, 41 speakers

#### **TTS**
* Korean Single Speaker (KSS) Speech Dataset [download](https://www.kaggle.com/bryanpark/korean-single-speaker-speech-dataset) (K. Park)
  - single female speaker, 12853 samples, 12+ hours
* 감정 음성합성 데이터셋 [download](https://aihub.or.kr/keti_data_board/expression) ((주) 아크릴)
  - single female speaker, 7 emotion (neutral, sad, fear, happy, angry, disgusting, surprise), total 22,000 samples (about 3,000 samples per emotion)
*  EmotionTTS-Open-DB dataset [download](https://github.com/emotiontts/emotiontts_open_db/tree/master/Dataset/SpeechCorpus) (KAIST and (주) 셀바스AI)
  - single-speaker, multi-speaker, and multi-speaker-multi-emotion dataset 
* 카이스트 오디오북 데이터셋 [download](https://aihub.or.kr/open_data/21292) (KAIST)
  - 58559 speeches, 72+ hours, 13 speakers
  - various reading materials (news, novel, etc..)
