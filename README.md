# Liverpool Transfer Network Analysis (2004–2024)

This project analyzes Liverpool FC’s transfer activity over a 20-year period by modeling the transfer market as a directed network. Clubs are represented as nodes and transfers as edges, enabling structural insights using Social Network Analysis (SNA).

The dataset is collected, cleaned, and transformed into processed CSV files and a final GraphML graph suitable for visualization and further analysis.

## Project Scope

- Extraction and preparation of transfer data from 2004–2024  
- Processing and aggregation of fees, transfer types, and club interactions  
- Construction of a directed transfer network using NetworkX  
- Export of the final graph for visualization in Gephi (layout, clustering, centrality)  

## Technologies

- Python (Pandas, NetworkX)  
- Jupyter Notebook  
- API-Football (data source)  
- Gephi (graph visualization)  

## Output

- Cleaned data in `data_processed/`  
- Raw API data in `data_raw/`  
- Final transfer network in `.graphml` format  
- Visualized graphs stored in `figures/`  
