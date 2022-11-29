[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9156172&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/27410-group-assigment-group_3/main)

# 27410 - Group assignment - Group 3 - Progesterone production in *S. cerevisiae*



> For this to work you will also have to keep `requirements.txt` up to date (by running `pip freeze > requirements.txt`).
> Furthermore, this will only work if you decide to make your repository public (which you can do under Settings -> Options),
> which I would encourage you to do – up to you. A lot of good science happens out in the open these days.
> Good luck!

## Project summary (<300 words)
We implemented the heterologous pathway producing the steroid hormone progesterone in the host organism *S. cerevisiae*. Progesterone is a high-value compound, e.g. used in birth control pills, currently produced heavily as a semi-synthesis reaction. If progesterone can be produced in a cell factory, it would create a sustainable "green" production, meaning that this implementation is a step in the direction of ensuring a sustainable and healthy future for all. The project is organized as follows; First, the implementation and characterization of the heterologous pathway for the production of progesterone. This includes the pathway implementation, calculating maximum yield, and performing a phenotypic phase plane analysis using cameo. The second part is concerned with our cell factory engineering strategies and involves manually knocking out relevant genes based on literature reviews, as well as performing gene target analysis to locate other relevant genes that can be knocked out, or up- or downregulated, and a co-factor swap analysis for better performance of the strain. The last part assesses the strains computed in this project and evaluates them using several factors. In the end, we succeeded with implementing the pathway producing progesterone and improving it using simulations.

## Project overview
- The report for the project can be found in the 'Report.ipynb' file. 
- The required environment needed to run the scripts is located in the 'requirements.txt' file.
- All figures/images used are located in the 'figures' folder.
- All models used are located in the 'models' folder.
- The code for the report is split up into 8 .ipynb files, which are linked to in the main report:
    - 01_GSM_Comparison.ipynb
        - Comparison of 4 GSMs and the parameters we chose our GSM from.
    - 02_heterologous_pathway_implementation.ipynb
        - Contains the code needed to implement the heterologous pathway.
    - 03_maximum_theoretical_yield.ipynb
        - Calculations of maximum yield and productivity on default and alternative carbon sources.
    - 04_phenotypic_phase_plane_analysis
        - A phenotypic phase analysis examining the relationship between parameters e.g. between glucose and oxygen uptake rates.
    - 05_gene_target_analysis.ipynb
        - Analysis of potential gene target for up- or downregulation to improve production.
    - 06_co-factor_swap.ipynb
        - Swap of reaction using NAD co-factor -> NADP co-factor to improve productivity of progesterone.
    - 07_DFBA
        - Dynamic flux balance analysis to mimick "real-life" conditions.
    - 08_strain_assessment.ipynb
        - The final assessment of computed strains and evaluation of top 10 best performing strains
- In addition, the .json and .csv files loaded in the online version Escher to create the heterologous pathway map can be found as 'model.json' (a .json file containing the model) and flux.csv (a .csv file containing the simulated fluxes).
    
