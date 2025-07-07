#  Word Count Using Apache Spark (RDD)

##  Project Overview
This project demonstrates how to build a distributed word count system using the RDD (Resilient Distributed Dataset) model in Apache Spark with PySpark. It processes 732 rows of social media sentiment data and outputs word frequencies.

##  Dataset
- **File**: `sentimentdataset.csv`
- **Columns Used**: `Text` (social media text posts)

## ⚙ Technologies
- Python 3.x
- Apache Spark 3.x
- PySpark
- Jupyter Notebook

##  Methodology
1. Load and parse CSV data
2. Extract and clean the `Text` column
3. Tokenize text, normalize words
4. Use `map`, `reduceByKey` for word count
5. Visualize top 10 most frequent words using matplotlib

##  Output
- Tab-separated `.txt` file containing words and their frequencies.
- Bar chart of top 10 frequent words.
- the    137
and    112
is     97
covid  85
vaccine 83


##  Demo Video
📺 [Watch it on YouTube](https://your-video-link.com)

##  Use Case
Useful in social media monitoring, trend analysis, and natural language processing.

##  How to Run
1. Install PySpark: `pip install pyspark`
2. Run the Jupyter notebook `RDD_WordCount.ipynb`
3. Upload your CSV file or edit the path
4. Output will be saved in `.txt` format

##  Author
Sree Praveen Challa

![Screenshot 2025-07-07 at 1 53 14 PM](https://github.com/user-attachments/assets/ad4f136a-90d1-4c90-918a-d32d0c4199af)

