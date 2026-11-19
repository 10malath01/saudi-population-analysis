# Saudi Arabia Population Analysis

An exploratory data science project examining Saudi Arabia’s mid-year population estimates by gender and administrative region from 2010 to 2024.

**GitHub repository:** https://github.com/10malath01/saudi-population-analysis/  
**Google Colab notebook:** https://colab.research.google.com/drive/1ph_2EFaICLdLwsbbVeSt3sclAEjrUNdz?usp=sharing

---

## Project Information

- **Project title:** Population Distribution by Administrative Region and Gender in Saudi Arabia (2010–2024)
- **Course:** Practical Data Science
- **Course code:** 2323 CIS
- **Instructor:** Anado Havli

## Team

| Student | Student ID |
|---|---:|
| Yara Muhammad Al Muzhar | 448815896 |
| Maram Al-sunaidi | 448815727 |
| Thikra Ali Alshahrani | 448815965 |
| Yomn Ali Alsultan | 448816841 |

### Proposed Contribution Allocation — Pending Team Confirmation

The following responsibilities are a proposed division based on the project workflow. Each team member should confirm or amend this record so that it reflects the actual work completed.

| Student | Proposed responsibilities |
|---|---|
| Yara Muhammad Al Muzhar | Project planning; defining the research question and objective; identifying and documenting the dataset source. |
| Maram Al-sunaidi | Downloading and inspecting the data; reviewing its structure and quality; cleaning and preparing the analytical dataset. |
| Thikra Ali Alshahrani | Transforming and aggregating the cleaned data; preparing summary tables; creating and interpreting the visualizations. |
| Yomn Ali Alsultan | Organizing the notebook and project files; documenting the workflow and requirements; preparing the GitHub repository; coordinating the final review and presentation. |

---

## Research Question

How has the estimated population changed by gender over time, and how do Saudi administrative regions compare in the latest available year?

## Project Objective

The objective is to prepare population data, describe national trends and regional differences, and communicate the findings through summary tables, visualizations, and a reproducible Python notebook.

This is a descriptive analysis. It summarizes patterns in the published estimates; it does not determine the causes of population changes.

---

## Dataset and Source

The project uses the **Population by Administrative Region, Nationality and Sex** dataset available from the KAPSARC Data Portal. The portal identifies the Saudi Central Bank (SAMA) as the dataset creator. The dataset covers 2010–2024, reports values in persons, and describes them as mid-year estimates based on the Demographic Research Bulletin 2016.

- **Dataset page:** https://datasource.kapsarc.org/explore/assets/saudi-arabia-population-by-administrative-region-nationality-and-sex/
- **CSV export endpoint used by the notebook:**

  `https://datasource.kapsarc.org/api/explore/v2.1/catalog/datasets/saudi-arabia-population-by-administrative-region-nationality-and-sex/exports/csv?lang=en&timezone=UTC`

The analysis focuses on year, region, gender, and population. The project does not analyze nationality.

---

## Project Structure

```text
saudi-population-analysis/
├── README.md
├── requirements.txt
├── data/
│   ├── README.md
│   └── ... cleaned project data
├── notebooks/
│   └── saudi_population_analysis.ipynb
└── outputs/
    ├── README.md
    ├── ... summary tables and analysis outputs
    └── figures/
        ├── 01_population_trend_by_gender.png
        ├── 02_population_by_region_latest_year.png
        └── 03_gender_composition_by_region.png
