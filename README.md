# P5_uppsala
 Use of biochar in urban environments, a case study in Uppsala South Eastern districts


## Installation
dMFA model based on ODYM - ODYM is not yet available via pip/conda install

Instead, download code source of ODYM, add setup.py and init.py files as suggested by Haasad

Then, in your environment make a pip install -e "path to ODYM folder" (pip install --help > explains what option -e means)
Removed import ODYM_Classes in Odym_functions.py


## Uppsala-SÖS case study

File structure:

	.
    ├── cs_Uppsala_biochar_demand.ipynb                  # dMFA is defined and solved in this jupyter notebook
    │
    ├── data
    │   ├ p_fu_upp-sos.xlsx                              # parameter, activity data for uppsala-sös scenarios
    │   ├ p_lci_biochar.xlsx                             # parameter, biochar data, derived from life cycle inventory of each use
    
   