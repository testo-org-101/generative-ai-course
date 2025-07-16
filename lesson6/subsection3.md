# Creating Generative Models for Audio

## Content

Different models can be used for generating audio: 
- **WaveNet**: Generates high-fidelity audio with autoregressive models.
- **GAN-based models**: Such as WaveGAN, which focus on generating raw audio directly using adversarial training.

### WaveNet Example Code:
```python
model = WaveNetModel(layer_size=30, stack_size=5, dilations=[1, 2, 4, 8])
model.compile(optimizer='adam', loss='categorical_crossentropy')
```

## Video URL

http://video.com/generativeAudioModels

## Code Examples

```
# Example of simple WaveNet configuration...

```

## External Links

- [https://deepmind.com/research/publications/wavenet](https://deepmind.com/research/publications/wavenet)

## Quizzes

### Which model is primarily used for high-fidelity audio generation?

- WaveGAN
- WaveNet
- AutoEncoder

**Answer:** WaveNet