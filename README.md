# Exploring the role of prosodic information as a modality in hate speech detection (Repository)

 
This project is oriented towards determining whether hate speech can be detected through prosodic features in speech. 

In this project, we use Youtube videos in Spanish to extract its audio and use it to observe the prosodic features from the speech of the interlocutors. This repository contains all the material and code used in the methodology for my master's final project. 

For copyright reasons, the videos and audios we scraped are not contained in this repository. However, you will be able to find datasets that enlist all the videos analyzed in this work, along with information about their origin, views and description (see datasets in data folder). 

If you wish to see the playlists with the videos we scraped, here are the links to both playlists: 

- First sampling: https://youtube.com/playlist?list=PLh0970rfsSfHwQNUkHwbUCNXk98dB4qiz&si=WQCf61HrN7Bf6L72
- Hate speech samples (Sampling extension): https://youtube.com/playlist?list=PLh0970rfsSfEljdgUjiO1f8pdU47rKeP_&si=bGVKHwyVF_CVg6Ay
- Non-hate speech samples (Sampling extension): https://youtube.com/playlist?list=PLh0970rfsSfHrs4HjmuUwK6OxFFv8BAWv&si=iiO4Me7pWJphzgPs

# What will I find in this repo?
The following list describes the content of this repository. Here, we organize our files in folders to access the data, clean it and train our models. We have organized it as it is shown to access our data more effectively with our code. 

### Files in main 

* CNN_classifier.ipynb --> (failed) test for using a CNN as a classifier.
* CNN_overfitting.ipynb --> code for overfitting data with a CNN.
* SVM_model.ipynb --> code for SVM model used in this project.
* exploratory_analysis.ipynb --> code for exploratory analysis.
* pre_processing_audions.ipynb --> code use for extracting, cutting and cleaning data.
* rename_files.ipynb --> code use for ennumerating and replacing the name of the original scraped videos (as they had their actual titles as file names).
* requirements.txt --> all requirements for running this code.
* spectrogram_generator.ipynb --> code use for generating the spectrograms. 
  
### Data (folder)
  
-  datasets (folder) --> CSV files that contain the generated dataframes of the scraped videos.
-  spectrograms (folder) --> PNG files with the spectrograms generated with the audio samples.
* edit_dataframes.ipynb --> Code used to change nominal labels, "hate" and "non-hate", to numerical data.
* keywords_search_spanish.txt --> list of keywords used for finding the videos.
* labels_extension.txt --> labels for all the scraped videos. 
* video_scraping.ipynb --> code for extracting videos from Youtube.


