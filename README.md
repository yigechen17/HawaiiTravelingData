---
title: "5293 Final Project Proposal"
author: "Group 2: Yige chen yc3986, Weijia Wang ww2589"
date: "2022/2/28"
output: html_document
---

### 1. Question

We are interested in Hawaii as our travel destination for our summer or spring break. As the tourism of Hawaii is well developed, we believe there should be enough data collected that can help us to explore the development of the tourism of Hawaii.

Here we come up with three questions:

1. We want to study about the features of the visitors to Hawaii. Here, the features may include their basic information like age or gender, where they are from, their travel purposes, how do they came here, etc.  

- (What kind of people like going to Hawaii for vacation is Hawaii a good travel destination for students like us?)

2. For our travel plan, we want to see which islands of Hawaii are more popular. What activities are more adaptable to do on different islands? And how long we should spend there considering the average time spent by other visitors.

- (Can we make a perfect travel plan based on the activities of other tourists?)

3. Does pandemic have an influence on the tourism of Hawaii. We may explore this question by studying if the answers of the two previous questions changed in the past two years.

- (Is the tourism of Hawaii influenced by the pandemic? If it is, how bad?)


### 2. Data Source

The official website of the Aloha State

Data: http://dbedt.hawaii.gov/visitor/tourismdata/

A screenshot of the data panel:
```{r}

knitr::include_graphics("D:/【CU】2022 Spring/5293_r/Proposal/1.png")

```



### 3. Links between questions and data.

We found this data by searching Hawaii Tourism public data on Google. This is the tourism data warehouse enable us to customize and download data sets about Hawaii’s tourism industry in difference perspectives.

By inputting different filters and get different outputs from the warehouse, we can find data about visitor arrival, length of stay, their places of departure, destination islands and purposes of travelling from Jan 1990 to Dec 2021. And we may especially concern about the data since 2020 (the period of the pandemic). We believe the data sets contains enough information for us to answer our questions. 

可以添加：
For example:

- For question 1, we can explore the features of tourists by downloading data sets containing their basic information like age, gender, departure place, travel purposes, their daily expenditure in Hawaii, etc.. If it is the majority of visitors are younger people who come from all over the world (meaning a safe place), the money their average expenditure is not high for us, then maybe we could consider Hawaii as a affordable destination.

- For question 2, we can make the travel plan based on what islands do most people go, what activities do they do on each island and  the average time they spend there. All these data could be found on the official data website.

- For question 3, We may explore this question by studying if the answers of the two previous questions (or the pattern of the two data sets) have changed in the past two years.


