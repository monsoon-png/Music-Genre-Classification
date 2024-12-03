The repository includes the following notebooks:

audio_extract.ipynb
Used to load .wav files from the dataset and process the raw audio data.

Waveplots.ipynb
Plots example waveforms for one track from each genre to visualize their structure.

feature_extraction.ipynb
Extracts a variety of audio features, such as MFCCs, spectral features, and chroma features

Featuresplot.ipynb
Visualizes different audio features to analyze and compare genres.

mfcc_transformation.ipynb
Demonstrates the transformation of a .wav file into an MFCC through intermediate visualizations like spectrograms and mel spectrograms.eda.ipynb

eda.ipynb
Conducts exploratory data analysis (EDA) on the extracted features

model_training1.ipynb
Implements training and testing for several machine learning models using the initial feature set.

feature_extraction2.ipynb
Extracts additional features beyond the initial set to explore their impact on model performance.

model_training2.ipynb
Tests models with the expanded feature set. This approach was abandoned due to worse performance compared to the original feature set.
