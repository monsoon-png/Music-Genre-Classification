This repository contains a collection of Jupyter notebooks for audio processing, feature extraction, and genre classification:
### Data Processing
**`audio_extract.ipynb`**
Used to load .wav files from the dataset and process the raw audio data, saving them as `X_data.npy`, `y_Genres.npy` and `file_names.npy`. 

### Feature Extraction
**`feature_extraction.ipynb`**
Extracts a variety of audio features, such as MFCCs, spectral features, and chroma features. Saved as `extracted_features.csv`.

**`feature_extraction2.ipynb`**
Extracts additional features beyond the initial set to explore their impact on model performance. Saved as `features_with_all_extracted.csv`.


### Visualisation

**`Waveplots.ipynb`**
Plots example waveforms for one track from each genre to visualize their structure. Saved in the `wavplots` folder.

**`Featuresplot.ipynb`**
Visualizes different audio features to analyze and compare genres. Saved in the `plots` folder. 

**`mfcc_transformation.ipynb`**
Demonstrates the transformation of a .wav file into an MFCC through intermediate visualizations like spectrograms and mel spectrograms. Saved in the `mfcc_transformation` folder. 

### Analysis and Modeling

**`eda.ipynb`**
Conducts exploratory data analysis (EDA) on the extracted features.

**`model_training1.ipynb`**
Implements training and testing for several machine learning models using the initial feature set.

**`model_training2.ipynb`**
Documents experiments with models using the expanded feature set. Note: This approach was discontinued due to inferior performance compared to the original feature set.
