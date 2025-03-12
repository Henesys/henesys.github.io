---
title: "Analyzing Data from SBS's Variety Show Running Man (런닝맨): Week 1"
description: "Portfolio Project"
summary: "Analysis, science and visualization of data collected from the South Korean variety show 'Running Man' (런닝맨)"
date: 2025-03-05
categories: ["Blog"]
tags: ["Data Analysis", "Data Science", "Data Visualization"]
draft: false
---

{{< figure
src="RunningMan.png"
alt=""
caption=""
>}}

## How Did I Get Here?

> "Having a project, even if it's terrible, is better than no project at all."

At the end of 2024, I did not expect to enter the job market after completing my master's degree.

Initially, I had planned to graduate, move back to South Korea, serve my mandatory military conscription and start working.

Instead, on the day of my finals, I read news about how the [president of South Korea declared martial law](https://en.wikipedia.org/wiki/2024_South_Korean_martial_law_crisis), setting off a massive flurry of information (both real and fake), ranging from something as serious as a North Korean invasion to something as trivial as a bad joke that gained a bit of traction.

Needless to say, the aftermath of this issue and the consequences that followed have not left me impressed. Therefore, after days of deliberation, I decided to enter the job market in mid-January.

Finding myself woefully unprepared and outmatched by other candidates after dozens of applications, I decided to get back to basics and approach the goal of getting a job offer like an assignment: something I've done for years at this point.

After seeing testimonies (and complaints) about how recruiters constantly see the same Kaggle Titanic competition "project", COVID-19 dataset analysis and TODO app, I decided to start a project using a dataset I collected by myself and try to make something useful out of it.

## About The Show

Running Man (런닝맨) is a TV show that first aired in July 11th, 2010 and is South Korea's *longest* running variety show.

Although the show has evolved and change drastically since its conception, the core premise- a standard cast with occasional guests invited to play games, compete in quizzes, complete missions has been preserved.

I'm personally a long-time viewer of the show and it has accompanied me weekly in middle school, high school and even now as an adult to some extent.

The longevity of the show comes with its own highs and lows. Changes in the format, showrunner (colloquially known as PD in Korea), main cast and changes in time have all affected the viewership of the show during the almost 15 years it has been on air.

## About The Data

As a fan of the show, my goal with this project is to create a dataset with readily available information and combine it with some unique points of interests in an effort to visualize and analyze its performance through time.

Information about the show's episode number, air date, guests and ratings have been somewhat arranged in a tabular format in [Wikipedia](https://en.wikipedia.org/wiki/Running_Man_(TV_program)#Ratings).

There are also people who have published datasets on [Kaggle](https://www.kaggle.com/datasets/zeeniye/running-man-korean-show-wikipedia/data) webscraping from the same Wikipedia source.

My intention while creating this dataset is to again, create my custom dataset and enhance it via information available on [Namu Wiki](https://namu.wiki/w/%EB%9F%B0%EB%8B%9D%EB%A7%A8#s-3) and some manual data collection I will be conducting by myself.

## Initial Plans

Undertaking the creation of the dataset might sound easy on paper, but it can quickly become convoluted once you consider certain tasks that need to be addressed properly.

Right off the bat, I'm seeing some potential data validation issues between Wikipedia, Namu Wiki, Parrot Analytics, TNmS Ratings and Naver (Later Nielsen) Ratings.

In addition, I'm seeing inconsistencies with the way certain names are romanized from Korean to English, which means I may consider opting to sanitize the dataset by entering guest names in Korean entirely and finding a way to disambiguate different guests with the same Korean name.

Results, teams and differences in the *dimensions* of the dataset through out different years (e.g. 2010 cast members are different than 2025 cast members) will also require additional attention.

I plan to try and build a working version of the datasets in the second week of this project and conduct feature engineering as needed if additional touches are required for proper use.