This subdirectory contains all the code written inn wrangling, exploration, and visualization for the CEWS dataset. Each file contains a note at the beginning outlining what it is, but I will explain here as well, with files detailed by category and in approximate chronological order.

## Initial Exploration

- VicensEDA_v1.ipynb: This is Vicens first attempt at exploratory data analysis. This file is outdated, and was improved upon in VicensEDA_v2 and then again in EricExploration.
- VicensEDA_v2.ipynb: The exploration done in this file did not account for the atypical structure of the CEWS dataset, and most of the results are incorrect due to double counting. The wrangling done here was incorrect, and improved upon in EricWrangling.ipynb.

## Wrangling
- EricWrangling.ipynb: This is the main code used to generate the initial CEWS dataset we used.
- cews_wrangling_v2.ipynb: This file was used to update the previous CEWS dataset. We merged the worker count datasets and added a column for province name. The dataset generated from this file is what was used in the final CEWS report.
- cews_wrangling_for_powerbi.ipynb: A slightly altered dataset for the PowerBI dashboards was made here. Just some minor nomenclature changes were made, as it was easier to do in Python than to manually change titles and factor level names in PowerBI.

## Exploration and Visualization
- EricExploration.ipynb: Eric's first attempt at data exploration and visualization. Nothing from this was actually used in the report.
- VicensExploration.ipynb: Vicens first attempt at Visualizations. Nothing from this file was used in our final report.
- EricReport.ipynb: An intermediate step of Erics exploration. 
- VicensRural.ipynb: Vicens almost final notebook.

## Final Visualizations
- final_cews_report.ipynb: This notebook contains all of Erics finished visualizations, some of which were used in the final report.
- VicensRural-Copy.ipynb: Contains Vicens finished visualizations, which were edited by Eric to have color schemes consistent with his visualizations. Some of these visuals were used in the final report.
