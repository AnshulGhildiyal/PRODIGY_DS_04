# **Sentiment Analysis Project**  

## **Overview**  

This project demonstrates the implementation of sentiment analysis using Python. By leveraging tools like **TextBlob** for natural language processing, 
the project analyzes textual data to determine sentiment polarity (positive, negative, or neutral). The insights generated from this analysis are visualized
to help interpret the sentiment distribution across various platforms.  

## **Features**  

- **Data Handling**: Efficient data loading and preprocessing using **pandas**.  
- **Sentiment Analysis**: Calculation of sentiment polarity for each post using **TextBlob**.  
- **Visualization**: Graphical representation of sentiment trends and distributions using **Matplotlib**.  
- **Platform Insights**: Sentiment analysis segmented by social media platforms.  

## **Dataset**  

The dataset used for this project includes:  
- **Columns**:  
  - `ID`: Unique identifier for each entry.  
  - `Platform`: Source platform (e.g., Twitter, Facebook).  
  - `Sentiment`: Predefined sentiment category (if available).  
  - `Post`: Text content of the post.  
- **File**: `PRODIGY_DS_04_Data.csv`  

## **Prerequisites**  

To run this project, ensure you have the following installed:  
- Python 3.7+  
- Libraries:  
  - `pandas`  
  - `TextBlob`  
  - `matplotlib`  

Install the required libraries using:  

```bash  
pip install pandas textblob matplotlib  
```

## **Project Structure**

📂 Sentiment-Analysis-Project  
├── PROGIDY_DS_04.ipynb    # Jupyter Notebook with code and analysis  
├── PROGIDY_DS_04_Data.csv # Dataset file  
├── README.md              # Project documentation  


## **Key Function**

The function get_sentiment_polarity computes the sentiment polarity of a given text:

```
def get_sentiment_polarity(text):  
    return TextBlob(text).sentiment.polarity
```

## **Visualization**

- **Sentiment Distribution**: Pie chart or bar graph to display sentiment breakdown.
- **Platform-Based Sentiment Trends**: Insights into sentiment by platform.


## **Results**

- Extracted sentiment polarities for all posts.
- Visualized sentiment distribution across platforms.
- Identified key trends and patterns in user sentiment.

## **Acknowledgement** 
This project was developed during my internship at Prodigy Infotech. Special thanks to my mentors and peers for their guidance and support.
