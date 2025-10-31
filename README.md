### Techno-economic assessment for non-aqueous CO<sub>2</sub>R

**Cite this work** : 
> Da Cunha, S.; Resasco, J. Techno-economic assessment of non-aqueous CO2 reduction. Chem Catalysis 2025. DOI: [10.1016/j.checat.2025.101548](https://doi.org/10.1016/j.checat.2025.101548)

This tool generates the capital and operating cost for a CO₂ reduction process converting captured CO₂ into either CO or oxalic acid in non-aqueous electrolytes. It also generates figures for our [2025 paper](https://doi.org/10.1016/j.checat.2025.101548).

For similar assessments in aqueous electrolyte, check out the [CO<sub>2</sub>R Costing Dashboard web app](https://co2r-dashboard.streamlit.app/). You only need this repository if you want to see and run the raw model. Fork or download/clone the entire repository - none of these notebooks run independently. Get started by running all of `<version>_4_TEA_Integrated.ipynb` - it will prompt you to interact and set up the figures you want.

**Figure generation and analysis**

"Front end" notebook for figure generation, data analysis, saving results to Excel files: `<version>_4_TEA_Integrated.ipynb`

**Models**

Electrolyzer: `<version>_0_ElectrolyzerModel.ipynb`

Mass and energy balances: `<version>_1_DownstreamProcessModel.ipynb`

Technoeconomics: `<version>_2_ProcessEconomics.ipynb`

Single run execution: `<version>_3_TEA_SingleRun.ipynb`

**Data**

Data for constants, utilities and products: `Supplementary Workbook 1 - TEA inputs.xlsx`


**Other**

License: `LICENSE.md`

Readme: `README.md`

Packages: `requirements.txt` (can be installed with pip, for example)
