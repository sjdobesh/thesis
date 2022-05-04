# Relevant Published Code:
- [Valence Arousal Detection Using Extreme Learning Machines](https://github.com/aeldesoky/valence-arousal-detection-using-elm)
	- Git submodule: [TEAP(Toolbox for Emotional feAture extraction)](https://github.com/aeldesoky/valence-arousal-detection-using-elm/tree/1e5f13136670432014fc066e8e2e9ee65da1ca0f/Matlab/TEAP-master)

# python libraries
- pyaudio
	- cross platform python audio playback and manupulation.
- pya
	- looks a little simpler than pyaudio
	- includes signal generators
	- looks outdated

[[https://stackoverflow.com/questions/8299303/generating-sine-wave-sound-in-python|pyaudio signal generator example]]
```python
import pyaudio
import numpy as np

# initiate pyaudio
p = pyaudio.PyAudio()

# audio data
volume: float   = 0.5   # range of [0.0, 1.0]
fs: int         = 44100 # sampling in hz
duration: float = 1.0   # in seconds
f: float = 440.0        # frequency in hz

# generate samples and convert to float32 array
samples = (volume * (np.sin(2*np.pi*np.arange(fs*duration)*f/fs)).astype(np.float32)).tobytes()

# define stream. sample vals must be in range [-1.0, 1.0]
stream = p.open(
	format=pyaudio.paFloat32,
	channels=1,
	rate=fs,
	output=True
)

# play
stream.write(samples)

# stop playing and close stream
stream.stop_stream()
stream.close()

# terminate pyaudio engine
p.terminate()
```
