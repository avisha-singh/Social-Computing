# Mental Health Estimation and IKS-Based Intervention

This project aims to estimate mental health using multimodal emotion recognition and design interventions rooted in Indian Knowledge Systems (IKS). The system utilizes Machine Learning (ML) and Deep Learning (DL) techniques to analyze text, audio, and video data for emotion detection, which is then used to evaluate mental health. Additionally, the project proposes a virtual reality-based chanting intervention to improve mental health indicators.

## Project Structure

### 1. **Text-Based Emotion Detection**
   - **Objective**: Analyze social media comments to detect emotions using text data.
   - **Method**: BERT model fine-tuned on the GoEmotions dataset to classify text into 27 emotion classes.
   - **Code**: Includes a preprocessing notebook and models trained for Big Five personality prediction.

### 2. **Audio Emotion Recognition**
   - **Objective**: Detect emotions from audio data using ML/DL methods.
   - **Dataset**: RAVDESS dataset.
   - **Features**: Extracted using `Librosa`, includes MFCC, Chroma STFT, and Spectral Centroid.
   - **Models**: Random Forest, SVM, XGBoost.
   - **Results**: Best results achieved with SVM (68.72% accuracy on spectrogram features).

### 3. **Video-Based Emotion Detection**
   - **Objective**: Analyze YouTube video frames to predict emotions.
   - **Method**: Extracted frames from video, passed through VGG19 for feature extraction, followed by emotion classification.

### 4. **IKS-Based Mental Health Intervention**
   - **Objective**: Use immersive VR environments with chanting to improve mental health parameters.
   - **Data Collection**: EEG, HRV, Stroop, DASS, PANAS before and after meditation.
   - **Results**: Significant improvement in HRV and EEG parameters, reduction in stress, anxiety, and depression.

## Project Components

- **Colab Notebooks**:
  - Preprocessing and Model Training for Text-based Emotion Detection.
  - Audio Emotion Feature Extraction and Model Training.
  - Video Frame Processing for Emotion Prediction.

- **Datasets**:
  - [GoEmotions](https://github.com/google-research/google-research/tree/master/goemotions) (for text analysis).
  - RAVDESS (for audio analysis).
  - YouTube videos (for video analysis).

- **Interventions**:
  - Chanting interventions in VR to assess mental health improvement.

## Installation and Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/project.git
