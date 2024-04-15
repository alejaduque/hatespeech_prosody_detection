# hatespeech_prosody_detection
This project is oriented towards determining whether hate speech can be detected through prosodic features in speech.

# # What will I find in this repo?

* Data (file): In this file you will find the following content:

 - audio_cuts (file): 2-minute lenght version of the samples. 

 - clean_audio (file): files containing with 2 .wav files for each sample, voice (voice of speaker) and accompaniment (background). 

 - raw_audio (file): .mp3 files of the audio (extracted with code from pre_processing_audios.ipynb). 

 - spanish_dataset (file): .mp4 videos extracted with video_scraping.ipynb code.

 - data_spanish_dataset.csv --> all the information about our dataset, including title of each video, lenght, number of views, and url. 

 - keywords_search_spanish.txt --> list of keywords used for finding the videos. 

 - video_scraping.ipynb --> code for extracting videos from Youtube.

* pre_processing_audions.ipynb --> code use for extracting, cutting and cleaning data. 

* requirements.txt --> all requirements for running this code.