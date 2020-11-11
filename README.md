# generate_music_TensorFlow
Use TensorFlow to generate short sequences of music with a [Restricted Boltzmann Machine](http://deeplearning4j.org/restrictedboltzmannmachine.html). 

## Dependencies

* [Tensorflow](https://www.tensorflow.org/versions/r0.10/get_started/os_setup.html)
* pandas
* numpy
* msgpack
* glob
* tqdm 

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies (i.e pip install msgpack) 

## Basic Usage
To train the model and create music, simply clone this directory and run
```
python rbm_chords.py
```

The training data goes in the pop_music_midi folder. You have to use MIDI files. You can find some [here](http://www.midiworld.com/files/). Training will take 5-10 minutes on a modern laptop. The output will be a collection of midi files. You can combine them together with a script if you'd like. 


## Credits
This is the code for [Generate Music in TensorFlow](Siraj Raval) on YouTube. 
The credit for this code goes to [dshieble](https://github.com/dshieble)
