
## f1_analysis

Small analysis project built around historical Formula 1 results/qualifying data.

### Programs

- f1_data_scraping.ipynb
  Scrapes qualifying lap-time data that is missing from the raw dataset (notably pre-1994 qualifying times).
  Produces cleaned qualifying time tables for merging into the main dataset.

- dataset_creation.ipynb
  Loads raw F1 datasets in data_raw/ plus any scraped qualifying-time outputs.
  Cleans/normalizes fields (e.g., missing values like \\N, consistent qualifying time columns).
  Builds analysis-ready tables and exports CSVs (e.g., overall.csv, circuit-specific qualifying CSVs).

### Data

- data_raw/
  Raw source tables (races, results, qualifying, lap_times, pit_stops, drivers, constructors, standings, etc.)

### Outputs

- overall.csv
  Main analysis-ready dataset.

- *_grand_prix_qualifying_1950_2025.csv
  Circuit-specific qualifying datasets.

### Python packages used
