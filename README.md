# Forex Data Pipeline

## Overview
The Forex Data Pipeline is a comprehensive solution designed to collect, process, and prepare currency exchange rate data for downstream machine-learning pipelines. This repository showcases the creation of a data pipeline that fetches currency rates from an external API, performs data transformation using PySpark, and loads the processed data into a Hive table within the Hadoop Distributed File System (HDFS). The primary goal is to provide clean and structured currency rate data for seamless integration into subsequent machine-learning workflows.

## Features

- **Data Extraction**: The pipeline connects to an external API to retrieve real-time currency exchange rates, ensuring that the most up-to-date information is captured.

- **Data Transformation**: PySpark is employed to perform data wrangling and transformation tasks, ensuring that the raw data is refined, cleansed, and structured for analysis.

- **Hive Integration**: The processed data is stored in a Hive table within HDFS, facilitating efficient storage and retrieval of the prepared currency rate information.

- **Seamless ML Integration**: By providing clean and well-structured data, the Forex Data Pipeline sets the stage for downstream machine-learning pipelines to integrate and build predictive models seamlessly.

## Repository Structure

The repository is organized as follows:

- `/forex_data_pipeline_final.py`: Contains the source code for the Forex Data Pipeline.

## Getting Started

To use the Forex Data Pipeline:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/sabareh/forex-data-pipeline.git

