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

data:image/png;base64,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L0at71GPehR/93d/x9VXd/oHP/7xj/PJT36SddddF4BtttmGvffem89//vO9fJvu0bNQmmTTJE/uWjUXuAhYr5kEiSSrJXlK1z57NuufCdxYVTcCNwNrde1zGp2AO3SeuQ+gvD27fv5yEtuVJEmS1MeWLVvG97//fbbccksOOeQQdtppJ84++2wWLFjAv//7v3PrrZ3+rl/+8pd89atf5ac//Skf/vCHWXvttTn//PM577zz2Gmnnbj22mv5yEc+wo9//GMWL17MwMAAhx122D3nGerRfOMb38ihhx7KnDlzOOCAA3jb297GkiVLeNaznjVqjb///e+544472GqrrQBYunQp8+bNu88+AwMDLF26tAfv0P31cqKjNYHPNUNwlwGX0RnmOh/4bJK1m/N/Ghi62huSnMm9Ex0BfAf4f0l2pTPR0YHA55Oc1xz/czqTIU3E6knOohPK92rWTUa7kiRJkvrQ7bffzty5c4FOT+l+++3HDjvswCmnnMKhhx4KdGYJ/v3vfw/AzjvvzDrrrAPAj3/8Y0444YR72nrkIx/JqaeeyoUXXsgznvEMAP72t7+x/fbb37PPy172MgDmzZvHSSedNK4av/GNb7BgwQJ+85vf8KUvfYnZs2ePum9VTdnkUb18pnQQGGkw87XAs0c57MSq+s9h7VwCbDVsvz2HLVNVBw9bXnOkbVU1p3n5wWH7XzuediVJkiRpuO5nSodUFSeeeCKbbrrpfdafddZZrLHGGvfZb3gArCp23nlnjj/+eEay+uqrA50JlpYtG9+3Vg49U/rLX/6SF7/4xbzoRS/isY99LJtvvjmDg4PstNNO9+y7ePFiNt9883G1+2D19JlSSZIkSepXL3jBC/jc5z7H0FQ355xzzoj7Pf/5z+eII464Z/mGG27g6U9/OmeccQaXXXYZALfddhuXXHLJmOdba621uPnmm8fcB2D77bfnta99LZ/5zGcAeNe73sW73/1urrvuOgCWLFnC0UcfzZve9KYVX+QkmDahtKp2rKrezTMsSZIkSVPo/e9/P3fddRdbbbUVW2yxBe9///tH3O9973sfN9xwA1tssQVbb701CxYsYL311uPoo49mr732YquttuLpT386F1988Zjn22WXXTj55JNXONERwLvf/W6OOuoobr75Zl760pey7777ssMOO7DZZpvxhje8geOOO47HPe5xD/jaJyI1jumNNT4DialakqQHyr9JJD1AF110EX//93/fdhl9Z6T3PclgVQ1MpJ1p01MqSZIkSeo/vZx9t//MmweL7CuVJEmSpPGyp1SSJEmS1BpDqSRJkqSVnnPlTK3JfL8NpZIkSZJWarNnz+a6664zmE6RquK6665j9uzZk9Kez5RKkiRJWqmtv/76XHXVVVxzzTVtl9I3Zs+ezfrrrz8pbRlKJUmSJK3UVlttNTbeeOO2y9AD5PBdSZIkSVJrDKWSJEmSpNYYSiVJkiRJrYkzVE2eJDcDv2m7DmkE6wLXtl2ENALvTU1H3pearrw3NV1135sbVdV6EznYiY4m12+qaqDtIqThkizy3tR05L2p6cj7UtOV96amqwd7bzp8V5IkSZLUGkOpJEmSJKk1htLJNb/tAqRReG9quvLe1HTkfanpyntT09WDujed6EiSJEmS1Bp7SiVJkiRJrTGUToIkL0zymySXJfmPtutRf0tyRZLzkyxJsqhZt06SHyW5tPn5yLbr1MyX5CtJ/pLkgq51o96LSf6z+Rz9TZIXtFO1+sEo9+bBSf7QfHYuSfKPXdu8N9VzSTZIsiDJRUmWJvm3Zr2fm2rVGPfmpH1uOnz3QUqyKnAJsDNwFXA2sFdVXdhqYepbSa4ABqrq2q51nwCur6qPNf/j5JFV9e62alR/SPJs4BbgmKraolk34r2YZHPgeGA74PHAj4FNqmp5S+VrBhvl3jwYuKWqDh22r/empkSSxwGPq6rFSdYCBoHdgH3wc1MtGuPefAWT9LlpT+mDtx1wWVX9tqr+BpwA7NpyTdJwuwJfbV5/lc4HidRTVfVz4Pphq0e7F3cFTqiqO6vqcuAyOp+v0qQb5d4cjfempkRVXV1Vi5vXNwMXAU/Az021bIx7czQTvjcNpQ/eE4Aru5avYuxfktRrBZyWZDDJ/s26x1TV1dD5YAEe3Vp16nej3Yt+lmo6eHOS85rhvUNDJL03NeWSzAGeCpyFn5uaRobdmzBJn5uG0gcvI6xzTLTa9Iyq2gZ4EfCvzTA1abrzs1Rt+yLwJGAucDXwqWa996amVJI1gROBt1bVTWPtOsI67031zAj35qR9bhpKH7yrgA26ltcH/thSLRJV9cfm51+Ak+kMl/hz8zzA0HMBf2mvQvW50e5FP0vVqqr6c1Utr6q7gS9x71Az701NmSSr0fmj/2tVdVKz2s9NtW6ke3MyPzcNpQ/e2cCTk2yc5CHAK4FTWq5JfSrJGs0D6CRZA3g+cAGde3LvZre9gW+3U6E06r14CvDKJKsn2Rh4MvDrFupTnxr6o7/xT3Q+O8F7U1MkSYD/AS6qqsO6Nvm5qVaNdm9O5ufmrMktuf9U1bIkbwZ+CKwKfKWqlrZclvrXY4CTO58dzAK+XlU/SHI28M0k+wG/B/ZosUb1iSTHAzsC6ya5CjgI+Bgj3ItVtTTJN4ELgWXAvzqDpHpllHtzxyRz6QwxuwL4F/De1JR6BvBa4PwkS5p178HPTbVvtHtzr8n63PQrYSRJkiRJrXH4riRJkiSpNYZSSZIkSVJrDKWSJEmSpNYYSiVJkiRJrTGUSpIkSZJaYyiVJEmSJLXGUCpJkiRJao2hVJIkSZLUmv8PmaiJEj/Xa7IAAAAASUVORK5CYII=

The month with the highest return on investment is July, followed closely by November and June.

![download (1)](https://user-images.githubusercontent.com/100429663/171656340-5f77de81-d5bb-47b8-b4e0-d4b757ef69c4.png)

Musical genre had the highest return on investment, followed by Animation.

To further explore these variables, I wanted to see if a given genre found more success (higher return on investment) if the film was released in a certain month of the year.

![download (2)](https://user-images.githubusercontent.com/100429663/171656394-a33a80be-6b45-4caa-b75d-1414ffcfd955.png)

February Musicals, and January Sport films dominated return on investment.

![download (3)](https://user-images.githubusercontent.com/100429663/171656450-cf7d0fd9-4ef9-4ff8-b238-d915dd8c2633.png)

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
