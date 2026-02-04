🎧 Speech Emotion Recognition using Audio

This project focuses on identifying human emotions from speech audio using machine learning and deep learning techniques.
The system analyzes audio signals and classifies them into one of eight emotional categories, based on how humans express emotions through voice.

The goal of this project was not just accuracy, but to understand the complete pipeline — from raw audio processing to model evaluation and visualization.

⸻

🔍 Problem Statement

Human emotions are strongly reflected in speech patterns such as tone, pitch, and intensity.
Manually identifying emotions from audio is subjective and inconsistent.

This project aims to:
	•	Automatically detect emotions from speech
	•	Learn meaningful audio features
	•	Build an interpretable and visual ML pipeline

⸻

🎯 Emotions Classified

The model classifies audio into the following 8 emotions:
	•	Angry
	•	Calm
	•	Disgust
	•	Fearful
	•	Happy
	•	Neutral
	•	Sad
	•	Surprised

⸻

📂 Datasets Used
	•	RAVDESS – Ryerson Audio-Visual Database of Emotional Speech and Song
	•	TESS – Toronto Emotional Speech Set

Both datasets provide labeled emotional speech samples, which were cleaned and unified before training.

⸻

⚙️ Project Workflow (High-Level)
	1.	Audio Loading
Audio files are loaded and standardized using Librosa.
	2.	Feature Extraction
Important speech characteristics are extracted using:
	•	MFCCs
	•	Mel Spectrograms
	3.	Preprocessing
	•	Feature scaling
	•	Label encoding
	•	Train–test split
	4.	Model Training
	•	An LSTM-based neural network is trained to classify emotions.
	5.	Evaluation & Visualization
	•	Accuracy and loss tracking
	•	Confusion matrix
	•	Per-class accuracy analysis

⸻

🧠 Model Used
	•	LSTM (Long Short-Term Memory) network
	•	Chosen because speech is sequential data, and LSTM helps model temporal patterns in audio features.

⸻

🧪 Performance Summary
	•	Overall Accuracy: ~82%
	•	Strong performance on:
	•	Neutral
	•	Angry
	•	Happy

The model generalizes reasonably well given the dataset size and feature-based approach.

⸻

📊 Visualizations Included

This project includes multiple visualizations to better understand the data and model behavior:
	## 📊 Visualizations

### Audio Waveform
![Audio Waveform](images/waveform.png)

### Mel Spectrogram
![Mel Spectrogram](images/mel_spectrogram.png)

### Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

### Training Curves
![Training Curves](images/training_curves.png)

### Feature Correlation Matrix
![Feature Correlation Matrix](images/feature_correlation_matrix.png)
### Per-Class Accuracy
![Per-Class Accuracy](images/per_class_accuracy.png)

These help explain why the model behaves the way it does, not just what it predicts.

⸻

🛠️ Tech Stack (One-Line Each)
	•	Python – Core programming language
	•	MFCCs – Speech feature extraction
	•	Mel Spectrogram – Audio frequency representation
	•	LSTM – Sequential learning model
	•	Librosa – Audio processing library
	•	TensorFlow / Keras – Model training framework

⸻

🚀 Future Improvements
	•	Use frame-level sequential features instead of mean-pooled vectors
	•	Apply data augmentation (noise, pitch shift, time stretch)
	•	Add early stopping and regularization to reduce overfitting

⸻

👤 Author

Shiv Arora
B.Tech (Hons.) Computer Science – Cybersecurity
AI / ML & Security Projects

	•	LinkedIn: https://www.linkedin.com/in/shivarora1/
	•	GitHub: https://github.com/shivabtech23
