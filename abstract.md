**ABSTRACT**

New York's energy bill fluctuations are a growing concern of the people. Due to the unpredictable changes in energy demand, suppliers struggle to allocate sufficient resources for energy production. This imbalance causes energy bill rates to surge which leads to residents not being able to plan their household budgets accordingly. The goal of this project is to build a robust Time Series Forecasting Model that predicts Energy Demand effectively. In addition to this, the project also attempts to investigate the reason behind the anomalous highs and lows in energy demand by studying social media sentiments. Data for Energy Demand is collected from New York ISO website. ARIMA model is built for Time Series Forecasting. Twitter Data is streamed for anomalous data and topic Modeling techniques like LDA and GSDMM are used for the analysis of textual data.

**ABOUT THE DATASET**:


In this project, three different kinds of datasets are used. They are as follows:

1.) Energy Demand Forecasting Data

Energy Load Data is collected from the EIA website through their open data API. Energy Information Administration (EIA) is a part of the U.S. Department of Energy. The U.S. Energy Information Administration (EIA) is the primary agency of the U.S. Federal Statistical System. They are responsible for collecting, analyzing, and disseminating energy information and are involved in policymaking. EIA website has APIs for a variety of data on coal, petroleum, natural gas, electric, renewable and nuclear energy. This dataset is in a time series format with data points from 2015 to 2022.

2.) Outlier Data 

Outler Data is collected from the original time series dataset by establishing a threshold which gives a collection of dates. More information about the process will be discussed in the Methodology section.

3.) Streaming Data

To stream Twitter Data, the best tool for use is the Twitter API. However, this API does not allow streaming Twitter data that is more than a month old. The EIA load data consists of dates from 2015 onwards. Therefore to stream tweets from 2015 onwards, an alternative is needed. Other libraries like Tweepy, GetOldTweets2, TWINT etc are useful but do not fully serve the purpose as they either consume a lot of time or are expensive. Therefore, a viable tool was required. 

"SNSCRAPE", a powerful scraping tool, helps in this regard. This tool can be used for obtaining twitter data on users, user profiles, hashtags, searches, threads, and list posts. Using this tool, tweets with high engagement are streamed to places in and around New York.


