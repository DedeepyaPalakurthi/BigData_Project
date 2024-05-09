# COVID-19 Twitter Data Analysis

## Introduction
This project aims to analyze Twitter data related to the COVID-19 pandemic. It includes the extraction, processing, and analysis of tweets to uncover insights into language trends, sentiments, and discussions surrounding the pandemic on Twitter.

## Requirements
To execute this project, you need to have Python installed on your system along with the following libraries:
- Apache Spark (pyspark==3.1.2, py4j==0.10.9)
- numpy==1.21.2
- pandas==1.3.3
- csv==1.0
- json==2.0.9
- matplotlib==3.4.3
- seaborn==0.11.2
- wordcloud==1.8.1

You also need to have MongoDB installed on your local system to connect using pymongo and load the processed data.

## Execution
1. Clone this repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Ensure you have a Spark environment set up or install Spark locally.
4. Run the main script `analyze_twitter_data.py` to start the analysis.
5. Follow the prompts or instructions provided in the script to execute specific analyses or visualizations.

## Data
The Twitter dataset used for this analysis spans from [start date] to [end date]. The dataset contains [number] of tweets related to COVID-19.

## Outputs
- Word cloud visualizations depicting popular terms and phrases used in COVID-19 tweets.
- Trend analysis plots showing the evolution of language patterns over time.

## Future Enhancements
1. Integration with real-time streaming for live analysis of Twitter data.
2. Implementing advanced machine learning techniques for deeper insights.
3. Enhancing data visualization techniques for more informative visualizations.

#References
1. Y. K. Gupta and S. Kumari. (2020). A Study of Big Data Analytics using Apache Spark  
with Python and Scala. IEEE, 471-478. doi: 10.1109/ICISS49785.2020.9315863.
https://ieeexplore.ieee.org/document/9315863/ 
2. Georgios, D., Aristeidis, K., Christos, K., K. G., Mylonas, P., Spyros, S. (2022). 
Decomposing Twitter Graphs Based On Hashtag Trajectories: Mining And Clustering Paths Over MongoDB. https://doi.org/10.1145/3549737.3549768 
3. Abdul Hafeez, Ali Hassan Sial. (2021). Comparative Analysis of Data Visualization 
Libraries Matplotlib and Seaborn in Python. https://doi.org/10.30534/ijatcse/2021/391012021

Feel free to reach out for any queries or assistance!
