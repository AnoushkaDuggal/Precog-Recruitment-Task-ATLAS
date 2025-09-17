# A Graph-Based Analysis of the Game of Atlas
## Precog Recruitment Task Submission: ATLAS Theme

### Project Description
This repository contains a series of Jupyter notebooks that model the word game 'Atlas' as a directed graph. The project explores game strategy through graph theory, community detection, and machine learning for link prediction. Each notebook is a self-contained component of the overall analysis.

### Directory Structure
```text
.
├── City/
│   ├── Graph.png
│   ├── Graph_Creation_and_Analysis.ipynb
│   ├── Strategy Dashboard.png
│
├── Country/
│   ├── Community Detection (Country).ipynb
│   ├── Graph.png
│   ├── Graph_Creation_and_Analysis.ipynb
│   ├── Link Prediction (Country).ipynb
│   ├── Strategy Dashboard.png
│
├── Combined/
│   ├── Graph.png
│   ├── Graph_Creation_and_Analysis.ipynb
│   ├── Strategy Dashboard.png
│
├── requirements.txt
│
└── README.md
```

* **`Country/`, `City/`, `Combined/`**: Each directory contains the primary EDA notebook (`Graph_Creation_and_Analysis.ipynb`) for its respective dataset, along with saved PNGs of the visualizations.
* The `Country/` directory also contains the notebooks for the specialized tasks (Community Detection and the bonus Link Prediction).
* **`requirements.txt`**: A list of all necessary Python libraries.
* **`README.md`**: This file.


  
### Setup & Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AnoushkaDuggal/Precog-Recruitment-Task-ATLAS.git](https://github.com/AnoushkaDuggal/Precog-Recruitment-Task-ATLAS.git)
    cd Precog-Recruitment-Task-ATLAS
    ```
2.  **Install dependencies from `requirements.txt`:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage
The analysis is split into self-contained Jupyter notebooks, organized by the dataset they analyze.

### Country Analysis
Navigate to the `Country/` directory.
* **`Graph_Creation_and_Analysis.ipynb`**: Performs the main Exploratory Data Analysis (EDA). It generates a quantitative report, a visual dashboard, and launches an interactive strategy advisor tool for the country graph.
* **`Community Detection (Country).ipynb`**: Investigates the community structure of the country graph using Louvain and Girvan-Newman algorithms.
* **`Link Prediction (Country).ipynb`**: (Bonus Task) Implements and compares Node2Vec and a Graph Attention Network (GNN) to predict valid moves.

### City Analysis
Navigate to the `City/` directory.
* **`Graph_Creation_and_Analysis.ipynb`**: Applies the full EDA pipeline (report, dashboard, advisor) to a graph of the 500 most populated cities.




### Combined Analysis
Navigate to the `Combined/` directory.
* **`Graph_Creation_and_Analysis.ipynb`**: Applies the full EDA pipeline to a final, merged graph of both countries and cities.
    

