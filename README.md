# Iris Dataset Analysis

This project analyses the Iris dataset using Python and Jupyter Notebook. The aim is to explore the dataset, summarise the variables using statistics, and identify patterns and relationships between different species of iris flowers through data visualisation.

## Dataset Description
The Iris dataset was introduced by Ronald Fisher in 1936 and is commonly used for evaluating classification methods.

The dataset contains measurements of 150 iris flowers from three different species:
 - Setosa
 - Versicolor
 - Virginica

Each flower is described using four features:
 - Sepal length (cm)
 - Sepal width (cm)
 - Petal length (cm)
 - Petal width (cm)

## Analysis Performed
The following analysis was carried out in this project:
- Loading and examining the dataset.
- Checking the dataset structure and confirming there are no missing values.
- Calculation of summary statistics for each variable.
- Saving summary statistics to text file.
- Creation of histograms to visualise overall distributions.
- Creation of histograms broken down by species to compare distributions
- Generation of scatter plots to examine relationships between variables.
- Correlation heatmap to show the strength of relationships between variables.
- Grouped analysis comparing average measurements between species.
- Creation of pairplot to visualise relationships across variables.

## Technologies Used
| Technology | Purpose |
|---|---|
| Python 3 | Core programming language |
| Jupyter Notebook | Interactive analysis environment |
| pandas | Data loading, cleaning, and summary statistics |
| matplotlib | Histograms, scatter plots, and box plots |
| seaborn | Correlation heatmap and pairplot |
| os | Creating output directory and saving files |
| itertools | Generating variable combinations for scatter plots |

## Project Structure
```
programming_scripting-pands-project/
├── analysis.ipynb
├── data/
|   └── iris.csv
├── outputs/
|   ├── boxplot.png
|   ├── correalation_heatmap.png
|   ├── pairplot.png
|   ├── petal_length_hist_by_species.png
|   ├── petal_length_hist.png
|   ├── petal_length_vs_petal_width.png
|   ├── petal_width_hist_by_species.png
|   ├── petal_width_hist.png
|   ├── sepal_length_hist_by_species.png
|   ├── sepal_length_hist.png
|   ├── sepal_length_vs_petal_length.png
|   ├── sepal_length_vs_petal_width.png
|   ├── sepal_length_vs_sepal_width.png
|   ├── sepal_width_hist_by_species.png
|   ├── sepal_width_hist.png
|   ├── sepal_width_vs_petal_length.png
|   ├── sepal_width_vs_petal_width.png
|   └── summary.txt
└── README.md
```

## How to Run
- Python 3 installed
- Install required libraries:
```bash
pip install pandas matplotlib seaborn jupyter
```

### Running the notebook
1. Clone the  repository
2. Navigate to the project folder
3. Open `analysis.ipynb` in VS Code or Jupyter Notebook
4. Run all cells to reproduce the full analysis

All plots will be saved automatically to the `outputs/` folder.

## Conclusion
The results consistently show that peteal length and petal width are the most useful features for distinguishing between species. These features showed clear seperation in scatter plots, distinct groupings in both overall and species-level histograms, and the strongest correlations in the heatmap.

Sepal measurements showed considerably more overlap between species and are less effective for distinguishing between them.

## References
- [UC Irvine Machine Learning Repository: Iris Dataset](https://archive.ics.uci.edu/dataset/53/iris)

- Fisher, R.A. (1936). The use of multiple measurements in taxonomic problems.

- [Pandas documentations](https://pandas.pydata.org/docs/)

- [Matplotlib documentations](https://matplotlib.org/stable/index.html)

- [Seaborn documentation](https://seaborn.pydata.org/)

- Prior undergraduate coursework in programming.

## Author
Aiswaria Lajan