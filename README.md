# Data Visualization of Iris Dataset

## Project Overview

This project demonstrates various data visualization techniques using the popular **Iris** dataset. The Iris dataset contains measurements of sepal length, sepal width, petal length, and petal width for three species of Iris flowers: *setosa*, *versicolor*, and *virginica*. The visualizations are implemented using **Matplotlib** and **Seaborn** in Python.

## Visualizations

1. **General Statistical Summary**:
   - Display basic statistical data (mean, standard deviation, min, max, etc.) for each feature.
   - Visualized using a **pairplot** to show relationships and distributions across the species.

2. **Pie Plot for Species Frequency**:
   - A pie chart representing the frequency of the three species in the Iris dataset.

3. **Scatter Plot for Sepal Length vs Sepal Width**:
   - A scatter plot to display the relationship between sepal length and sepal width, differentiated by species.

4. **Distribution of Sepal and Petal Features**:
   - Histograms displaying the distribution of sepal and petal length and width for the dataset.

5. **Joint Plot of Sepal Length vs Sepal Width**:
   - A joint plot visualizing the individual distributions of sepal length and sepal width on the same plot.

6. **KDE Plot for Setosa Species (Sepal Length vs Sepal Width)**:
   - A Kernel Density Estimate (KDE) plot for the setosa species showing sepal length and width.

7. **KDE Plot for Setosa Species (Petal Length vs Petal Width)**:
   - Another KDE plot for the setosa species, showing petal length and width.

## Requirements

- Python 3.x
- Libraries:
  - `matplotlib`
  - `seaborn`
  - `pandas`

Install the necessary libraries using:
```bash
pip install matplotlib seaborn pandas
```
## Example Output

- **Pairplot**: A visualization of the relationships between all features of the dataset.
- **Pie Chart**: Species frequency distribution.
- **Scatter Plot**: Relationship between sepal length and width, color-coded by species.
- **KDE Plots**: Density estimates for the setosa species.

## Dataset

The Iris dataset is available via the `seaborn` library:
```python
iris = sns.load_dataset('iris')
```
