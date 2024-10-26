# Deploying Shiny Applications on Posit Connect Using Pins

## Overview

Tutorial Link: <https://ccb.connect.hms.harvard.edu/Git-Backed-Content-Tutorial/>

This tutorial guides you through deploying a Shiny app on Posit Connect using the powerful [pins](https://cran.r-project.org/web/packages/pins/index.html) package to manage your data efficiently. It demonstrates single-cell RNA sequencing data analysis with the [scRNAseq](https://www.bioconductor.org/packages/release/data/experiment/html/scRNAseq.html) package, encompassing data fetching, quality control, normalization, and dimensionality reduction with results showcased via a dynamic Shiny interface.

This tutorial provides step-by-step instructions for:

1.  Setting up your local environment and preparing data for deployment.
2.  Using the [pins](https://cran.r-project.org/web/packages/pins/index.html) package to upload datasets to Posit Connect securely.
3.  Developing a Shiny app that dynamically reads data from Posit Connect.
4.  Configuring and deploying the Shiny app on Posit Connect.

## Repository Structure

The tutorial's complete codebase is housed in this [GitHub repository](https://github.com/ccb-hms/Git-Backed-Content). Below are the main components and their respective branches:

-   **Analytics Code**: Responsible for generating and saving data using `pins`, located in the [master branch](https://github.com/ccb-hms/Git-Backed-Content).

-   **Quarto Document Code**: Generates this documentation, also deployed on the Posit Connect server alongside the Shiny app, available in the [Quarto branch](https://github.com/ccb-hms/Git-Backed-Content/tree/Quarto).

-   **Shiny Application Code**: Codebase for the Shiny app visualizing single-cell RNA-seq data, located in the [Shiny branch](https://github.com/ccb-hms/Git-Backed-Content/tree/Shiny).

## Outputs

From this repository's projects, several outputs are realized:

1.  [**Quarto Document**](https://ccb.connect.hms.harvard.edu/Git-Backed-Content-Tutorial/): Detailed guide and documentation displayed on Posit Connect.

2.  [**Shiny App**](https://ccb.connect.hms.harvard.edu/Git-Backed-Content-Shiny-App/): Interactive platform for visualizing single-cell RNA-seq data in reduced dimensions.

## Quick Start

### Setting Up Your Environment

1.  **Prerequisites**:
    -   Ensure you have R and RStudio installed.

-   Install required packages: `shiny`, `pins`, `rsconnect`, `scRNAseq`, `scran`, `scuttle`, `scater`.

2.  **Clone the Repository**:

``` bash
git clone https://github.com/ccb-hms/Git-Backed-Content.git 
cd your-repository
```

## Additional Resources

For extended information and guidance, explore the Posit Connect documentation under the [Git-Backed Content section](https://docs.posit.co/connect/user/git-backed/).
