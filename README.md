# MMB
These are codes for generating multiscale morpho-barcodes for neurons and comprehensive, associcative analysis between neuronal morphology 
and brain anatomy. This repository is maintained mainly by Sujun Zhao (sjzhao818@seu.edu.cn) from SEU-Allen. <br>

### Prerequisites
* Python. The project is developed under Python 3.10 and should be compatible with Python versions 3.6 and above.
* Common python packages for data processing and visualization, including NumPy, SciPy, scikit-learn, scikit-image, pandas, seaborn, matplotlib, etc.
* neuro_morpho_toolbox. neuro_morpho_toolbox is designed for the analysis of single-cell full morphology reconstruction data, including:
1. Quantification of projection strength.
2. Sub-cellular morphology analysis at arbor level.
3. Visualization of projection map.
The installation and details could be found at https://github.com/pengxie-bioinfo/neuro_morpho_toolbox.

### Structure of the project
project/  
├── clustering_code.ipynb               # generation of MMB  
├── fig3.ipynb                          # analytical code for figure 3
├── fig4.ipynb                          # analytical code for figure 4
├── fig5.ipynb                          # analytical code for figure 5
├── Supplementary.ipynb                 # analytical code for supplementary figures
└── README.md                           # project overview and instructions

### Dataset
All the dataset involved and other materials refer to https://drive.google.com/drive/folders/1aF5njPqDW9v-TX2kQdJ3k5-KzSJ2JyeN.

## Acknowledgement
Special thanks to all contributors and the SEU-ALLEN team for their support in developing this project.
