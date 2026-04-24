# Speech Emotion Recognition

A comparative deep learning study to determine the best model architecture for classifying human emotions from speech audio.

## Problem
Emotion detection from speech has applications in mental health monitoring, customer service analytics, and human-computer interaction. This project evaluates which architecture performs best on this task.

## Approach
Three architectures were trained and compared on the same dataset:
- CNN/LSTM with data augmentation
- CNN/LSTM without data augmentation
- Transformer-based model

## Results
| Model | Accuracy |
|---|---|
| CNN/LSTM with data augmentation | 97% |
| CNN/LSTM without data augmentation | 93% |
| Transformer | Comparative baseline |

Datasets used: EmoDB and TESS

## Tech Stack
- Python
- TensorFlow, Keras
- CNN, LSTM, Transformers
- NumPy, Scikit-Learn
- Librosa (audio processing)

## How to Run
```bash
git clone https://github.com/Temitope3003/Speech_Emotion_Recognition
cd Speech_Emotion_Recognition
pip install -r requirements.txt
jupyter notebook
```

## Key Takeaway
CNN/LSTM with data augmentation outperformed the Transformer baseline on the EmoDB and TESS datasets, achieving 97% accuracy.
