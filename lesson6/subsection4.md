# Evaluating Generative Audio Models

## Content

Generative audio models can be evaluated using subjective and objective methods:
- **Subjective Methods**: Listener tests are conducted for human perception evaluation.
- **Objective Methods**: Use metrics like Signal-to-Noise Ratio (SNR) and log-likelihood.

```python
# Sample code for evaluation with PySAR GIST
from pesq import pesq
score = pesq(fs, ref_signal, degraded_signal, 'nb')
```

## Video URL

http://video.com/evaluatingAudioModels

## Code Examples

```
# Using PESQ for objective evaluation
from pesq import pesq
score = pesq(fs, ref_signal, degraded_signal, 'wb')
```

## External Links

- [https://www.itl.nist.gov/iad/mig/tests/spet/](https://www.itl.nist.gov/iad/mig/tests/spet/)

## Quizzes

### What does SNR stand for in the context of audio evaluation?

- Signal Notation Review
- Sound Noise Ratio
- Signal-to-Noise Ratio

**Answer:** Signal-to-Noise Ratio