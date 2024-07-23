# New York Taxi Data Processing

## Project Overview
This project processes New York Taxi Trip data for the year 2019 to derive analytical insights and load the processed data into a SQLite database for further analysis.

## Environment Setup
- Python 3.7+
- Pandas
- Requests
- TQDM
- SQLite3
- Matplotlib
- Seaborn

## Running the Project
1. Clone the repository.
2. Run the data extraction script:
    ```bash
    python data_extraction.py
    ```
3. Run the data processing script:
    ```bash
    python data_processing.py
    ```
4. Load the processed data into SQLite:
    ```bash
    python data_loading.py
    ```
5. Generate visualizations:
    ```bash
    python data_analysis.py
    ```

## Data Analysis
- Peak hours for taxi usage.
- Effect of passenger count on trip fare.
- Trends in taxi usage over the year.
