# belly_button_challenge

This repository contains an interactive dashboard built to explore the Belly Button Biodiversity dataset. The dataset catalogs the microbes that colonize human navels and reveals that a small handful of microbial species (operational taxonomic units, or OTUs) are present in more than 70% of people, while the rest are relatively rare. The dashboard provides visualizations and demographic information for the Belly Button Biodiversity dataset. Users can select individual samples from a dropdown menu to view the top 10 OTUs found in that individual and explore various other visualizations.

## Features
- **Horizontal Bar Chart**: Displays the top 10 OTUs found in an individual. The bar chart updates based on the selected sample.
- **Bubble Chart**: Displays each sample with the following properties:
- **Demographic Info Panel**: Shows the sample's metadata (demographic information).
- **Interactive Update**: All plots and demographic information update when a new sample is selected from the dropdown menu.

## Dataset
The dataset is read from a JSON file located at the following URL: https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.

## Sources
Several documentation sources were utilized while creating the dashboard code:
 - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
 - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseInt
 - https://plotly.com/javascript/horizontal-bar-charts/
 - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/option
