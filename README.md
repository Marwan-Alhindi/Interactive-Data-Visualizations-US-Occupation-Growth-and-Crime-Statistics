### Languages and Tools

- **R**: For creating data visualizations and building interactive web applications.
- **Shiny**: For creating interactive dashboards and applications.
- **ggplot2/Plotly**: For generating plots and interactive graphs.
- **RPubs**: For hosting data visualizations.

# Data Visualization Projects: Occupation Growth and Crime Statistics

## Overview

This repository contains two data visualization projects:

1. **Visualizing Occupation Growth Rate in the US**: A project focused on visualizing the growth rate of occupations in the US and their expected growth rate over the next decade.
2. **Crime Statistics Agency (CSA) Data Visualization**: This project uses data from the CSA in Victoria, Australia, to create interactive visualizations and narrative reports to uncover crime patterns.

### Project 1: Visualizing Occupation Growth Rate in the US

This project visualizes the growth rate of various occupations in the US, as well as their projected annual pay growth over the years 2019-2029. The goal of the project is to make it easy for a non-statistical audience to understand which occupations are growing fastest and how their wages are expected to evolve.

#### Features

1. **Interactive Data Visualization**:
   - The visualizations are available on the RPubs platform.
   - The project allows users to explore the fastest-growing occupations and their corresponding median annual pay.
   - [View the visualization on RPubs](https://rpubs.com/Mrwanz/1034388).

2. **Key Insights**:
   - The data focuses on occupations expected to see significant growth in terms of both employment and salary.
   - Categories include healthcare, IT, operations research, and construction roles.
   - The visual representation was chosen to simplify complex data for public use.

3. **Reconstruction**:
   - The original data visualization had some issues, which were resolved by improving the structure, simplifying the message, and making the visual cleaner and easier to understand.
   - A **Deconstruct-Reconstruct** approach was used to improve the clarity and accuracy of the visualization.

#### Files

- **Code and Reconstruction**:
   - The code used for generating the visualization is available in RMarkdown format (`code.Rmd`).
   - The improved version can be viewed via a Shiny app for better interaction with the dataset.
   - [Explore the interactive app on ShinyApps](https://6csuz1-mrwan-alhandi.shinyapps.io/Assignment3/).

### Project 2: Crime Statistics Agency (CSA) Data Visualization

This project uses data from the Crime Statistics Agency (CSA) in Victoria, Australia. The goal is to create meaningful data visualizations that help communicate trends in crime data to the general public, government officials, and researchers. These visualizations allow users to explore and interpret CSA data interactively.

#### Features

1. **Interactive Crime Data Dashboard**:
   - Interactive visualizations that allow users to explore crime trends by offense type, gender, and year.
   - Narrative data visualization methods were employed to build upon existing CSA reports.
   - The visualizations provide insights into crime patterns across different regions and demographics.

2. **Objectives**:
   - Improve the accessibility of crime statistics for all Victorians.
   - Strengthen the integrity and quality of recorded crime data.
   - Provide tools for data literacy and decision-making support for stakeholders.

3. **Use Cases**:
   - Visualizations and dashboards that help uncover crime trends in specific regions of Victoria.
   - Linking CSA data to other datasets, such as census data, to create compelling narratives around crime statistics.

#### Files

- **Crime Data Visualization Code**:
   - The code for building the dashboard and visualizations can be found in the RMarkdown file (`code1.Rmd`).
   - These visualizations can be customized or extended to add more interactivity based on user input.

### How to Run the Projects

1. **RMarkdown Setup**:
   - Install R and RStudio if you haven’t already.
   - Download the `code.Rmd` and `code1.Rmd` files to your local machine.
   - Ensure that necessary libraries such as `ggplot2`, `plotly`, and `shiny` are installed.

2. **Run Visualizations**:
   - For Project 1, you can either run the `code.Rmd` locally or explore the RPubs and Shiny links provided for interactive versions.
   - For Project 2, run `code1.Rmd` to generate the crime statistics visualizations and build the dashboard.

### Data Sources

1. **US Occupation Growth**:
   - The data was sourced from the **U.S. Bureau of Labor Statistics**, focusing on occupations with the fastest-growing employment rates and expected salary increases between 2019 and 2029.

2. **Crime Statistics Agency**:
   - The crime data used in the CSA visualizations is publicly available from the Crime Statistics Agency of Victoria, which provides annual crime statistics reports to the public.
