# belly-button-challenge

# Bacteria Cultures Dashboard

This project is an interactive dashboard that visualizes bacteria culture data from human belly button samples. The dashboard is built using D3 and Plotly and provides a user-friendly interface to explore the data.

Link to the Bacteria Cultures Dashboard: https://kathyvng.github.io/belly-button-challenge/ 

## Project Overview

The dashboard reads data from a JSON file hosted at [https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json). It features:

- **Horizontal Bar Chart:** Displays the top 10 OTUs (Operational Taxonomic Units) found in the selected sample.  
  - Uses `sample_values` for the bar lengths.
  - Uses `otu_ids` for the labels.
  - Uses `otu_labels` for hovertext information.
  
- **Bubble Chart:** Shows each sample's bacteria cultures.  
  - Uses `otu_ids` for the x-axis.
  - Uses `sample_values` for the y-axis.
  - Marker size is set by `sample_values`.
  - Marker colors are based on `otu_ids`.
  - Hovertext displays `otu_labels`.

- **Metadata Panel:** Displays demographic information (metadata) for the selected sample.  
  - Iterates through each key-value pair from the metadata JSON object and appends it to the panel.

The dashboard updates all charts and the metadata panel whenever a new sample is selected from the dropdown menu.

## Technologies Used

- **JavaScript** for interactive functionality.
- **D3.js** to load and manipulate the JSON data.
- **Plotly.js** to render interactive charts.
- **HTML/CSS** for page structure and styling.

## File Structure

- **index.html:** Main HTML file that structures the dashboard.
- **app.js:** Contains the JavaScript code for building and updating the charts and metadata.
- **styles.css:** (Optional) Custom CSS styles for the dashboard.
- **README.md:** Project overview and instructions (this file).

## Code Source: 
Xpert learning Assistant: https://bootcampspot.instructure.com/courses/6252/external_tools/451

