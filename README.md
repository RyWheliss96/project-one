# project-one

## Initial Project

### Project Title:
    My Python [Don't Want None] Unless You've Got API's, Hun

### Team Members:
* Ryland Wheliss
* Callie Carlton
* Daniel Meyerowitz
* Christian Lingle
* Qonesha Hunter

### Project Description/Outline
    1. Merge the data (this didn't work as expected, used original dataset)
    2. Compare variables to address research questions
    3. Create visualizations of analyses
    4. Incorporate an API into our data set (time/access permitting)
    5. Draft written analysis of the data
    6. Create and present a formal presentation


### Research Questions and Answers After Analyses
    1. How does the danceability correlate to popularity?
        * Danceability and popularity do not correlate in this dataset
    2. How does energy compare to popularity?
        * Energy and popularity do not correlate in this dataset
    3. How does Explicit content affect popularity?
        * Explicit content does not negatively affect popularity in this dataset-in fact, the majority of the most popular songs contained explicit content 
    4. How does key compare to popularity?
        * C# was the most popular song key for this dataset
    5. How does acousticness compare to popularity?
        * Acousticness and popularity do not correlate in this dataset
    6. How does liveness compare to popularity? (Boolean?)
        * Liveness and popularity do not correlate in this dataset
    7. How does valence compare to popularity?
        * Valence and popularity do not correlate in this dataset
    8. How does tempo compare to popularity?
        * Tempo and popularity do not correlate in this dataset
    9. How does genre compare to popularity?
        * Pop was by far the most popular genre in this dataset
    10. How does speechiness compare to popularity?
        * Speechiness and popularity do not correlate in this dataset


### Datasets
    https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019
    Top Hits Spotify from 2000-2019

    API:
    https://api.chartmetric.com/apidoc/

### Task Delineation
* Ryland - Group Lead, Initial Merge (Failed), Question 4, Question 6, Statistics Testing, Helped begin Questions 8 and 9, Further Exploratory Regressions, Slideshow Slide Creation
* Callie - Question 2 , Question 3 , DataSet Investigation, Question Construction, Project Writing, Helped Questions 1 and 5, Further Exploratory Regressions, Slideshow Slide Creation
* Qonesha - Question 8 , Question 9, Further Exploratory Regressions, Slideshow Slide Creation
* Daniel - Lead Presenter, API Investigation, Dataset Outliers, Question 7, Question 10, Helped begin Questions 1 and 5, Further Exploratory Regressions, Slideshow Slide Creation
* Christian 

### Analysis and Conclusion
In choosing a dataset, our focus was on selecting data that enabled our group to discover the perfect formula for writing a song. The first dataset we considered included a large number of intersting metrics and included many songs we found familiar. The second dataset we considered had a larger volume of data, but had far fewer variables to examine. Originally, we considered merging the 2 different datasets on song title, as they initially appeared to have overlapping data. However, once we attempted the merge, it cut down the volume of our dataset significantly-so we decided to move forward with the inital dataset as there were more factors to analyze.

We then began by leveraging each variable present in the dataset against the song's popularity. In this dataset, each song was given a score between 0 and 100 based on its popularity. We wanted to specify a base determinant of popularity, so we dove into the songs with a popularity score greater than 50 and investigated the statistical significance of the popular songs against the dataset as a whole. We conducted a One Sample T-Test and found that the popular songs were statistically significant with a p-value = 1.876245645341364e-227. This gave us confidence to use the popular song specification for later correlation analyses.

When doing statistical testing, we also investigated what we called the "loser" songs-referring to all songs with a popularity between 0 and 10. We ran a T-Test on this dataset as well and the p-value = 2.5527473836321144e-303, proving that this group of songs were also statistically significant. We found this interesting, as they seemed to be outliers when compared to the rest of the data.

Our group members then began attempting to answer the questions we discussed in our brainstorming sessions individually. Unfortunately, most of the variables we analyzed in this dataset did not appear to correlate to each song's popularity metric. We initially expected variables such as tempo, liveness, danceability, and energy to have some weight in making the song popular, but this did not appear to be the case. However, we were able to make a few interesting conclusions about popularity as well as some of the other variables present. 

One of the metrics that we found had a strong correlation to popularity was the key of the song. We created some visualizations about the key of the songs in relation to popularity and learned that C# is the most popular key with the popular songs. We also learned that D# is the least popular key for musicians in this dataset.

Another metric we found that had a strong correlation to popularity is genre. 44% of the songs that were in this dataset were pop songs, which dwarfed hip hop (the second most popular genre) at only 21% of the songs. Both classical and Jazz music were the least used genres in the dataset. 
