# Twitter-analysis
!!!!!NOTE THAT SOME GRAPHICS MADE BY PLOTLY ARE NOT DISPLAYED IN THE CODE!!!!

Method:
This project used Tweepy to scrape tweets from March 31st to April 9th with the hashtag #TrumpIndictment and related ones, just after Trump was indicted. As a result, more than 52,000 tweets were collected during the period.

In order to sort, prepare, and analyse the dataset, Python was chosen to be the main tool, as it has great libraries for text analysis, data processing, and visualisation. As the project mainly focused on the content analysis of the tweets, a data cleaning process took place to guarantee the quality and accuracy of the texts for the analysis, removing irrelevant information such as links and special characters.

Result:

The project used an N-gram model to detect the probability of the occurrence of a sequence of two words in tweets to discover the most popular topics trending on social media about Trump’s indictment. The 30 most present bigrams chart shows ‘donald trump’ is the most popular two-word sequence in the dataset, followed by ‘new york’, ‘hush money’, and "trump indictment'. Most of the two-word sequences found are related to the topic; this shows that not many spams or irrelevant content are included in the dataset after the data cleaning process.
<img width="514" alt="image" src="https://user-images.githubusercontent.com/121313767/235665930-08a068de-8901-48d5-8bf0-e76f6b6a9f79.png">

Furthermore, the study analysed the 20 most popular emojis used in the dataset, which provides additional insight into the emotions and attitudes expressed on the platform. Emojis are a ubiquitous part of online communication, and their use has increased exponentially in recent years, particularly on social media platforms like Twitter. Emojis can be used to convey emotions, sarcasm, humour, and other nuanced meanings that may be difficult to express through text alone. By examining the emojis used in a dataset, it was revealed that 🤣 😂 and 🤡 were among the most used one in the dataset. This suggests that humour and sarcasm are part of many conversations on Twitter related to the topic.
<img width="524" alt="image" src="https://user-images.githubusercontent.com/121313767/235666092-6cf68ae1-51fc-4c58-8324-f910370d74b1.png">

Subsequently, the project visualised the data collected in Wordcloud to detect the most commonly used single words in tweets and examine the popular trends in the conversation on Twitter. Some words were eliminated, such as Donald, Trump and linking words, in order to visualise the importance of other topics. As shown by the Wordcloud below, the main conversation on Twitter was about the criminal charges against former President Donald Trump. Some interesting words that showed up frequently in the tweets included lie, end, and guilty, giving the notion that public opinion is inclined towards the jury’s decision and against Trump.

<img width="524" alt="image" src="https://user-images.githubusercontent.com/121313767/235666166-f17c076f-1dc0-4e7b-b91f-ffd37f47c573.png">

The project also used another Wordcloud to detect the most frequently mentioned (@) accounts in the dataset. @realDonaldTrump is obviously in first place, followed by @DonaldJTrumpJr, @RepMTG (Marjorie Taylor Greene) and @GOP. Looking at the tweets with those mentions, the research found that most of them included negative arguments against Donald Trump and the Republican Party after his indictment.

<img width="524" alt="image" src="https://user-images.githubusercontent.com/121313767/235666202-2ad54f80-caf1-431a-9ef3-f173e3085dee.png">

For the main analysis of the project, the research chose the lexical approach to analyse the content of the tweets collected using Vader (Valence Aware Dictionary and sEntiment Reasoner). Vader is known as an effective method for sentiment analysis that detects polarity (positive, neutral, or negative opinions) within the text, with a range score of -1 to 1 (negative-positive).
<img width="524" alt="image" src="https://user-images.githubusercontent.com/121313767/235666250-78978a1d-20fc-4963-b816-d589d4983b60.png"> 

As shown in the chart above, the dominant sentiment on Twitter regarding Donald Trump’s indictment was largely negative. Looking at the texts in the dataset, many comments showed disgust and anger towards Trump’s actions. The table below illustrates the most retweeted tweet in the dataset, with 14 times retweeted, which also has a critical and sarcastic tone regarding the news. 
<img width="524" alt="image" src="https://user-images.githubusercontent.com/121313767/235666290-9d65188c-be18-4019-a2d5-8b32edf40d19.png">

In the case of sentiment analysis by topic, based on the most popular two-word sequences, the general public's opinion was largely negative towards ‘donald trump’, ‘hush money’ and ’34 felony’. Meanwhile, the tone of conversation related to ‘grand jury’ was relatively positive, as many expressed supports for the jury’s decision.

<img width="524" alt="image" src="https://user-images.githubusercontent.com/121313767/235666328-d0ba895d-13d3-4091-aee1-00b722509b17.png">

Furthermore, in the sentiment analysis by the most frequently mentioned accounts, the replies to @realDonaldTrump and other important figures of the Republican Party, like @SpeakerMcCarthy, @RepMTG and @DonaldJTrumpJr, were negative. 
<img width="524" alt="image" src="https://user-images.githubusercontent.com/121313767/235666366-3fea2168-9754-4e1a-a020-6dd555f4e270.png">

On the other side, examining the replies to @ManhattanDA in the dataset, various Trump supporters showed negative reactions towards the jury’s decisions. 

<img width="416" alt="image" src="https://user-images.githubusercontent.com/121313767/235666397-e3479fa5-9c91-4589-9c92-c43c4797fbde.png">

<img width="414" alt="image" src="https://user-images.githubusercontent.com/121313767/235666414-ca07b9b5-704c-4930-9406-9df4a05133aa.png">

Meanwhile, another protagonist of the event, @StormyDaniels, received support and encouragement online as many members of the public showed a positive attitude towards her based on the text analysis.
<img width="417" alt="image" src="https://user-images.githubusercontent.com/121313767/235666453-ddda2dab-f01f-4040-bb23-a1a9b490ff85.png">
<img width="414" alt="image" src="https://user-images.githubusercontent.com/121313767/235666466-ca9547a5-26a9-4808-81b2-f5fbece0075f.png">

Conclusion and recommendation:
Trump’s indictment has received a lot of attention from the public, with different opinions coming from both sides of the political spectrum. With the level of analysis undertaken in this research, it is difficult to provide a definitive trend or sentiment of the Twitter conversation on the subject, but these preliminary findings indicate a negative reaction and sarcastic tone towards Trump’s action, as well as support and a positive attitude towards the jury and Stormy Daniels.

From the collected dataset, the study explored the corpus of tweets to get ideas about the popular topics in public discourse as well as the emotions related to the event. To do so, many text processing techniques were used for analysing the tweet content and finding trends and sentiment under the text. This allowed the project, to present sentimental polarities in general, by topic and account.

While sentiment analysis presents certain challenges, such as data bias, language nuances, and the limitations of textual analysis using computer programmes, it has proven to be a powerful tool for analysing large-scale social media data and can contribute to a deeper understanding of public sentiment and opinions towards significant events.

As limited by the time and resources for this project, the report hasn’t covered some aspects, such as the links between the most active Twitter accounts in the dataset. Therefore, it is suggested that future studies cover more analysis of the dataset to investigate these links and the potential influence of active accounts on the sentiment expressed in the dataset. Additionally, incorporating other forms of social media data, such as Instagram and Facebook, could provide a more comprehensive understanding of public sentiment and attitudes towards the topic in question.

Bibliography:
Goyal, G. (2021) Twitter Sentiment Analysis Using Python | Introduction & Techniques. Available at: https://www.analyticsvidhya.com/blog/2021/06/twitter-sentiment-analysis-a-nlp-use-case-for-beginners/ [Accessed: 20 Abril 2023]

Gaisbauer et al. (2021) Ideological differences in engagement in public debate on Twitter. Available at: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0249241 [Accessed: 20 Abril 2023]

Kumar, P. (2017) An Introduction to N-grams: What Are They and Why Do We Need Them?. Available at: https://blog.xrds.acm.org/2017/10/introduction-n-grams-need/
[Accessed: 20 Abril 2023]
![image](https://user-images.githubusercontent.com/121313767/235665397-a9c43c71-356c-42d6-bbe5-8c516176b6cf.png)

