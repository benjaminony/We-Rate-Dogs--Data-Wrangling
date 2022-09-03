### INTRODUCTION
This is a data wrangling project carried out with Twitter data of @dog_rates (a.k.a WeRateDogs). @dog_rates, rates dogs in a unique way using pictures of dogs, sent in via tweets by dog owners to the twitter handle. Dogs are also rated with humorous comments, some tweets containing dog stages known as doggo, puppo, floofer and pupper. Here, tweet archive data of @dog_rates up to the year 2017 is wrangled and analysed.

The file `act_report.pdf`, contains more information of the data wrangling activity done, with visalizations of findings.

### DATA WRANGLING
* _Gathering_: Data is gathered from three online locations in three files namely: `twitter-archive-enhansed.csv`, `image-prediction.tsv` and `tweet_json.txt`. The content of these files are then loaded into three dataframes for accessement and cleaning, using data loading methods that are suitable for the different file formats.
* _Accessment and Cleaning_: The data in three dataframes were accessed visually and programmatically for quality and tidiness issues. All three datafames were then merged to produce one master dataframe, before cleaning and tidying were done using _define_, _code_ and _test_ approach.
* _Data Analysis_: Once cleaning was over, exploratory data analysis was carried out on the final master dataset containing 1,914 tweet records and 21 columns/variables.

### FINDINGS
For all dog stages, pupper had more retweet counts followed by doggo. Tweets relating to pupper had the highest likes. The algorithm used to predict the dog breeds using sent in images, was more confident predicting dogs in doggo pupper stages.

### PROJECT ENVIRONMENT
Project was carried out in Anaconda environment using the following python packages:
 - JuPyter notebook
 - Pandas
 - Numpy
 - Matplotlib
 - seaborn
 - requests
 - os
 - json

Other compute resources used include:
 - [Online JSON Viewer](http://jsonviewer.stack.hu/)
 - [CSV Viewer Online](https://limonte.github.io/csv-viewer-online/)