# COVID-19-sentiment-analysis-dataset-Weibo
## Sentiment Analysis on Chinese Weibo regarding COVID-19
This dataset contains the unlabeled Weibo posts and labeled Weibo posts used for sentimental analysis about COVID-19. 
### Unlabeled Weibo Data
 We used Weibo as a platform to crawl the top 50 searched hashtags (a total of 5800) and their corresponding search volume as of 23:59 every day from January 19, 2020 to May 31, 2020. Besides, we also considered the hashtags that are related to the COVID-19 (a total of 1123), and used them as a basis to crawl 1,000 Weibo posts under each hashtag (webpage restrictions result in only 1,000 Weibo posts under each hashtag). In summary, the total number of Weibo posts on the hashtag related to the COVID-19 is 1,681,265, and the number of users is 399,231. This part of data consists of userid and text. In order to protect user privacy information, we performed data replacement processing on userid. If you want to get the real userid, please send an email to xiaotinglvtt[AT]gmail[dot]com.

### Labeled Weibo Data

We performed sentiment analysis on Weibo posts related to COVID-19. Therefore, we constructed the COVID-19 sentiment analysis dataset that consists of the following three parts, including NLPCC sentiment analysis dataset, emotional conversation dataset provided by the team of Professor Huang of Tsinghua University and our own annotated dataset. Instead of using coarse feeling, in this work, we annotated the Weibo posts by 7 fine-grained feelings, i.e., fear, anger, disgust, sadness, gratitude, surprise, and optimism.

After carefully validation, we form the sentiment analysis data set that consists of 21,173 Weibo posts falling into 7 sentiment categories, e.g., anger, disgust, fear, optimism, sadness, surprise, and gratitude. The number of posts for each category of sentiment is shown in the following table:

|Sentiment category|Number|
|:----:|:----:|
|Fear|3227|
|Anger|3175|
|Disgust|2203|
|Sadness|2756|
|Optimism|3595|
|Gratitude|3072|
|Surprise|3145|

The correspondence between sentiment categories and labels is as follows:

|Sentiment category|Label|
|:----:|:----:|
|Fear|0|
|Disgust|1|
|Optimism|2|
|Surprise|3|
|Gratitude|4|
|Sadness|5|
|Anger|6|

Refer to our paper for more details:

Xiaoting Lyu, Zhe Chen, Di Wu, Wei Wang.
#### Sentiment Analysis on Chinese Weibo regarding COVID-19. NLPCC2020

Please kindly cite our paper if this paper and the dataset are helpful. (Citation info will be released soon.) 
