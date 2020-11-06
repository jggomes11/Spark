# Spark

This project uses Apache Spark's DataFrames and Views(SQL).

Data is parsed from [2006 Amazon products metadata file](https://snap.stanford.edu/data/amazon-meta.html) to different files,\
each file will become a DataFrame or View to answer some questions:

- Product's most helpful and highest rating top 5 comments \
and most helpful and lowest rating top 5 comments.
- Product's similar products with greater salesrank than itself
- Product's daily rating evolution
- Top 10 Salesrank by categorie
- Top 10 Rating average by group
- Top 5 Rating average by categorie
- Top 10 Customers with more comments by group

The expected result is a Panda's Dataframe for answer the respective question

# Dependencies

 - PySpark
 - Pandas

# How to run

 - Download [Amazon product co-purchasing network metadata file](https://snap.stanford.edu/data/amazon-meta.html)

 - Open ```Spark-DataFrame-SQL.ipynb``` on Google Colab

 - Upload thw downloaded file ```amazon-meta.txt.gz``` to Google Colab

 - Run all notebook cells (You can **change** the desired **product** on Variables / Import(Setup) section) 
