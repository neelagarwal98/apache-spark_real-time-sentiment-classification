# Tracking Tweet Sentiment at Scale Using a Pretrained Transformer (Classifier) with Apache Spark

This project demonstrates an end-to-end system for tracking tweet sentiment at scale, leveraging Apache Spark and its ecosystem, including Databricks, Delta Lake, and MLflow. The implementation showcases Spark streaming within a medallion data architecture using Delta Lake, enabling scalable Spark inference with an MLflow-packaged model. Additionally, the system includes exploratory data analysis, system tracking, and monitoring features to ensure comprehensive data management and analysis.

## Features

- **Spark Streaming**: Real-time processing of tweet data.
- **Medallion Data Architecture**: Efficient data management using Delta Lake.
- **Spark Inference at Scale**: Deploy and manage ML models at scale using MLflow.
- **Exploratory Data Analysis**: Dive deep into data insights with interactive notebooks.
- **System Tracking and Monitoring**: Monitor the system's performance and data flow.

## Notebooks Description

- `includes.ipynb`: Defines paths for raw data stored in the Amazon S3 bucket and sets essential variables for the project.
- `utilities.ipynb`: Contains helper functions for listing contents of the S3 bucket, clearing previous runs, and managing Spark streaming jobs (stop specific/all running streams).
- `Streaming Tweet Sentiment Analysis at Scale.ipynb`: The main PySpark implementation notebook. This notebook outlines the entire end-to-end pipeline following the medallion data architecture principles.

<br><br>
<img src="https://data-science-at-scale.s3.amazonaws.com/images/pipeline.drawio.png">
<img src="https://data-science-at-scale.s3.amazonaws.com/images/notebooks.drawio.png">

## Technologies Used

- Apache Spark
- Databricks
- Delta Lake
- MLflow
- Amazon S3

## Getting Started

To get started with this project, clone the repository and follow the setup instructions in each notebook to configure your environment and data paths.

## License

Apache License - see the `LICENSE.md` file for details.

## Authors

- Neel Agarwal

## Acknowledgments

- Ajay Anand, Professor, Goergen Institute for Data Science and Artificial Intelligence, University of Rochester.
- Lloyd Palum, CTO at Tenstreet True Fuel Division and Adjunct. Prof at University of Rochester. 

#Spark #Streaming #DeltaLake #MLFlow #DataMarts