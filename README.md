# project-one

## Initial Project

### Project title:
    My Python [Don't Want None] Unless You've Got API's, Hun

### Team members:
* Ryland Wheliss
* Callie Carlton
* Daniel Meyerowitz
* Christian Lingle
* Qonesha Hunter

### Project description/outline
    1. Merge the data (Didn't work going to use 1 dataset)
    2. Compare variables to Address Research questions
    3. Create visualizations of Analyses
    4. Incorporate an API into our data set
    5. Draft Written Analysis of the data
    6. Create and Present a presentation


### Research questions
    1. How does the danceability correlate to popularity?
    2. How does energy compare to popularity?
    3. How does Explicit content affect popularity? 
    4. How does key compare to popularity?
    5. How does acousticness compare to popularity?
    6. How does liveness compare to popularity? (Boolean?)
    7. How does valence compare to popularity?
    8. How does tempo compare to popularity?
    9. How does genre compare to popularity?
    10. How does speechiness compare to popularity?


### Datasets to be used
    https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019
    Top Hits Spotify from 2000-2019

    API:
    https://api.chartmetric.com/apidoc/

### Rough breakdown of tasks
* Ryland - Group Lead, Initial Merge (Failed), Question 4, Question 6, Statistics Testing, Helped begin Questions 8 and 9, Further Exploratory Regressions, Slideshow Slide Creation
* Callie - Question 2 , Question 3 , DataSet Investigation, Question Construction, Project Writing, Helped Questions 1 and 5, Further Exploratory Regressions, Slideshow Slide Creation
* Qonesha - Question 8 , Question 9, Further Exploratory Regressions, Slideshow Slide Creation
* Daniel - Lead Presenter, API Investigation, Dataset Outliers, Question 7, Question 10, Helped begin Questions 1 and 5, Further Exploratory Regressions, Slideshow Slide Creation
* Christian 

### Analysis and Conclusion
In picking a dataset, our focus was on selecting a group of data that allowed our group to discover the perfect formula for writing a song. The dataset we found included a large number of metrics that ended up being somewhat vague but included many songs we found familiar. Below you will find the results from this dataset in an attempt to discover the perfect formula for a song.

The main metric that was investigated is popularity. This is a metric where each song was given a score between 0 and 100 based on its popularity. We dove into the songs with a popularity greater than 50 and investigated the statistical significance of the popular songs. We conducted a One Sample T-Test and found that the song were statistically significant with a PValue = 1.876245645341364e-227. This allowed us to use the "popular" songs for later correlations.

When doing statistical testing, we also investigated what we called the "loser" songs. This was all songs with a popularity between 0 and 10. We ran a T-Test on this dataset as well and the p-value = 2.5527473836321144e-303 proving that this group of songs were also statistically significant which was a curiosity because they were such outliers.

One of the metrics that we found which had a strong correlation to popularity was the key of the song. We created some visualizations about the key of the songs in relation to popularity and learned that C# is the most popular key with the popular songs. We also learned that D# is the least popular key for musicians as far as popular songs go.

Another metric we found that had a strong correlation is genre. 44% of the songs that were in thisdataset were pop songs. It dwarfed the next genre which was hip hop at only 21% of the songs. Both classical and Jazz music were the least used genres in the dataset. 
