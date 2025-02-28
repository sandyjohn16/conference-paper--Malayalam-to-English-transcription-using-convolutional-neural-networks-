
# Conference Paper: Malayalam to English Transcription using Convolutional Neural Networks

## Title
**Overcoming the Barrier of Emotion in Interlingual Transcription:**  
_A Case Study of Malayalam to English Transcription using Convolutional Neural Networks_

---

## Authors
- Sandra John    
- Abdul Khader Abdul Vahid  
- Lakshmi Radhakrishnan Nair  
- Mohammad Farhan Khan
- Fakhreldin Saeed 

**Affiliation:** Department of Computing, Sir David Bell Building, Digby Stuart College, University of Roehampton, London, UK

---

## Abstract
This paper addresses the challenge of interlingual speech-to-text transcription from **Malayalam to English**, specifically considering the influence of **emotions** and **accents** in speech data. Traditional models struggle to perform well on noisy and emotionally varied datasets. The proposed method leverages **Convolutional Neural Networks (CNN)** using both **1D speech vectors** and **2D spectrogram matrices** to enhance transcription accuracy. Data pre-processing techniques such as **silence removal**, **outlier elimination**, **amplitude normalization**, and **spectral reduction** play a crucial role in improving performance.

---

## Key Features
✅ Real-world speech data from native Malayalam speakers  
✅ Pre-processing pipeline for noise and silence removal  
✅ Comparative performance evaluation of 1D vs 2D CNN architectures  
✅ Case study on non-native Malayalam speakers to assess generalization

---

## Dataset
- 871 speech samples collected from native Malayalam speakers (male and female)
- Samples captured using mobile devices without specialized microphones
- Dataset includes a range of emotions and accents, enhancing diversity
- Class labels represent days of the week spoken in Malayalam

---

## Pre-processing Steps
1. **Silence Removal:** Trims unnecessary silent segments.
2. **Outlier Elimination:** Removes samples with unusual durations.
3. **Amplitude Normalization:** Standardizes volume levels.
4. **Spectral Reduction:** Reduces dimensionality of spectrograms while preserving essential features.

---

## CNN Architectures
### 1D CNN (Speech Vector Input)
- Convolves directly over temporal speech signals.

### 2D CNN (Spectrogram Input)
- Extracts spatial and temporal patterns from time-frequency representations.

---

## Results Summary
| Model | Pre-processing | Accuracy |
|---|---|---|
| 1D CNN | Full pipeline | 66.47% |
| 2D CNN | Full pipeline | 98.86% |

- 2D CNN outperforms 1D CNN, especially when emotions and accents vary.
- Case study with non-native Malayalam speakers showed reduced accuracy, indicating the need for further augmentation or domain adaptation.

---

## Citation
If you use this work, please cite as:

> Sandra John, Fakhreldin Saeed, Abdul Khader Abdul Vahid, Lakshmi Radhakrishnan Nair, Mohammad Farhan Khan, "Overcoming the Barrier of Emotion in Interlingual Transcription: A Case Study of Malayalam to English Transcription using Convolutional Neural Networks," in *2024 International Technology Conference on Smart Computing for Innovation and Advancement in Industry 4.0 (OTCON)*, IEEE, 2024. DOI: 10.1109/OTCON60325.2024.10687437.
git commit -m "Initial commit with README"
git branch -M main
git remote add origin <your-repository-URL>
git push -u

