
# F1 Analysis Project

Small analysis project built around historical Formula 1 results and qualifying data.

## Programs

### `f1_data_scraping.ipynb`  
Scrapes qualifying lap-time data that is missing from the raw dataset (notably pre-1994 qualifying times).  
Produces cleaned qualifying-time tables that can be merged into the main dataset.

### `dataset_creation.ipynb`  
Loads raw F1 datasets from `data_raw/` together with any scraped qualifying-time outputs.  
Cleans and normalizes fields (for example: missing values such as `\N`, consistent qualifying-time columns).  
Builds analysis-ready tables and exports CSV files.

## Data

### `data_raw/`  
Raw source tables including:
- races  
- results  
- qualifying  
- lap_times  
- pit_stops  
- drivers  
- constructors  
- standings  

## Outputs

- `overall.csv`  
  Main analysis-ready dataset.

- `*_grand_prix_qualifying_1950_2025.csv`  
  Circuit-specific qualifying datasets.

## Python packages used

To run all programs in this repository, make sure the following Python packages are installed:

- **pandas**  
- **numpy**  
- **requests**  
- **matplotlib**

(Other modules used in the code such as `time`, `re`, and `io` are part of the Python standard library and do not need separate installation.)

## Running the code

Once the packages above are installed, all notebooks should run on any computer without further modification.


