# Progress Reports
## Progress Report 0
#### 2/10/25 Lillian Carlson
I have started the repository and set up the outline of the repository. It currently has a README, a LICENSE (that is currently undecided), and a project plan.
## Progress Report 1
#### 2/26/25 Lillian Carlson
I have loaded in the corpus and have two data frames
- one dataframe containing all the meta data (more details found in the jupyter notebook file linked below)
- one dataframe containing the raw ConLL data, a more readable format of the ConLL data, the transcription by parsing the conLL data, and  the raw audio file 

The process of developing these dataframes can be found [here](https://github.com/Data-Science-for-Linguists-2025/DEU-ENG-Mono-and-Billingual-Speakers/blob/main/LoadingRUEGData.ipynb)

This file also contains more metrics about the data such as the size, makeup, and more specific metrics about the contents (how many spoken/written data, how much formal/informal data, adolescent/adult data, and the heritage langauge distribution) 

Things to continue to accomplish: find more substantial ESL (English as a Second Language) or DSL (German as a Second Language) resources- a lot of what I have been finding has only been a handful of audio files and I want more to fully compare. I also want to organize the dataframe a little bit more in terms of sorting tokens and token, POS touples, size, ect.

Data Sharing: I plan to share all of the relevant corpus in my repo, as it is free for distribution, but I will be thoroughly scanning the license and working out the legal jargon to ensure that this is allowed. 

## Progress Report 2
#### 3/21/25 Lillian Carlson
It may not look like a whole lot has changed, but a lot has happened behind the scenes. I've continuted working [here](https://github.com/Data-Science-for-Linguists-2025/DEU-ENG-Mono-and-Billingual-Speakers/blob/main/LoadingRUEGData.ipynb) to develop dataframes, however I discovered that in order to keep all the syntactic information represented in conll format, I should be using a conll parser. I chose the spacy conll library, but I was really stuck because of a very minor issue in many of the documents (quite literally, an extra newline character- so frustrating! and a HUGE thanks to Na-Rae for helping me figure this out). I have mostly been working on plaing with the conll format and cleaning some of the data that isn't written in the correct format. My script has continued to be in the same Jupyter Notebook as I continue working with the ConLL data format, however when I start more linguisitc explorations to the data I will be creating a new script.

For the mean time, I will continue data cleaning and exploring my data linguistically to discover features that are more or less common within the different groups of speakers.

Future Goals:
- Explore the data more and find more differences in the data through linguistic inquiry
- As of right now, I will still include speech data, but I am still a ways away from incorporating that into the project as my hands have been full with conll and that is a beast of its own.


Some other changes to my project
- I will no longer be including an ESL or DSL corpus. For my current project plan and goals, it doesn't make a lot of sense for me.
- After reading up on a CC0 license, I can publish the whole Dataset, however I will not because it is about 7GB and git does not want to push that. This is also to hope to keep my repo small. I have added data samples, however, and that is enough for me.
- Researched licenses to reflect how I want my work to be shared
- Additionally, I've updated my [project plan](https://github.com/Data-Science-for-Linguists-2025/DEU-ENG-Mono-and-Billingual-Speakers/blob/main/project_plan.md) to reflect my current goals after working with the data for a while now.

## Progress Report 3
#### 4/6/25 Lillian Carlson
I had a lot of forward progress, but a LOT of backward progress here. I had to pivot (much later than I would have liked) to the stanza library after trying to wrestle with spacy for far too long. Luckily, that's sorted now and I've really begun to work and focus on exploring my data.

As of right now, for what I am anticipating to explore, all the data processing is complete and I have lists of POS and token unigrams, bigrams, and trigrams pickled and have begun to explore them.

So far with my exploration, I've found some interesting differences between stopword usuage between the languages. I have not spotted any glaring differences between bilingual and monolingual speakers, which is to be expected as I can't imagine much difference between heritage speakers of multiple languages. I will begin machine learning to uncover something that the human eye can't see, but perhaps algorithms can.

Some changes to my project:
- My [license](https://github.com/Data-Science-for-Linguists-2025/DEU-ENG-Mono-and-Billingual-Speakers/blob/main/LICENSE.md) is now fully updated and finished with unigrams, bigrams, and trigrams of POS marking and tokens
- My [jupyter notebook](https://github.com/Data-Science-for-Linguists-2025/DEU-ENG-Mono-and-Billingual-Speakers/blob/main/LoadingRUEGData.ipynb) on loading and processing the data is essentially finished and I have begun to work in [this one](https://github.com/Data-Science-for-Linguists-2025/DEU-ENG-Mono-and-Billingual-Speakers/blob/main/ExploringRUEGData.ipynb) to explore the data
    - When I eventually get to speech data, I will likely create a different notebook altogether
