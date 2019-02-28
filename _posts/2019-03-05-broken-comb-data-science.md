---
layout: post
title: "Broken Comb Data Scientists"
date: 2019-03-05
excerpt: "Beyond the T-shape: Why you should follow the broken comb instead."
tags: [opinion]
comments: false
---

Over the past 1 month, I had the opportunity to talk about data science (DS) with people from many different walks of life. They ranged from developers, senior technical leaders, recent graduates, mid-career switchers and aspiring data scientists. While I think it is okay for diverse opinions, it is still necessary to firm up the key details regarding some areas of this field. This post will talk about how a modern data scientist should be (in my opinion). I will also write about how you can get started. I will write this post with the following intents.

## 1. Intents
1. Some common misconceptions of DS.
2. Beyond the T-shape: Why you should follow the broken comb instead (for data scientists).
3. Run-through of DS skills and tools
4. Wow that sounds like a lot of ground to cover. How do I get started?

## 2. Some common misconceptions of DS

**<center>Myth 1: It's all about the cool machine learning algorithms!</center>**

A common misconception of DS is that it is all about the ML algorithms. Oftentimes, many places choose to focus only on the juicy and exciting topics. Usually, they focus on new ML algorithms with futuristic names, new real-life application of DS, how AI can replace humans or promising improved results from some research programme. What they fail to write about are the unglamorous chores such as data pre-processing, feature engineering and exploratory data analysis. This is the bulk of the work in a data science project and is mission-critical to the success of the algorithms that comes much later. As a rough gauge, this usually takes up 70% of a data scientist's time on a project. 

**<center>Myth 2: As long as the project involves data, we need a data scientist!</center>**

For those unfamiliar with DS, it may seem that anything and everything that involves data requires a data scientist. I feel that this stems from the confusion between DS and Business Intelligence (BI) which people are generally more familiar with. In BI, it is more for **Descriptive Analytics** or reporting. I.e. I'm trying to describe the past year financial performance. In DS, we are more concerned about **Predictive Analytics** or **Prescriptive Analytics**. I.e. I want to predict customer churn. 

While there is a difference, I do agree that there are some overlaps between BI and DS. E.g. Business analysts also do revenue forecasting. Isn't that predictive analytics? Well, what happens if you have to incorporate text and image data collected from your company's Facebook page? Can your traditional BI tools handle anything other than tabular data? 

In DS, it is not just about prediction. We have also become more concerned about unstructured data (e.g. text, audio, image) which has formed the main bulk of data existing in the world today. The sheer volume and velocity of data collected and waiting for processing each day are of a completely different scale. Think quarterly sales reporting versus the number of tweets on Twitter per day.

I may have delved too much into this. However, the key point is that sometimes, what you need is not a data scientist but a data analyst or business analyst.

**<center>Myth 3: Data Scientists must know fancy visualisations!</center>**

In DS, a lot of data scientists usually do not go beyond the usual scatter plots, bar charts and line graphs. Basically, we use most of the graphics you can find in Microsoft Excel (We use Python or R to generate these plots). Sometimes we may use the occasional country/world maps, starplot, heatmaps or graph networks but that really depends on your domain (e.g. Telecomm, Transport).

As I have mentioned, we spend the majority of our time pre-processing the data. Usually, for this stage, we will use simple graphs like bi-variate plots to analyse the relationship between features and target. We also plot graphs for model evaluations (e.g. lift charts, ROC). Most data scientists do not have the time to design fluid and interactive graphics. Neither is it part of our core skill set (Just look at a few job descriptions). 

What about those fancy visualisations that you saw online? Probably done by a team of dedicated frontend developers.

## 3. Beyond the T-shape: Why you should follow the broken comb instead (for data scientists)

**<center>T-shaped Data Scientists</center>**

![t-shape]({{ site.baseurl }}/assets/img/t_shape.png "T-shape")
*<center>image credit: futurice</center>*

A lot of people are T-shaped people. T-shaped people are people with deep expertise in a particular area and he also has the breadth to understand the bigger picture. You can think of this guy as the "**Jack of many trades, master of one**". Having the breadth helps because you can stay engaged in a conversation with your broad knowledge without sounding ignorant. A T-shaped data scientist is someone who has worked on a particular application of data science for a long time with some knowledge in other areas. E.g. You have been building Natural Language Processing models for some time and you also roughly know something about other areas like computer vision, data engineering, etc.

As someone who has been in this data science field for the past 4-5 years, I see DS as a cross-disciplinary field with several pillars of knowledge:

* Statistics/Mathematics/Machine Learning (*Even within machine learning, there are several pillars*)
* Business Acumen/Domain Knowledge
* Big Data Infrastructure
* Coding
* Communication/Soft Skills

While knowing everything is quite unrealistic, I feel that this will be something data scientists should be working towards. The T-shaped model is not good enough.

**<center>Broken-Comb Data Scientists</center>**

![broken-comb]({{ site.baseurl }}/assets/img/broken_comb_people.jpg "Broken Comb")
*This image was for Design/Marketing. Replace the words in the image with words from the pillars of knowledge I mentioned above.*

**Broken Comb people are like T-shaped people on overdrive.** Broken comb people do not stop and rest on their laurels after gaining a deep area of expertise and broad breadth. **Learning in depth** does not stop for these people. They are constantly learning, improving and going deeper than expected. While this broken comb concept is still relatively new, I do think that this will be the standard expectation, especially since we live in an age where information is ubiquitous. **Finding much different information is easy. However, mastering all these different information is something else..**

I feel that this is particularly important for a data scientist. The DS field is moving very fast and new things are coming up all the time. It is not enough to just master the regular supervised/unsupervised machine learning algorithms. You have to pick up and master even more complicated algorithms like deep learning. By the time you understand deep learning to a certain level, maybe it is time to pick up reinforcement learning which has gained traction in recent years(remember AlphaGo). That is only in the area of machine learning. How about the other pillars that I mentioned about? What about data engineering? Just because it is a separate job scope does not mean that you can ignore it. You have to pick that up gradually as well.

**Having said all these, in reality, nobody really expects to find someone with all these skill sets. Job descriptions are meant to be the best case scenario. In fact, hiring managers are having a tough time finding people and they usually settle for people with SOME of the skillsets.**

## 4. Run-through of DS skills and tools

**<center>A high level and non-exhaustive list off the top of my head. TAKE NOTE: You are NOT expected to know everything to get started. </center>**

* **Mathematics** 
    * Linear Algebra
    * Calculus
* **Statistics**
    * Probability 
    * Hypothesis testing
    * Sampling
* **Coding** 
    * Python or R
* Data Infrastructure/tools
    * Databases, data processing tools, etc.
* Machine Learning
    * Supervised and Unsupervised learning: See <a href="https://scikit-learn.org/stable/user_guide.html">here</a> :) 
    * Applications: Natural Language Processing, Computer Vision, Graph Networks, Recommender Systems, etc.
* Soft Skills
    * How to explain algorithms to a layman
    * How to link the business problem to data science
    * How to convey results to business

The ones in **bold** are the fundamental topics you need to *get started*.

## 5. Wow that sounds like a lot of ground to cover. How do I get started?

Nevertheless, personally, my career path has been an <a href="https://nhanwei.github.io//how-i-got-started/">amazing journey</a> for me and I had fun all the way. Data science is an exciting and lively field with tons of applications, tons of community support and career opportunities. I do not believe it is ever too late for something to get started but the approach will be a bit different depending on your unique backgrounds:

* If you are still in school, consider taking up coding/mathematics/statistics classes regardless of your main study. E.g. You may be a psychology undergrad/grad, that doesn't mean that you can't transition into DS.
* If you have just graduated and had some working experience, consider taking up MOOCs, Masters if it is within your budget (e.g. SMU MITB, NUS MSBA) or immersive and focused Bootcamps (e.g. <a href="https://metis.kaplan.com.sg/">Metis</a>). I honestly feel that other technical masters will not automatically transition you into a data scientist.
* If you have graduated a long time ago and have tons of working experience, consider Masters if it is within your budget (e.g. SMU MITB, NUS MSBA) or immersive and focused Bootcamps (e.g. <a href="https://metis.kaplan.com.sg/">Metis</a>). You will need more help from experienced instructors and you shouldn't be wasting time muddling around MOOCs or some technical masters. 

I apologise if this post was a lot to digest. Whichever route you choose, don't procrastinate and start today. Feel free to send me an email or linkedin connection/message.

*Full disclosure: I will be teaching in the Metis Data Science Bootcamps*

