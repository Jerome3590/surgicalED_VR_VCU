# **SlingED VR Exploratory Data Analysis (EDA)**

SlingED VR is a data analysis platform for tracking user surgical performance.
A comprehensive solution that will leverage AWS cloud infrastructure to analyze user trial data.  
Below is initial exploratory data analysis for a to be determined final solution.  

## Architecture

**Initial Cloud Infrastructure**
- Primary Storage: AWS S3 Data Lake
- Real-time Database: Amazon DynamoDB
- Client Integration: AWS C++ SDK

## Features

**Data Processing Pipeline**
- Data ingestion from VR devices

**Visualization Suite**
- Interactive time series analysis
- Cluster visualization interface

## Project Structure
.  
├── eda/  **(exploratory data analysis scripts)**   
├── eda/student_survey/ **(student survey results)**  
├── cluster_analysis/  **(cluster analysis scripts)**    
├── optimal_path/  **(optimal path scripts)**    
└── data_viz/  **(various data visualizations)**    


## Time Series Clustering Analysis
[**Time_Series.html**](https://plotly-demo.s3.us-east-1.amazonaws.com/time_series.html)

## Optimal Path Analysis
[**Optimal_Path.html**](https://plotly-demo.s3.us-east-1.amazonaws.com/optimal_path.html)