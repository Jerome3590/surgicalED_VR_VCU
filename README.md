# **SlingED VR Exploratory Data Analysis (EDA)**

SlingED VR is a data analysis and visualization platform for tracking and optimizing user surgical performance.
A comprehensive solution that will leverage AWS cloud infrastructure to collect, analyze, and visualize VR user trial data near real-time. 
The system will determine optimal performance paths and provides instant feedback through dynamic visualization.
Below is initial exploratory data analysis for a to be determined final solution.

## Architecture

**Initial Cloud Infrastructure**
- Primary Storage: AWS S3 Data Lake
- Real-time Database: Amazon DynamoDB
- Client Integration: AWS C++ SDK

## Features

**Data Processing Pipeline**
- Automated data ingestion from VR devices
- Real-time data normalization and preprocessing
- Expert path modeling using advanced clustering algorithms
- Deviation analysis from optimal performance paths

**Visualization Suite**
- Interactive time series analysis
- Cluster visualization interface
- Optimal path mapping with color-coded deviation tracking

## Project Structure
.  
├── eda/  
│   
├── cluster_analysis/  
│   
├── optimal_path/
│   
└── data_viz/  


## Time Series Clustering Analysis
[**Time_Series.html**](https://plotly-demo.s3.us-east-1.amazonaws.com/time_series.html)

## Optimal Path Analysis
[**Optimal_Path.html**](https://plotly-demo.s3.us-east-1.amazonaws.com/optimal_path.html)