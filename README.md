# SNA_Bibliographic-graph-or-its-subgraph-implementation-and-visualization.-And-clustering

## Dataset
The `cwurData.csv` dataset was loaded into a pandas DataFrame and cleaned by removing duplicates and NaN values. The cleaned dataset was saved into a new file named `cleaned.csv`.

## Bibliographic Network Analysis
The relevant columns for bibliographic connections were extracted from the cleaned dataset, and an empty directed graph was created using NetworkX. Nodes (paper title and citation) were added to the graph, and edges between paper title and citation were added to the graph. The resulting graph was visualized using Matplotlib.

## Institution Clustering
The institutions were clustered using K-means clustering after vectorizing the abstracts using TF-IDF and reducing dimensionality using Truncated SVD. The clusters were plotted using Matplotlib.

## Variable Distribution Visualization
The distribution of variables such as institutions, countries, and years in the dataset was visualized using Seaborn and Matplotlib libraries.

## Requirements
- pandas
- networkx
- matplotlib
- scikit-learn
- seaborn

These requirements can be installed using pip:

```bash
pip install pandas networkx matplotlib scikit-learn seaborn
```

## Usage
1. Clone the repository:
```bash
gh repo clone ketankolte7/SNA_Bibliographic-graph-or-its-subgraph-implementation-and-visualization.-And-clustering
```

2. Navigate into the project directory:
```bash
cd SNA_Bibliographic-graph-or-its-subgraph-implementation-and-visualization.-And-clustering
```

3. Run the Jupyter notebook:
```bash
jupyter notebook
```

4. Open `22mcb0016_SNA_Assessment3.ipynb` and run all the cells.

## Author
This project was created by [22MCB0016](https://github.com/ketankolte7) as an assessment for the Social Network Analysis course.

