# ligafy_flow_analysis_git_repo
Data analysis for the Ligafy manuscript
## Prerequisites:
This data analysis is in a series of Jupyter notebooks.
To run the notebooks, you will need to install the following Python packages:
- https://github.com/djross22/flowgatenist
- https://github.com/djross22/gsf_ims_fitness

Follow the installation instructions for gsf_ims_fitness to install the correct versions of the folowing packages:
- matplotlib, version 3.7.2
- numpy, version 1.25.1
- pandas, version 1.5.3
- scipy, version 1.11.1
- cmdstanpy, version 1.1.0

## Data Analysis Pipeline:
First run the analysis notebooks for each flow cytometry dataset, in order.
For example, in the folder `/2023-08-24_12-plasmids_4-ligands_Cytom/plate_1/Jupyter notebooks`, run these notebooks in order:
```
01_Auto Gating.ipynb
02_Beads Fit and Background Subtract.ipynb
03_Plots and output.ipynb
```

Repeat for all cytometry datasets.

Then, in the folder `/Plot and fit all cytometry data`, run the following notebooks for the Hill equation fitting and plot gneration:
```
Plot and fit cytometry data.ipynb
Dose response plots for each sensor.ipynb
Cytometry histogram plots.ipynb
```
