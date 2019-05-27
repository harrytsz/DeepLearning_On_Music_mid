Note: deepjazz has been succeeded by songbird.ai and is no longer being actively developed.

deepjazz

Using Keras & Theano for deep learning driven jazz generation

I built deepjazz in 36 hours at a hackathon. It uses Keras & Theano, two deep learning libraries, to generate jazz music. Specifically, it builds a two-layer LSTM, learning from the given MIDI file. It uses deep learning, the AI tech that powers Google's AlphaGo and IBM's Watson, to make music -- something that's considered as deeply human.

SoundCloud
Check out deepjazz's music on SoundCloud!

Dependencies

Keras
Theano ("bleeding-edge" version on GitHub)
music21
Instructions


Run on CPU with command:

python generator.py [# of epochs]
Run on GPU with command:

THEANO_FLAGS=mode=FAST_RUN,device=gpu,floatX=float32 python generator.py [# of epochs]
Note: running Keras/Theano on GPU is formally supported for only NVIDIA cards (CUDA backend).

Note: preprocess.py must be modified to work with other MIDI files (the relevant "melody" MIDI part needs to be selected). The ability to handle this natively is a planned feature.

If you want to get more detail about music21, you can visit the webpage below:

Music21 Documentation: http://web.mit.edu/music21/doc/

## Installation:
1.music21
```
pip install music21
```
2.pygame
You may should also install the pygame package:
```
pip install pygame
```