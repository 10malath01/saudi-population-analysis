# Saudi Arabia Population Analysis

## Team Information

| Student | Student ID |
|---|---:|
| Yara Muhammad Al Muzhar | 448815896 |
| Maram Al-sunaidi | 448815727 |
| Thikra Ali Alshahrani | 448815965 |
| Yomn Ali Alsultan | 448816841 |

**Course:** Practical Data Science  
**Instructor:** Anado Havli

## Project Title

**Population Distribution by Administrative Region and Gender in Saudi Arabia (2010–2024)**



## Colab URL:
https://colab.research.google.com/drive/1ph_2EFaICLdLwsbbVeSt3sclAEjrUNdz?usp=sharing


## Data question

How has the estimated population changed by gender over time, and how do Saudi administrative regions compare in the latest available year?

## Dataset

The project uses the **Population by Administrative Region and Gender** dataset from the KAPSARC Data Portal. The portal identifies the creator as the **Saudi Central Bank (SAMA)**, country as Saudi Arabia, and coverage as 2010–2024. The values are mid-year population estimates.

Direct download URL used by the notebook:

`https://datasource.kapsarc.org/api/explore/v2.1/catalog/datasets/saudi-arabia-population-by-administrative-region-nationality-and-sex/exports/csv?lang=en&timezone=UTC`

The source page is:

`https://datasource.kapsarc.org/explore/assets/saudi-arabia-population-by-administrative-region-nationality-and-sex/`

## Project files

- `notebooks/saudi_population_analysis.ipynb`: complete Jupyter/Colab notebook.
- `requirements.txt`: required Python packages.
- `data/`: downloaded and cleaned data will be saved here after execution.
- `outputs/`: aggregated CSV files, a JSON summary, and three figures will be saved here after execution.


## Cleaning and transformation performed

The code selects the analytical columns, renames them, converts year and population to numeric types, trims text values, removes missing or invalid population records, removes duplicates, and sorts the data. It then creates three aggregated outputs: trend by gender and year, latest-year totals by region, and latest-year gender shares by region.

## Visualizations

1. National population trend by gender.
2. Population comparison across administrative regions in the latest available year.
3. Gender composition percentage by region in the latest available year.

## Important limitation

These are population estimates. The analysis is descriptive and shows trends and differences; it does not prove that gender or region causes population changes.

## Citation

For this project, We cite the data source as:

> Saudi Central Bank (SAMA), *Population by Administrative Region and Gender*, accessed through the KAPSARC Data Portal, 2010–2024. https://datasource.kapsarc.org/explore/assets/saudi-arabia-population-by-administrative-region-nationality-and-sex/
