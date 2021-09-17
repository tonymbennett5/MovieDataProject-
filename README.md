# Microsoft Movie Studios Technical Analysis 

![blueprint](images/blueprint.png)
## Overview
Companies coming out with studios to produce film and tv content are increasingly becoming the norm. In an industry that used to only have a few powerful players, digital media has allowed all types of companies to start their own streaming/movie studios. Content has never been more accessible for the consumer and this is causing many existing companies to try to get into the media business. 


## Business Problem
The question behind this analysis was that Microsoft wants to start its own movie studio, but they are not sure where to begin. They have no industry knowledge and need someone to conduct a data analysis of films currently performing well at the box office. I have conducted said analysis and come up with 3 business recommendations for Microsoft to use. Microsoft can use these recommendations to try to become a profitable studio in a short amount of time.  
## Data

The data that was used in this study was taken from four separate data frames. The first two were taken from imdb which is an online database containing data related to films, televesion programs and other media information. The third data base that was used holds information on box office numbers such as gross and genre of film. The fourth data frame used held similar data to the third dataframe in that it had box office gross information. 


## Methods 
This was a descriptive analysis that focused on looking closely at the films and type of films that have been performing well financially in recent years. From this information a new studio can start to build a model of how they want to run. 



## Visualization/Explanation

### Box office and studio 

Top box office producing studios from 2010-2018. This data came from the BOM gross data base. A total box office column was created by adding the domestic and foreign box office numbers for each record. The dataframe could then be grouped by studio and return the sum of their total box offices. This chart shows big name studios like Marvel, Fox and Warner Brothers are doing well in the box office. It seems to drop off significantly after Paramount.  

![Top Studio Box Offices 2010-2018 ](images/movie_studio.png)

We can also see the biggest box office money makers in 2018. Most of these films are produced by these larger studios. We can also see that many of these films are sequels or part of some overarching film dynasty. It appears that only Bohemian Rhapsody is the only film not connected to another film series in some way. 
![Top Box office Films 2018 ](images/film_gross.png)


### Movie Genres and Box office

In order to get this movie genre chart the Bom gross and IMDB title data frame had to be merged. I then did a string contain method to test out a few genres to see which ones were most popular. I created two separate data bases for this chart, one with only the top genre and the rest containg movies without the genre. Adventure films appear to perform well at the box office vs all other genres. 

![Top Genre vs all other genres (2008-2018) ](images/adventure_scatter.png)


This provides a litte more insight into genres and how well they perform at the box office. The BOM gross and IMDB title data frame were combined here again. I could could then use a groupby.df.agg to to group by genre and add up the box office totals. Adventure and Action are the top here with a sharp drop off after comedy.  

![Movie Genre Top Gross (2008-2018)](images/genre_gross.png)



### Production Budget and Box office 

There is a postive correlation between production budget and box office gross, however a high production budget is not a guaranteed future box office smash hit. Films with higher budgets can still sometimes fail. Many movies make around what they put into the movie but as the budget increases it can raise the box office gross. This is not always the case but films from Marvel and Universal can have production budgets of well over 200 million dollars and reap close to a billion dollars at the box office.

![Movie Budgets Plotted Against World Wide Gross 2008-2018](images/prodbud_totalgross.png)

This chart shows the production budgets of the top ten films of 2018. Except for Bohemian Rhaposdy all the films had a budget over 100 million dollars. If one were too look at a list of top production budgets in 2018 there were only three movies that did not make it into the top ten for box office gross. The correlation between big budget and big production value is not perfect but it clearly exists. 
![![Movie Budgets Plotted Against World Wide Gross 2008-2018]](images/prodbud_films.png)


## Conclusions 

The analysis of this data has led to three recommendations for Microsoft to start, grow and expand their film/media studio. 

1. **Look closely at how large budget studios profit off their films** 
- Start a movie series that is familiar to audiences so there is a higher chance of box office returns 
- Look for current properties owned by Microsoft to transfer into the movie setting 
- Look to other large movie studios as to how they merchandise their movies and use preqel/sequel models


2. **Start by producing films in the Action/Adventure Genre**
- These two genres yield high box office returns and are recognized by audiences world wide
- Large action/adventure movies are prime for sequels and merchanising opportunities

3. **Putting Money into films can increase box office returns** 
- Microsoft is in an advantageous position unlike some companies trying to get into the film business as they are a very large comapny with accesss to capital for future films
- A higher production budget means access to good directors , crew members and popular actors. 
- A higher production budget means more money can be spent on marketing campaigns which are key to letting potential audiences know about films 


## Next Steps 

- Analyze current Microsoft properties to see if there are any potential contenders for box office hits (Halo, Minecraft etc ). These current properties will already be recognized by audiences which increases likelihood of them purchasing a ticket. 
- Conduct furthur analysis on how to produce successful action/adventure films. Explore subgenres and trends of what types of action/adventure films audiences are going out to see. What characteristics do they have: likeable characters, a high energry plot, smart dialogue etc. 
- Meet with potential excecutive producers and studio heads to make sure the studio is run in a smart, efficient way. Even though Microsoft has the potential to produce films with high production budgets they can become bloated without good and experienced management.  

## For More Information see full analysis in Jupyter notebook or review the presentation 


