Customer segmentation is a crucial aspect of marketing and business strategy. This project aims to analyze customer behavior and group them into segments based on their purchasing patterns, total spending, and recency of purchases. The clustering algorithm used for segmentation is KMeans.

**Note:** The interactive 3D scatter plot in the conclusion section does not render on GitHub. You can download the interactive HTML file [here](plots/interactive_plot.html)

## Contents

- `main.ipynb`: Jupyter notebook containing the entire data science project, from data exploration to customer segmentation using KMeans.

- `data.xlsx`: Excel file containing the dataset used for analysis.

- `plots/interactive_plot.html`: Downloadable HTML file for the interactive 3D scatter plot.

- `plots/static_plot.png`: PNG of the 3D graph so that it can be displayed on github

## Project Structure

1. **Data Exploration and Preprocessing**: Initial exploration of the dataset, handling missing values, and creating relevant features.

2. **Feature Engineering**: Creating new features such as total spendings, total purchases, and recency of orders.

3. **Exploring Data Distribution**: Visualizing the distribution of key metrics using histograms and boxplots.

4. **Removing Outliers**: Applying the Interquartile Range (IQR) method to remove outliers from the dataset.

5. **Clustering Customers with KMeans**: Utilizing the KMeans clustering algorithm to group customers into segments.

6. **Conclusion**: Summarizing findings, providing insights into each customer segment, and displaying relationships between clusters.

## Instructions

1. Clone the repository:

    ```bash
    git clone https://github.com/MarekFilo/customer-segmentation.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Open and run the Jupyter notebook:

    ```bash
    jupyter notebook main.ipynb
    ```

4. Explore the analysis, visualizations, and conclusions in the notebook.

## Results

The results of the customer segmentation analysis are summarized in the notebook and include insights into the behavior of each customer segment.

## Acknowledgments

- Dataset Source: [Kaggle - Customer Segmentation Dataset](https://www.kaggle.com/datasets/yasserh/customer-segmentation-dataset) , special thanks to the author [yasserh](https://www.kaggle.com/yasserh)