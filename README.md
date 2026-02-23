# Global Earthquake Analysis with PySpark

Analysis of global seismic activity using Apache Spark (PySpark) on Google Colab.

## Datasets

Three datasets from Kaggle:
- **USGS Earthquake Database (1965-2016)** - 23,000+ events
- **Significant Earthquakes (1900-Present)** - 112,000+ events
- **Countries of the World** - 227 countries with demographic and economic data

## Project Structure

```
project/
  Project_Nolan_CACHEUX.ipynb   # Main notebook (run on Google Colab)
  images/                       # Spark UI screenshots
resources/
  consignes.txt                 # Assignment instructions
  spark/                        # Course materials (PySpark labs)
  hadoop/                       # Course materials (Hadoop labs)
```

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/github/nolancacheux/big-data-spark-hadoop/blob/main/project/Project_Nolan_CACHEUX.ipynb)
2. Add your Kaggle and ngrok credentials in the first code cell
3. Run all cells (Runtime > Run all)

## Techniques Used

| Technique | Reference |
|---|---|
| SparkSession setup | Lab 3.1 |
| Actions vs Transformations | Lab 3.2, 3.4 |
| Schema declaration | Lab 3.5 |
| Data quality and cleaning | Lab 3.6 |
| Transformations and calculated columns | Lab 3.7 |
| Spark SQL | Lab 3.8 |
| Joins and unions | Lab 3.10 |
| Window functions | Beyond course |
| Pivot tables | Beyond course |

## Author

Nolan Cacheux
