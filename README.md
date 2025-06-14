# BHS_trRSA_project
Practicing trRSA with the existing dataset (https://osf.io/xz8jr/).

## Features
The repository contains all the data from the original resources (https://osf.io/xz8jr/), as well as the Jupyter notebooks for analysis.

A standard pipeline and details of RSA is discribed in the pdf file.

The folder contains the PREPROCESSED EEG data
The electrode positions have been transposed as explained in the manuscript from the original paper.

### File names' ragularity
XX_RSA_indi.ipynb: XX is the number of subjects. This Jupyter notebook contain the analysis pipeline and results of each participant. 

RSA_group.ipynb: analysis results of group-level tr-RSA.

Behavioral data is the Behavioral_variables.mat file (aggregated data per participant, containing SDT measures d' and c).

Channels_clusters.png: location of EEG sensors.

EEGdata.zip: raw data downloaded from OSF.(SEE UPDATES)

preproc(folder): it contains the preproccessed EEG data(after unzip the file).

preprocess.m: preprocessing method from the original paper.


# updates
it seems like the EEGdata.zip file is too large to upload, so there's no such a file in this repository. One can get the full data set from OSF.
