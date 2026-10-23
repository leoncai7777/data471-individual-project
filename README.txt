DATA471 Individual Project: Does Urban Status Reverse the Poverty-Income Effect on Low Food Access?
======================================================================

AUTHOR
------
  Leon Cai (300692424)


FILES
-----
  individual_report_leon.qmd : full source -- data loading/cleaning, EDA,
                                and all models (M0-M3), interleaved with
                                the report text
  individual_report_leon.pdf : rendered report


REQUIREMENTS
------------
  - R, Quarto, lualatex
  - R packages: dplyr, tidyr, ggplot2, knitr, broom, patchwork, car,
    ResourceSelection, randomForest, pROC, scales


DATA
----
  Not included in this repository (assignment brief: code submissions must
  not include data files). To re-render, place the public USDA Food Access
  Research Atlas (2019) CSV at:

    data/2019/2019_Food_Access_Research_Atlas_Data/Food Access Research Atlas.csv

  Source: https://www.ers.usda.gov/data-products/food-access-research-atlas/


HOW TO RUN
----------
  With the CSV in place, from this directory:

    quarto render individual_report_leon.qmd
