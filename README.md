# ML/Deep Learning Analysis and Model Implementation on Human Activity fMRI Dataset

This machine learning model implementation has been done for LJMU Masters Thesis.<br>
Here we classify sports activity from fMRI data (brain signals) of 180 human activities of various categories like sports, household chores, personal grooming, arts & entertainment etc. activities.<br>
Dataset used: Human Action Dataset https://doi.org/10.18112/openneuro.ds004488.v1.1.1<br>

## Prerequisite Installation
For installation of packages follow below instructions:
(Note: brainiak does not have windows support, works in linux https://pypi.org/project/brainiak/)
- conda create -n fmri_env
- conda activate fmri_env
- conda install -c brainiak -c defaults -c conda-forge brainiak
- python3 -m pip install -U tensorflow tensorflow-probability
- conda install jupyter nilearn ipykernel chardet
- python -m ipykernel install --user --name fmri_env --display-name fmri_env

(For detailed packages list refer fmri_env.yml file in sourcecode zip)
