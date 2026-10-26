# Flight Delay Analysis and Data Visualization Using Python

## Project Overview

This project analyzes flight delay data for January 2019 and January 2020 using Python. It explores departure delays, arrival delays, flight cancellations, diversions, and airport-level delay patterns through data analysis and visualizations.

The project uses a random sample of 10,000 flight records to demonstrate data cleaning, exploratory data analysis, and data visualization.

## Dataset

The dataset contains flight information from:

- January 2019 — 5,000 sampled records
- January 2020 — 5,000 sampled records

**Total records analyzed:** 10,000

The sample dataset is provided in `flight_delay_sample.zip`, which contains:

- `Jan_2019_sample.csv`
- `Jan_2020_sample.csv`

The data is a sample of the original January flight datasets, not the complete dataset for either year.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Project Objectives

- Analyze departure and arrival delays.
- Examine flight cancellations and diversions.
- Compare flight data from January 2019 and January 2020.
- Explore departure delay percentages by origin airport.
- Present findings using charts and a dashboard.

## Project Workflow

1. Load the January 2019 and January 2020 sample datasets.
2. Combine the datasets and identify the year for each record.
3. Inspect and prepare the data for analysis.
4. Calculate delay and flight disruption metrics.
5. Create visualizations to explore delay patterns.
6. Summarize the findings and limitations.

## How to Run the Project

1. Download or clone this repository.
2. Open `Flight_Delay_Analysis_Corrected.ipynb` in Google Colab.
3. Upload `flight_delay_sample.zip` when prompted by the notebook.
4. Extract the ZIP file into the folder expected by the notebook.
5. Run the notebook cells in order using **Runtime → Run all**.

Make sure the extracted CSV filenames and folder path match those used in the notebook.

## Key Analysis Areas

- Departure delay percentage
- Arrival delay percentage
- Flight cancellations and diversions
- Origin airport departure delay comparison
- Airline and time-based delay patterns, where supported by the available data

Results are calculated from the sample records when the notebook is run.

## Conclusion

This project demonstrates how Python can be used to explore flight operations data and visualize delay patterns. The analysis provides practice with Pandas, data aggregation, and visualization using Matplotlib and Seaborn.

Because the analysis uses a random sample of 5,000 records from each January dataset, the results may differ from those obtained using the full datasets. The findings cover January only and should not be interpreted as representing the entire year.

## Limitations

- The analysis covers January 2019 and January 2020 only.
- Only 10,000 sampled records are included.
- Missing delay values may affect calculations.
- Airport comparisons can be influenced by the number of sampled flights at each airport.
- The analysis identifies patterns and does not establish the causes of delays.

## Repository Contents

- `Flight_Delay_Analysis_Corrected.ipynb` — Jupyter notebook containing the analysis and visualizations.
- `flight_delay_sample.zip` — ZIP file containing the two sample CSV datasets.
- `README.md` — Project documentation.

