# TMDB-analysis


this project is analysis for this dataset where I had two questions and did the analysis to answer them 

[The link for the dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
**\*the dataset is a little diffrent because the dataset I have is a little bit old**
---

## Introduction

### Dataset Description 

>TMDb movie dataset contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue 
>### columns in this dataset : 
>- imdb_id
>- popularity
>- budget
>- revenue	
>- original_title 
>- cast 	
>- homepage	
>- director
>- tagline	
>- keywords	
>- overview	
>- runtime	
>- genres	
>- production_companies	
>- release_date	
>- vote_count	
>- vote_average
>- overview 	
>- runtime 	
>- genres 	
>- production_companies 	
>- elease_date 	
>- vote_count 	
>- vote_average 	
>- release_year 	
>- budget_adj 	
>- revenue_adj

    



### Questions for this analysis


>Question 1: deos the month release will affect the popularity or the vote_average?

>Question 2: what is the most genres was made in the dataset and does the genere affect the the popularity?

---

## Data wrangling/Data cleaning

in this dataset there was missing values and some additional columns so I handled them for every case different solution details in the full file of the analysis.

---

## visuals and their describtion

in this section for the first question there are 3 visual and the second question have 2 visuals 


### Q1: deos the month release will affect the popularity or the vote_average?

![q1p1](https://github.com/Asem-001/TMDB-analysis/assets/117676536/013033c2-ad83-4445-a377-df201aafde4b)

As we can see the movies release in in every month nearly evenly now we will see if the month affect the popularity or the average vote

---

![q1p2](https://github.com/Asem-001/TMDB-analysis/assets/117676536/0048e865-ba3f-4884-a1c0-073fe81556cb)

we can see may,june,july,november,december is the hieghist in trems of popularity and january and september is the worst in terms of popularity so the month release have a slight effect on the popularity

---

![q1p3](https://github.com/Asem-001/TMDB-analysis/assets/117676536/2902c47a-8418-4aaa-b3e3-84cd0e22da02)

and in vote average the release month doesn't effect the vote which is something I didn't expect

---

### Q2: what is the most genres was made in the dataset and does the genere affect the the popularity


![q2p1](https://github.com/Asem-001/TMDB-analysis/assets/117676536/2349db87-1edb-4cd6-94b5-5cb831c88415)

we can see that darama is the number one genre choice for the production companys then comedy then thriller

---
![q2p2](https://github.com/Asem-001/TMDB-analysis/assets/117676536/69bf46a8-9484-4382-ba9c-e623c8382944)


But in terms of popularity the adventure then science fiction then fantsy are top performer in terms of popularity


---


## Conclusions

> finally I found that the month of release doesn't have an impact on the vote but there is some effect on the popularity and this a place to start investagating more it might lead to something helpfull for the industry but the genre it sure affect the popularity but the industry produce genres that not the most popular and this a place to see why and here is my dataset limitation is the budget and the revenue are both lacking because hlaf of the rows are zeros and this will not make the analysis near accurate so I couldn't anlayse in those columns and I think the directors affect on the movies is something should be considered in future analysises














