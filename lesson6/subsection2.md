# Pre-processing Audio Data for Generative Models

## Content

· Audio normalization is crucial to reduce the range of values and stabilize training.
· Feature extraction is conducted to convert audio signals into feature vectors (e.g., MFCC – Mel-Frequency Cepstral Coefficients).
· Data augmentation can be applied to increase dataset size by introducing noise or shifting pitch.

## Video URL

http://video.com/preProcessingAudio

## Code Examples

```
import librosa
signal, sr = librosa.load('audio_file.wav', sr=16000)
mfccs = librosa.feature.mfcc(y=signal, sr=sr, n_mfcc=20)
```

## External Links

- [https://librosa.org/](https://librosa.org/)

## Quizzes

### What is MFCC used for in audio processing?

- Data Augmentation
- Noise Reduction
- Feature Extraction

**Answer:** Feature Extraction