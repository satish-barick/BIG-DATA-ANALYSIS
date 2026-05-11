# BIG DATA ANALYSIS

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: SATISH CHANDRA BARICK

*INTERN ID*: CTIS9149

*DOMAIN*: DATA ANALYTICS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

# DESCRIPTION :
## Project Description

This project focuses on **Big Data Analysis using Dask** on the **NYC Taxi Trip Dataset (2018)**, which contains approximately **9.39 million taxi trip records**. The dataset includes information such as passenger count, trip distance, fare amount, payment type, pickup and drop-off details, and other trip-related attributes. The primary objective of the project was to efficiently process and analyze a large-scale real-world dataset while demonstrating the scalability and performance benefits of distributed computing.

The project was developed using **Python** in **Jupyter Notebook (VS Code)** with the help of **Dask**, **Pandas**, and **Matplotlib**. Dask was used as the core big data processing framework because it enables parallel and out-of-core computation, allowing large datasets to be processed efficiently without memory issues.

Several data preprocessing techniques were applied, including removing null values, eliminating duplicate records, and cleaning column names for consistency. Exploratory Data Analysis (EDA) was then performed to understand passenger trends, fare distributions, and trip distance patterns. Multiple visualizations such as bar graphs, histograms, and scatter plots were created to represent the analysis results clearly.

The project identified several important findings. Most taxi rides involved single passengers, showing a strong dominance of solo travel behavior. The average fare amount was approximately **31.64**, while the average trip distance was around **8.84 km**, indicating that most rides were short urban trips. The analysis also detected major anomalies in the dataset, including trips with zero passengers, extremely high fares for near-zero distances, and infinite fare-per-distance calculations caused by zero trip distances. These findings highlighted the importance of data cleaning and anomaly detection in real-world datasets.

To demonstrate scalability, Dask partition optimization was performed. Repartitioning the dataset improved execution performance significantly, reducing computation time from approximately **36.15 seconds to 31.39 seconds**. This proved the effectiveness of parallel processing for handling large datasets.

This type of analysis can be used in several real-world applications such as:

* Smart transportation systems
* Traffic and commuter behavior analysis
* Ride fare prediction systems
* Urban planning and traffic optimization
* Fraud and anomaly detection in taxi services
* Real-time transportation analytics

Overall, the project successfully demonstrated scalable big data processing, performance optimization, and anomaly detection using Dask on a large real-world transportation dataset.
