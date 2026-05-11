# Mariia-Sabaeva-Lesson-6-Mini-Project

# Open Data ETL Mini Project — Pokemon API

## Project Overview
This project demonstrates a simple ETL workflow using the public PokéAPI.

The pipeline:
1. Extracts Pokémon data from the API
2. Transforms and cleans the data using pandas
3. Loads the processed dataset into a CSV file

## Data Source
PokéAPI:
https://pokeapi.co/

Example endpoint:
https://pokeapi.co/api/v2/pokemon/pikachu

## Technologies Used
- Python
- pandas
- requests
- Google Colab

## Transformations Performed
- Extracted nested JSON fields
- Renamed columns
- Converted height and weight units
- Created a new BMI-like metric column
- Sorted Pokémon by calculated metric

## Output
The final cleaned dataset is saved to:

data/processed/output.csv

The output contains:
- Pokémon name
- type
- ability
- height
- weight
- base experience
- calculated BMI-like metric

## How to Run
1. Install dependencies:

pip install pandas requests

2. Open the notebook in Google Colab or Jupyter

3. Run all cells

4. The processed CSV will be generated automatically

## Example Output
The final dataset includes cleaned and transformed Pokémon statistics ready for analysis or dashboarding.
