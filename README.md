# Bengali Vocal Spectrum (BVS): A Bengali Voice Dataset for Psychological Stability Analysis

## 📊 Project Overview

This project provides a detailed implementation of **feature extraction** from audio recordings for psychological stability analysis using the **Bengali Vocal Spectrum (BVS)** dataset. The focus is on creating **spectrograms** from `.wav` audio files to extract frequency and temporal features critical for machine learning models.

### Key Steps in Feature Extraction:
1. **Audio Preprocessing**:
   - Audio files are loaded using `librosa` at a sampling rate of 48,000 Hz.
   - Segmentation is applied to divide audio files into **2-second clips** for finer analysis.

2. **Spectrogram Generation**:
   - **Short-Time Fourier Transform (STFT)** is applied to extract frequency and amplitude variations over time.
   - Spectrograms are converted into decibel scale (logarithmic) for better visualization and machine learning compatibility.

3. **Visualization**:
   - Each spectrogram is saved as a `.png` image for exploratory analysis and model training.
   - The x-axis represents time frames (seconds), while the y-axis represents frequency components.

4. **Output**:
   - Spectrograms for each audio file are saved in structured folders:
     - `data/Stable/` for psychologically stable recordings.
     - `data/Unstable/` for psychologically unstable recordings.

---

## 📄 Dataset Access:
The dataset is publicly available on **Mendeley Data**:
- **Direct URL**: [BVS Dataset](https://data.mendeley.com/datasets/s5j25b5tjk/1)

### 📊 Key Highlights:
- **Ethical Data Collection**: Approved by mental health institutions in Bangladesh.
- **High-Quality Preprocessing**: Ensures clarity and consistency across recordings.
- **Balanced Dataset**: Equal representation of stable and unstable categories.

### 

---

## 🚀 Getting Started

### 1. Clone the Repository
- git clone https://github.com/rafi0020/Bengali_Vocal_Spectrum.git
- cd Bengali_Vocal_Spectrum

### 2. Install Dependencies

pip install pip install librosa matplotlib numpy

### 3. Access the Dataset
- Download the Audio dataset from Mendeley Repository.
- Extract the files and place them in the data/ directory.

### 4. Run the Notebook
Open the Spectrograms_Creation_Code.ipynb file in Jupyter or Colab to:

---

### Audio Statistics:
- Stable: 3,575 spectrogram samples
- Unstable: 4,726 spectrogram samples
  
### Sample Visualizations:

![image](https://github.com/user-attachments/assets/91651d0a-9da7-4c90-b90a-2a72bfa270ba)


---

🤝 Collaboration
We welcome contributions! Please open an issue or submit a pull request for any suggestions or improvements.

---

📫 Contact
For queries, reach out via:
Email: rafiulislam1921@gmail.com
