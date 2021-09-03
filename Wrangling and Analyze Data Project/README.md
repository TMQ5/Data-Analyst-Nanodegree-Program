# Wrangling and Analyze Data
## Project Overview
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "[they're good dogs Brent](http://knowyourmeme.com/memes/theyre-good-dogs-brent)." WeRateDogs has over 4 million followers and has received international media coverage.

## Project Instructions
Our tasks in this project are as follows:  
**Step 1:** Gathering data from 3 different sources and different file formats  
**Step 2:** Assessing data  
**Step 3:** Cleaning data  
**Step 4:** Storing data  
**Step 5:** Analyzing, and visualizing data  
**Step 6:** Reporting  
    * our data wrangling efforts  
    * our data analyses and visualizations  

## Tools Used in the Project
These python's packages is used:
* pandas
* NumPy
* requests
* tweepy
* json

## Project Submission
1. Ensure that we meet specifications for all items in the [Project Rubric](https://review.udacity.com/#!/rubrics/3027/view). Our project "meets specifications" only if it meets specifications for all of the criteria.
2. Ensure that we have not included our API keys, secrets, and tokens in your project files.
3. If we completed our project in the **Udacity Project Workspace**, ensure the following files are present in our workspace, then click "Submit Project" in the bottom righthand corner of the Project Workspace page:
* `wrangle_act.ipynb`: code for gathering, assessing, cleaning, analyzing, and visualizing data
* `wrangle_report.pdf` or `wrangle_report.html`: documentation for data wrangling steps: gather, assess, and clean
* `act_report.pdf` or `act_report.html`: documentation of analysis and insights into final data
* `twitter_archive_enhanced.csv`: file as given
* `image_predictions.tsv`: file downloaded programmatically
* `tweet_json.txt`: file constructed via API
* `twitter_archive_master.csv`: combined and cleaned data
* any additional files (e.g. files for additional pieces of gathered data or a database file for your stored clean data)
4. If we completed our project outside of the Udacity Classroom, we must package the above listed files into a zip archive or push them from a GitHub repo, then click the "Submit Project" button on this page.
