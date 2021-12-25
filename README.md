# Reddit-Sentiment-Analysis-with-Visualization

## What it does

This program extracts user posts submitted on the social media plattform Reddit. After it pulls the data, a sentiment analysis using flair 
determines the sentiment score of the individual posts. The results are stored in .csv-Files locally and a graphical illustration is shown to the user. 

Furthermore, the program lets the user select the search term, the subbreddit wished to search on, and a date range. 
>Please enter the search term. For example GME:
>
>Please enter subreddit. For example Superstonk:
>
>Enter yes to input a start and end date or no to show new posts: 

For further documentation, please view the file.

# How to run:


```
Reddit-Sentiment-Analysis-withVisualization.py
```

## Sample Output:

The program stores the output in .csv-Files locally.
>The .csv-Files have been created and stored locally.

The file reddit_data.csv looks like this:

<img width="1125" alt="Reddit Data Sample" src="https://user-images.githubusercontent.com/94754510/147390354-9ebcf931-137a-4a50-8e13-d042964103c6.png">

The second file timed_data_sentiment.csv looks like this:

<img width="362" alt="Reddit Sentiment" src="https://user-images.githubusercontent.com/94754510/147390450-5fd853e4-fbcc-4070-b371-7221c43915f2.png">


The two graphics look like this:

<img width="711" alt="Reddit Sentiment Plots" src="https://user-images.githubusercontent.com/94754510/147390505-5a01e34e-ea06-477d-a1d8-f50dc9fe5f32.png">

## Data

The data is extracted from Reddit and its selected subreddit. 
To do this, the program uses the API from https://pushshift.io. 

## Contributors

This program is written by *amileaminute* (Real Name & Immat. Nr. ) and *CookieMonster* (Real Name & Immat. Nr. ). 
