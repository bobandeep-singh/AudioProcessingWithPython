# AudioProcessingPython
I wrote this python code to process an audio files using methods from pydub module. The audio is of wav format. The script can split the audio word by word and you can either generate individual wav audio files of individual word or analyse them. 
I'm calculating the peak amplitude, time duration, frequency of each word.

The results are then exported to a csv file.

# Modules used
1. pydub
2. itertools
3. db_to_float from pydub.util

** I'm using few methods from pydub in my script
Instead of using the following methods directly from pydub package, I'm using their implementation so as to tweek some of its functionality to get my results.
Following are those methods:
1. split_on_silence
2. detect_nonsilent
3. detect_silence
