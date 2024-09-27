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

## Key Files

- **Final Project.Rproj**: RStudio project file that allows you to open and manage the project directly in RStudio.
- **Project_Arianna_Tessari.qmd**: The main Quarto document containing the complete analysis, including data cleaning, visualizations, and conclusions. This file can be rendered to HTML, PDF, or other formats.
- **Project_Arianna_Tessari.pdf**: PDF version of the final report, summarizing the project's findings and useful for sharing or presentation.
- **data/**: Directory containing all datasets and input files used in the analysis, organized for easy access and management.
- **renv/**: Folder created by the `renv` package, containing the R environment setup for the project, which ensures that all dependencies are consistent and reproducible.
- **renv.lock**: Lock file for managing package versions used in the project, allowing for the recreation of the same R environment.
- **styles.css**: Custom CSS file used to style the HTML report when rendered from the Quarto document.

## How to Run

1. **Clone the repository**
```
git clone https://github.com/artessari/DataVisualizationProject_water-risk
cd DataVisualizationProject_water-risk
```

2. **Install R and RStudio**: Ensure that you have R version 3.6.0 or higher and RStudio installed on your machine. 

3. **Set Up the R Environment**: Use the `renv` package to recreate the project's R environment. Run the following commands in R:
```
<<<<<<< HEAD
install.packages("renv")    # Install renv if you haven't already
renv::restore()             # Restore the R environment from the lock file
=======
install.packages("renv")  # Install renv if you haven't already
renv::restore()            # Restore the R environment from the lock file
>>>>>>> origin/main
```

4. **Open the RStudio Project**: Open the project in RStudio by double-clicking on the Final `Project.Rproj` file. This will load the project settings and associated files.

5. **Render the Quarto Document**: To run the analysis and generate reports, render the Quarto file `Project_Arianna_Tessari.qmd`.

### Additional Notes
- Ensure that all necessary R packages are installed, as specified in the `renv.lock` file.
- For visualization purposes, you may need to install additional libraries like `ggplot2` and `sf` if not already included in the environment.

## Key Steps in the Analysis

1. Data Cleaning and Preprocessing:
- Removed missing values and standardized the dataset for further analysis.
- Selected key water risk indicators such as:
    - Physical Risk (Quantity and Quality)
    - Regulatory and Reputational Risk
    - Overall Water Risk

2. Exploratory Data Analysis:
- Descriptive statistics were calculated for water risk scores across different regions and sectors.
- Visualizations such as boxplots and density distributions were used to highlight water risk variations.

3. Geospatial Analysis:
- Merged country-level risk data with geographical data from the rnaturalearth R package to visualize global water risk on maps.
- Created maps showing regions with the highest and lowest water risk scores, highlighting hotspots in Africa, South Asia, and Latin America.

4. Risk Indicators by Sector:
- Compared water risks across key economic sectors including:
    - Agriculture
    - Energy Production
    - Manufacturing
- Assessed which sectors face the highest risks in different regions.

5. Analysis of future projection:
- Explored projected costs for sustainable water management by 2030 and their correlation with water risk levels.

## Visualizations

The following visualizations were created during the project:

## Visualizations

The following visualizations were created to explore global water risks in detail:

- **Global Overview of Water Risks**: This visualization provides a geographic representation of water risks across the globe. It highlights areas with the highest and lowest water risk scores, offering a clear view of regional disparities. Hotspots such as parts of Africa, South Asia, and Latin America emerge as regions with the most severe water risks, while more developed areas show relatively lower risks.

- **Sector-wise Comparison of Water Risks**: This set of visualizations breaks down water risks across key economic sectors, including agriculture, energy production, and manufacturing. Each sector is assessed for its vulnerability to both water quantity (scarcity) and water quality issues. These visualizations help identify which industries are most at risk in different regions, providing insights for targeted interventions.

- **Confidence Interval Plots**: Confidence intervals were plotted to assess the precision of water risk estimates across different regions and sectors. These visualizations provide a statistical layer of insight, helping to identify areas where risk estimates are more uncertain and require further investigation or additional data collection.

- **Density and Box Plots**: These visualizations were used to analyze the distribution of water risks within and across regions. Density plots helped show the concentration of countries or sectors facing specific risk levels, while box plots allowed a comparison of median risks and the spread of data, identifying regions and sectors with the greatest variability in water risks.

- **Projected Costs for Sustainable Water Management**: A key part of the analysis was understanding the future costs of managing water risks. Visualizations were created to compare the projected costs of sustainable water management across different regions by 2030. These graphs show not only the regions where the highest investments will be needed but also the correlation between current water risks and future water management costs.

More visualizations and insights can be found by running the Quarto file.

## Conclusions

This project highlighted the crucial importance of making complex hydrological data more accessible and understandable. Through the application of visualization techniques, complex information could be translated into clear and intuitive risk indicators, facilitating understanding and informed action.

Evidence suggested that the level of water risk varies significantly between regions, with more developed areas generally having a lower risk than developing regions. However, no region is completely immune to water challenges, emphasizing the need for comprehensive, coordinated action.

In the second phase of the analysis, it was found that even regions with lower water risk may face significant costs to achieve sustainable water management. These findings underscore the importance of targeted policies and investments to tackle water-related challenges on a global scale.

### References

- Kuzma, S., M.F.P. Bierkens, S. Lakshman, T. Luo, L. Saccoccia, E. H. Sutanudjaja, and R. Van Beek. 2023. "Aqueduct 4.0: Updated decision-relevant global water risk indicators." Technical Note. Washington, DC: World Resources Institute. Available online at: doi.org/10.46830/writn.23.00061.

- Lehner, B., and G. Grill. 2013. "Global River Hydrography and Network Routing: Baseline Data and New Approaches to Study the World's Large River Systems." Hydrological Processes 27 (15): 2171-86.

- World Resources Institute. 2023. "Achieving Abundance: Understanding the Cost of a Sustainable Water Future Data." Available online at: https://www.wri.org/data/achieving-abundance-understanding-cost-sustainable-water-future-data

- World Resources Institute. 2023. "Aqueduct 4.0 Current and Future Global Maps Data." Available online at: https://www.wri.org/data/aqueduct-global-maps-40-data#download-form