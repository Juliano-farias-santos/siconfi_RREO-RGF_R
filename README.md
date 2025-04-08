📊 ##Brazilian Treasury Data - RREO Extraction

This project provides R scripts to collect fiscal data from the Brazilian National Treasury API — specifically the RREO (Relatório Resumido da Execução Orçamentária), which summarizes public budget execution by federal, state, and municipal entities.

🔎 What the Script Does
The main script in this repository performs the following tasks:

Connects to the Tesouro Nacional's public API.

Fetches any Annex of the RREO or RGF for any state for any period.

Parses and structures the API response into a unified data.frame.

Saves the result as a .csv file using Latin1 encoding to preserve Portuguese special characters.
