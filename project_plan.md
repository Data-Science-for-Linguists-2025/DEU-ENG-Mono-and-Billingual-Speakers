# Refined Project Ideas
### Lillian Carlson
**Title:** Language and Accent Identification

**Linguistic Questions:** Are Bilingual and Monolingual speakers identifiable? What features are more common in which groups of speakers? What features are more common in spoken or written language productions and how does the language of production change this?

**Corpus:** I plan to use the [RUEG Corpus](https://zenodo.org/records/3765218).

**Plan:** Although it's a large corpus, I only plan to use the English and German data. For this, I will be utilizing the conll format of the data to create a machine learning model that can take such a format and classify/label a given conll format. Ideally, this model is similar to a Naive-Bayes Classifier so I can pick out and analyze specific features that the model identifies as relevant, however I will go with whatever is best suited for the data input.

I will be analyzing the linguistic difference between these different groups of speakers to find linguistic differences that can be used as features in a classifier model. 

In terms of the audio file usuage, there are a few tools I will try out in terms of audio file reading like the scipy wavfile method, librosa, pyAudio, or Tensro Flow and PyTorch (deep learning methods).

Some things I'd like to continue to look into are libraries for loading the data, and more python libraries compatable with praat (speech and text alignment). Additionally, I'd like to read some publications about the data to understand what has already been done.