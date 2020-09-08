# EEGrunt: A Collection Python EEG (+ECG) Analysis Utilities

### [READ THE ANNOUNCEMENT POST &raquo;][1]

Working with EEG (electroencephalography) data is hard, and this little library aims to make it easier. EEGrunt consists of a collection of functions for reading EEG data from CSV files, converting and filtering it in various ways, and finally generating pretty and informative visualizations.

**Update:** We’ve added functions to plot heart rate and heart rate variability from recorded OpenBCI ECG (electrocardiography) data. You can test these out with the `analyze_ecg_channel.py` and `analyze_ecg_data.py` demo scripts. We’ve posted a new tutorial on our blog to get you started: **[EEGrunt update: Analyze heart rate and HRV with Python][2]**


## Features

1. EEGrunt is compatible with data from OpenBCI and Muse.

2. EEGrunt has bandpass, notch, and highpass filters for cleaning up powerline interference, OpenBCI's DC offset, and zeroing in on the frequency band you want to analyze.

3. EEGrunt makes it easy to generate signal plots, amplitude trend graphs, spectrograms, and FFT (fast-fouier transform) graphs, etc.

 
