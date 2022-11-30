[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9156172&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/27410-group-assigment-group_3/main)

# 27410 - Group assignment - Group 3 - Progesterone production in *S. cerevisiae*

## Project summary
During our project, we implemented the heterologous pathway to produce the steroid hormone progesterone, in the host organism *S. cerevisiae*. Progesterone is a high-value compound mainly used as a contraceptive. It is currently produced in s semi-synthetic manner causing a burden to the environment. 
Producing progesterone via biosynthesis in a cell factory is recognized as a promising 'greener' alternative production method. 
The purpose of this project is to design a progesterone-producing cell factory using computational tools.
<!-- If progesterone can be produced in a cell factory, it would create a sustainable "green" production, meaning that this implementation is helps ensure a sustainable and healthy future for all.  -->

The project was organized as follows; First, the implementation and characterization of the heterologous pathway to produce progesterone. This part includes calculating maximum yield and performing a phenotypic phase plane analysis. 
The second part focused on improving the progesterone and biomass productivity. We identified gene targets for knock-outs, up- and down-regulation. Additionally, we implemented a co-factor swapping strategy to improve the co-factor balance. 
The last part assessed the computed strains by evaluating and comparing them through phenotypic simulations.

<!-- finding gene targets for knockadditional cell factory engineering strategies. -->
<!-- including manually knocking out relevant genes based on literature reviews, as well as performing gene target analysis to locate other relevant genes that can be knocked-out, or up- or downregulated, and a co-factor swap analysis for better performance of the strain.  -->

## Project overview
- The report for the project can be found in the 'Report.ipynb' file. 
- The required environment needed to run the scripts is located in the 'requirements.txt' file. For the dynamic flux balance analysis the 'requirements_dfba.txt' file is needed.
- All figures/images used are located in the 'figures' folder.
- All models used are located in the 'models' folder.
- In the 'escher' folder,  the .json and .csv files loaded in the online version Escher to create the heterologous pathway map can be found as 'iMM904_progesterone.json' (a .json file containing the model) and fluxes.csv (a .csv file containing the simulated fluxes).
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

    
