# Bellybutton Biodiversity Dashboard

This project aims to create an interactive dashboard to explore bellybutton biodiversity data. The dashboard includes:

1. **Data Visualization**: Utilizes Plotly.js to create dynamic charts:
   - Horizontal Bar Chart: Displays the top 10 Operational Taxonomic Units (OTUs) found in the selected individual, with sample values as bar heights, OTU IDs as labels, and OTU labels as hovertext.
   - Bubble Chart: Illustrates each sample with OTU IDs on the x-axis, sample values on the y-axis, marker size representing sample values, marker color corresponding to OTU IDs, and OTU labels as text values.

2. **Dropdown Menu**: Allows users to select different test subject IDs to view corresponding data.

3. **Demographic Info**: Provides demographic information of the selected individual.

4. **Integration with D3.js**: Fetches sample data from an external JSON file using D3.js, ensuring dynamic data retrieval and visualization.

## Usage

1. Clone the repository.
2. Open `index.html` in a web browser.
3. Select a test subject ID from the dropdown menu to view the corresponding data.

## Technologies

- HTML
- CSS (Bootstrap for styling)
- JavaScript (D3.js for data fetching and Plotly.js for data visualization)

## Credits

- D3.js: [https://d3js.org/](https://d3js.org/)
- Plotly.js: [https://plotly.com/javascript/](https://plotly.com/javascript/)
- Bootstrap: [https://getbootstrap.com/](https://getbootstrap.com/)

## Data Source

- samples.json: [https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json)


