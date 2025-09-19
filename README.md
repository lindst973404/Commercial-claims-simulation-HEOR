# Simulated Claims Data for Payer-Provider Workflow Analytics I

This project explores high-cost utilization patterns among chronic condition 
cohorts using simulated commercial claims data. The analysis focuses on 
differences in cost burden and builds reproducible workflows for HEOR 
applications.

## What's Included

- **Notebook**: `Claims_PayerCostStatWorkflow.Rmd`  

- **HTML output**: `Claims_PayerCostStatWorkflow.html`  

- **Simulated Claims Data**: `commercial_claims_cpb.RData`  
  

## Additional Modifications

- Manual control over table titles and numbering (no auto-numbering)
- Float-resistant LaTeX tables using `longtable` and raw LaTeX blocks
- Conditional logic for BRFSS smoking variables
- Clean, reproducible RMarkdown-to-PDF pipeline using `pdflatex`

## How to Reproduce

To regenerate the notebook and PDF:

1. Clone the repository
2. Open `Claims_PayerCostStatWorkflow.Rmd` in RStudio
3. Ensure the data file `commercial_claims_cpb.RData` is located where desired   
4. Knit to HTML using the Knit button or `rmarkdown::render()`

> Note: This notebook is designed for manual control over table layout and numbering. Auto-numbering and float environments are intentionally disabled.

## Author

**Lindsay Trujillo, PhD, MPH**  
Principal Data Scientist & Epidemiologist  
Specializing in reproducible analytics, regulatory documentation, and 
data simulation for advanced training and generating insights for 
clear stakeholder-ready reporting.

### Suggested Citation

Trujillo L. *Simulated Claims Data for Payer-Provider Workflow Analytics*. GitHub. September 2025.

## License

This project is released under the MIT License. See `LICENSE` for details.
