# Beyond Hydrology: Shaping Sustainable Future with Intuitive Water Risk Metrics

This project is a data visualization exploration aimed at understanding global water risks using intuitive metrics. It investigates water risk across various sectors and regions, combining data from hydrological indicators and future projections of water management costs. It was developed as part of the **Data Visualization and Exploration course** at the **Free University of Bozen-Bolzano**.

## Project Overview

The goal of this project is to analyze water-related risks at a global scale using visual analytics. The analysis focuses on different economic regions and sectors, utilizing datasets from the World Resources Institute to assess both current risks and future costs associated with water management.

The datasets analyzed include:

Aqueduct 4.0: A dataset providing long-term, chronic trends in water-related risks (1979-2019).
Projected Costs for Sustainable Water Management in 2030: Used to estimate future costs needed to manage water sustainability effectively.

- **Aqueduct 4.0**: A dataset providing long-term, chronic trends in water-related risks (1979-2019).
- **Projected Costs for Sustainable Water Management in 2030**: Used to estimate future costs needed to manage water sustainability effectively.

## Directory Structure

```
├── data/                               # Directory for storing datasets and input files
├── renv/                               # Virtual environment folder created with renv
├── README.md                           # Project README file
├── renv.lock                           # Lock file for environment dependencies
├── Final Project.Rproj                 # RStudio project file
├── Project_Arianna_Tessari.qmd         # Quarto Markdown file containing the analysis
├── Project_Arianna_Tessari.pdf         # PDF version of the final report
├── styles.css                          # Custom CSS for styling the HTML report
```

## How to Run

**1. Clone the repository**
```
git clone https://github.com/artessari/DataVisualizationProject_water-risk
cd DataVisualizationProject_water-risk
```

**2. Install Dependencies**









## Key Steps in the Analysis

1. Data Cleaning and Preprocessing:
- Removed missing values and standardized the dataset for further analysis.
- Selected key water risk indicators such as:
    Physical Risk (Quantity and Quality)
    Regulatory and Reputational Risk
    Overall Water Risk

2. Exploratory Data Analysis:
- Descriptive statistics were calculated for water risk scores across different regions and sectors.
- Visualizations such as boxplots and density distributions were used to highlight water risk variations.

3. Geospatial Analysis:
- Merged country-level risk data with geographical data from the rnaturalearth R package to visualize global water risk on maps.
- Created maps showing regions with the highest and lowest water risk scores, highlighting hotspots in Africa, South Asia, and Latin America.

4. Risk Indicators by Sector:
- Compared water risks across key economic sectors including:
    Agriculture
    Energy Production
    Manufacturing
- Assessed which sectors face the highest risks in different regions.

5. Analysis of future projection











## Conclusions

This project highlighted the crucial importance of making complex hydrological data more accessible and understandable. Through the application of visualization techniques, complex information could be translated and subsequently visualized into clear and intuitive risk indicators, facilitating understanding and informed action. In a context of increasing awareness of water-related risks, evidence suggested that the level of risk varies significantly between regions, with more developed areas generally having a lower risk than developing regions. But not only that, there are also differences between econ

However, no region is completely immune to water challenges, which underlines the importance of addressing these problems in a comprehensive and coordinated manner. Furthermore, the second phase of the analysis focused on understanding the costs associated with sustainable water management. It was found that even in regions with lower water risk, significant costs can arise, highlighting the need for a holistic and adaptive approach to addressing water-related challenges.

Ultimately, these findings can provide valuable insights into the measures needed to ensure a sustainable future for water resources globally. They underscore the urgency of targeted policies and investments that take into account regional specificities, as the world prepares to tackle the increasingly pressing challenges that climate change and global development pose to water supply and water security.

### References

- Kuzma, S., M.F.P. Bierkens, S. Lakshman, T. Luo, L. Saccoccia, E. H. Sutanudjaja, and R. Van Beek. 2023. "Aqueduct 4.0: Updated decision-relevant global water risk indicators." Technical Note. Washington, DC: World Resources Institute. Available online at: doi.org/10.46830/writn.23.00061.

- Lehner, B., and G. Grill. 2013. "Global River Hydrography and Network Routing: Baseline Data and New Approaches to Study the World's Large River Systems." Hydrological Processes 27 (15): 2171-86.

- World Resources Institute. 2023. "Achieving Abundance: Understanding the Cost of a Sustainable Water Future Data." Available online at: https://www.wri.org/data/achieving-abundance-understanding-cost-sustainable-water-future-data

- World Resources Institute. 2023. "Aqueduct 4.0 Current and Future Global Maps Data." Available online at: https://www.wri.org/data/aqueduct-global-maps-40-data#download-form