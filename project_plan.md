# Refined Project Ideas
### Lillian Carlson
**Title:** Language and Accent Identification

**Summary:** Can a model identify language spoken and even bilingual/monolingual speakers?

**Corpus:** I plan to use the same corpus as identified earlier, the [RUEG Corpus](https://zenodo.org/records/3765218).

**Plan:** Although it's a large corpus, I only plan to use the monolingual and bilingual data. For this, I want to train a model with more advanced machine learning techniques. I want to train the model on the audio files to see if identification of language, and even accent is detectable. I'd will also compare the formality in the identification and a few other factors (such as age, location of speaker/how long in either language-speaking country) to see if that effects how accurate the model can be. There are a few tools I will try out in terms of audio file reading like the scipy wavfile method, librosa, pyAudio, or Tensro Flow and PyTorch (deep learning methods).

Some things I'd like to continue to look into are libraries for loading the data, python libraries with praat, and maybe an ESL/DSL corpus to compare. Additionally, I'd like to read some publications about the data to understand what has already been done. As a note, I have to look for speech and text alignment within the data.