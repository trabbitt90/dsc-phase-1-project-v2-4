# Movie Industry Analysis and Exploration

By: Tim Rabbitt

## Overview:

Microsoft wants to enter the multibillion-dollar movie industry. Before doing so they would like to explore the factors that help to make a movie successful in today's market. I have been tasked with finding some helpful insights into the industry. By focusing on return on investment, I keyed in on specific release dates, genres, and celebrities that can help make their inaugural film a success. After importing data from reputable sources and performing data cleaning and filtering, my analysis found that animated musicals and horror sci-fi films were very effective in producing a high return on investment. Additionally, I made recommendations on month of release and which celebrities to cast for the films. If Microsoft considers a successful film, one that produces a high return on investment, following these recommendations can help to make their venture into the movie industry a big hit.

## Business Problem:

Microsoft wants to enter into the movie-producing business. Before they dive into the multibillion-dollar industry they want to do their due diligence on what factors have historically contributed to a successful film. This is where I come in, I have been tasked with sorting through industry data to make their production debut a success. The focus of my analysis surrounds variables that influence return on investment (ROI). From a business standpoint, I thought this would an appropriate focus. As Microsoft begins to establish itself in the industry the more it can get in return for initial investments, the better. By analyzing a variety of ROI influences, I can make recommendations to Microsoft that will produce the highest rate of return possible. The ROI influences that I focused my analysis on are as followed:

How does the release date of the film influence return on investment?

How does the genre of the film influence return on investment?

What actors/actresses have produced the highest return on investment?


## Data:

I used two different sources for my analysis. 

IMDb (Internet Movie Database): IMDb is the world's most popular and authoritative source of movie, TV, and celebrity content. This database contains valuable information on relevant actors and actresses, movie titles, and genres. 

The Numbers: The Numbers is a premier provider of movie industry data and research services. This free resource provides detailed movie financial analysis, including box office, DVD and Blu-ray sales reports, and release schedules. This resource provides production budget and worlwide gross revenue information that is of particular interest in our ROI analysis.

## Methods: 

After importing the data I began to remove unwanted values such as NaN or entries of 0. I also stripped movie titles of punctuation and spaces so they would not interfere with merging data frames. I used the production budget and worldwide gross of the film to find the percent ROI. I then performed descriptive statistics on these refined dataframes and created data vizualizations that point to the recommendations below.



## Results:

<img width="937" alt="1" src="https://user-images.githubusercontent.com/100429663/171662584-b45c6983-d065-4668-8a0c-7a281d46c04c.png">

The month with the highest return on investment is July, followed closely by November and June.

<img width="884" alt="2" src="https://user-images.githubusercontent.com/100429663/171663003-a822e32b-35dc-4ae7-ab70-579a56d80e2c.png">

Musical genre had the highest return on investment, followed by Animation.

To further explore these variables, I wanted to see if a given genre found more success (higher return on investment) if the film was released in a certain month of the year.

<img width="980" alt="3" src="https://user-images.githubusercontent.com/100429663/171663402-3e39edda-ea6a-4078-a085-d0345da6afd3.png">

February Musicals, and January Sport films dominated return on investment.

<img width="1039" alt="4" src="https://user-images.githubusercontent.com/100429663/171663691-4e915366-df79-4c29-9390-a3869929064c.png">

Anya Taylor-Joy, Octavia Spencer, and Judi Dench have a track record of starring in films that produce high ROI. Addtionally, their are celebrities that have appeared in several animated films (high ROI genre) such as Josh Gad and Kristin Wiig.

## Conclusion:

### First Movie Recommendation:

An Animated Musical

Released in February or July

With characters voiced by actors/actresses that have a track-record of high return on investment and appearing in animated films such as Kristen Wiig, Josh Gad.

### Second Movie Recommendation:

A Horror Sci-Fi

Released in May or November

Starring actors/actresses that have a track record of a high return on investment and appearing in thrilling films such as Anya Taylor-Joy, Octavia Spencer, and Judi Dench.

I feel confident that my anlysis will help Microsoft to make appropriate decisions regarding the direction of their first film. By following the recommendations above they can optimize return on investment and produce a profitable movie. Future analysis could include an investigation into which genres these top actors/actresses find their success. Production budget, directors, and rating would be interesting to look into to see how they may affect ROI. All things considered, I believe this is a good start for Microsoft's venture into the movie industry.


## For More Information:

Please check out my Jupyter Notebook: https://github.com/trabbitt90/Movie-Industry-Analysis/blob/master/movie_industry_analysis.ipynb and my presentation: https://github.com/trabbitt90/Movie-Industry-Analysis/blob/master/Presentation.pdf

## Navigating the Repository: 

README.md ---> Document for reviewers of the project

movie_industry_analysis.ipynb ---> Analysis and method explaination in Jupyter Notebook

Presentation.pdf ---> PDF of presentation slides





```python

```
