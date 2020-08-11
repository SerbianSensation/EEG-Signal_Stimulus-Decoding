# EEG-Signal_Stimulus-Decoding
Contains experiments and other files from my research done during the 2020 Texas State Computer Science REU.

This repository contains all of the notebooks from my research of EEG Signal Analysis for Stimulus Decoding during the summer of 2020. These notebooks were written in Google Collab and are ready to be run. All that is needed that is not included in the notebooks is the actual dataset, which can be obtained through the owner Kevin LaBar. This dataset included 24 participants looking at images containing the four stimuli: static fear, static anger, dynamic fear, and dynamic anger. For each stimulus, up to 72 trials were recorded for each user.

Each notebook contains comments describing the different experiments. To summarize, each of the notebooks contains different versions of experiments to decode the stimuli of the EEG signals in the dataset using deep learning algorithms provided by TensorFlow. 1D-CNN and LSTM models were used to attempt to classify the data, along with other techniques such as transfer learning and scaling.

The conclusion was made that fear and anger stimuli were to closely related to be accurately classified by deep learning models. The highest average accuracy achieved by these models was 60%. Visualizations to support this conclusion can be seen in the repository containing the dataset called 'Visualizations.'
