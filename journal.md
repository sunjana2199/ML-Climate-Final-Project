>>ML & Climate | Journal
>>Sunjana Ramana Chintala (sc4921)

January 30, 2022

The last week was mostly about exploration. Though initially, I knew that working on Tracking
Carbon Emission would be my goal for this semester, I didn’t really arrive at how I was going to
achieve it. Machine Learning of course is one fascinating topic that I would be prepared work
with countless hours. I was looking for a sector to apply this to. My background is in Electrical
Engineering and I have done quite a lot with energy per se, Hence working with energy again
would be interesting. I skimmed through the internet for datasets, looked for meaningful data
and found the website which is " ourworldindata". It is an interesting website and I am looking
forward to working with the data I obtained from there

February 7, 2022 

As a part of the data exploration process, this week I started off with understanding the concepts of Time Series Analysis.I have now a strong hold on concepts such as persistence model, ADF test, Autocorrelation, Partial Auto Correlation and ARIMA. As weekly dicussions have also included a variety of concepts like Linear Inverse Modelling , I wanted to see if this concept could be applied to the current case. However, due to the limitations in the method, I think the concept cannot be applied to my study. Overall, I am looking forward to applying these concepts to the dataset.

February 15, 2022

This week was more about, data cleaning and pre-processing. I dedicated majority of my time to understanding the variables and analysisng how the data can be used for further analysis. Initially, I thought that I might want to collect data from the source and simply predict how much of the green house gas emission scenario would change over the course of time for countries around the world. But in order to arrive at this, I realized that the current dataset would not serve the purpose, mainly because there are plenty of missing values within the dataset itself. I tried several procedures to correct the dataset but they still seem to be ineffective.


February 22, 2022 

I was able to overcome the hiccup in the last week and now my data seems to be ready for analysis. I fit the dataset to the baseline model. Now I am looking to explore it with all the methods that I have studied in week 2. Hopefully,, this should bring out some insight.

March 1, 2022

After attending the Class today, my curiosity was piqued by the concept of Causality. I realized that my project could extend into something bigger.
What if Energy Demand could have a causal relationship with Social Media Sentiments(Priya mentioned that Social-Media Sentiments is a good avenue to extend energy research into)

Essentially, I would wanna delve deeper into whether "Do the spikes in energy demand on certain days of the year have a causal relationship with trending media topics?"
This looks like a good study to focus on.

Up until now my progress is as follows:

- I realized that the dataset that I already have is wanting.
Hence I explored further for a more meaningful dataset and foind the EIA website.
The EIA website has more structured data. I was able to retrieve the Energy Demand Data for New York from 2015-2022.

- This dataset was relatively clean. However, I did spend time to refine it further and save it to csv formats.

- I spent time to preprocess the data and did some basic data exploration.

- I applied to to a moderaltely strong ARIMA model and tried to select best hyperparameters for the same.

## 2022-03-07 check in: alp

Looking good. Thank you for the frequent updates. How are the results from your most recent modeling approach? I would recommend trying to get some initial results sooner than later; you can extend your ideas from that point with more insights.

## 2022-03-14 

After taking your inputs into consideration, I was able to produce a few initial results with the ARIMA Model. Though the Model was not stable in the beginning, eventually it worked and gave the results I desired. The final output is better that that produced by the baseline.

## 2022-03-20

In the last week, I was trying to link NLP with Time Series Forecasting. My idea here is to be able to stream Social Media Data for outliers in Energy Demand Dates. I was able to Set Up GCP with the credentials given and do a little bit of pre-processing.


## 2022-03-28

In the past week, my task was to finalize which Social Media platform would be best for data collection. I was looking at a few open-source APIs for streaming and found that Twitter and Reddit have APIs. This is a good start for Social Media Streaming. 

##  2022-04-07

Though the APIs were avaialble, the limitation was that they do not allow streaming for over 30 days. I have been looking for an alternative and found a library called snscrape which allowsing scrapin for over 10 years. I have used this to stream twitter data for the outlier dates. I was sure to include one additional day to get rid of any inconsistencies.

## 2022-04-14

I studied topic modelling techniques to make sense of the data collected. After cleaning and pre-processing, I used LDA and GSDMM to find the most relevant topics on these dates.

After Brainstorming I feel like I have been able to find a link between the topics and the Energy Demand Data.

## 2022-04-20

Last week was mostly about the presentation of the work done until now. After receiving suggestions on my progress, I hope to use some evaluation metrics to see if the link that I found really holds.




