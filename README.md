# menarche_classification

This repository stores code and analyses for the [preprint](https://www.medrxiv.org/content/10.1101/2023.08.31.23294880v1) entitled 

> *Menarche, pubertal timing and the brain: female-specific patterns of brain maturation beyond age-related development*

Before running the code, please make sure to set up a new conda environment first:

+ conda create --name <env> python=3.11.5
+ conda activate <env>
+ pip install -r requirements.txt
+ Make sure to activate env for all analyses within this repo: conda activate <env>

# Order of operations

To execute this code, access to tabulated Adolescent Brain Cognitive Development (ABCD) data, to be stored in the folder "ABCD_tabulated", as well as to Philadelphia Neurodevelopmental Cohort (PNC) MRI data parcellated with FreeSurfer, to be stored in the folder "regularFSstats", is required. 

The jupyter notebooks are numbered according to the order that they should be excecuted in. The individual scripts build upon each other, the output of one script being the input of the next. Any plots will be saved to the Plots directory, and data will be stored in the processedData directory after every processing step.

