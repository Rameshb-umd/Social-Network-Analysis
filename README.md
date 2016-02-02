

Social Network Analysis of 2016 US Presidential Election Candidates
* * *

INST 633 - Final Project Report

Apoorva Ajmani

Karan Kashyap

Ramesh Balasekaran

GitHub Repository : [https://github.com/Rameshb-umd/Social-Network-Analysis/][1]

* * *

Introduction and Background

Social Media's presence is ubiquitous today. Its extent can be realised with Facebook's 1.55 billion monthly active users. As Social Media grew from its embryonic state in 2004, it gradually transformed into a communication platform on which governance, news, protests and friendships originated and sustained. Around the world, social media consistently plays a major role from managing natural disasters to winning election campaigns. As many political candidates started using social media to mobilize and influence voters, the social media companies also started to realize the opportunities of using data created in this communication platform to predict and understand the outcome of an election campaign. With less than a year remaining for the US Presidential Election 2016, Election campaigns are in full swing and yet again social media is poised to become a game changer. Social Media's major role came into effect during Obama's 2008 presidential victory, It was not a surprise that one of Obama's key strategist was Facebook co-founder Chris Hughes (Soumitra Dutta &amp; Matthew Fraser, 2008). Even in current 2016 US presidential election social media's role has been noteworthy. Twitter has rolled out special features like $Cashtags to aid candidates in raising funds for their election campaigns (Reuters, 2015). Bernie Sanders who started the year 2015 with 0 followers in Twitter now has almost 1.4 million followers, more than triple the followers of Jeb Bush and Chris Christie combined. Social media's excessive use as a part these campaign strategy is due to the fact that it is able to reach a variety of audience and get the attention of the millennials.

Objective

The impact of social media in elections has been studied extensively. Our objective here is to study the social network of the two prominent election candidates - Hillary Clinton and Donald J. Trump. The main aim of the paper is to understand the reach of Hillary Clinton and Donald J. Trump among Twitter users and how their social media strategy is helping or affecting their election campaign.

Literature&nbsp;Review

Even though social media's history started as early as 1997 with the emergence of Six Degrees&nbsp;(Drew Hendricks, 2013), research on social media's impact on election results were not studied or researched until it grew exponentially from 2004 with the launch of Facebook and Twitter. Research on social media's impact on election results started with social networking sites that were predominantly blogs. Initial research, after studying the impact of blogging and hyperlinking in 2004 U.S Presidential&nbsp;Campaign, stressed the need for user-friendly and interactive websites with more options for user participation, (Andrew Paul Williams et al, 2006).

In 2008 Presidential election, Obama's strategy of using his social-networking website mybarackobama.com, known as MyBO enabled more user interaction, grassroot mobilization and ultimately played a major role&nbsp;in his victory (Williams and Gulati 2008). Usage of social media in election campaigns evolved from websites like blogs and hyperlinking in 2004 to social media heavyweights like Twitter and facebook in 2008, as the results of Obama's victorious online strategy&nbsp;(Tumasjan, Andranik, et al, 2010). This led to multiple types of research on predicting election results based on Twitter data. Simple Sentiment Analysis on Twitter data correlated with public opinions collected from various survey results from 2008 to 2009 strongly indicated that social media analysis can supplement time intensive polling during&nbsp;Presidential Elections (O'Connor, Brendan, et al, 2010). On the other hand, social media's predictive analysis on 2010 presidential election did not correlate with the results of the election&nbsp;(Gayo Avello, D., Metaxas, P. T., &amp; Mustafaraj, E., 2011). Conflicting claims from the two researches were based on data collected before 2010 and also took into consideration only the tweets to predict the results.

Studying social networks and its impact in the political arena opened up new ways of analysis and claims and also overcame the shortcomings of using just text for predicting results. Experimental studies to measure the effects of social influence online led to many debates on whether political influence were facilitated &nbsp;by "weak ties relationship" or "strong ties relationship". During 2010 US Congressional elections a randomized and controlled trial of political mobilization messages were delivered to 61 million Facebook users and the results were studied. The reports showed that the messages not only influenced the persons who received the message directly (Strong ties), but also their friends and friends of their friends (weak ties). Furthermore, the influence of these messages transmitted among close friends were four times the effect of the messages itself, indicating the importance of strong ties in influencing behaviour&nbsp;change (Bond, Robert M., et al, 2012). Combining these results with decades of research on understanding the impact of Interpersonal, Media, and Organizational Influences on Presidential Election indicates that political choices are affected&nbsp;to a significant degree by the flow of information from the decisionmaker's immediate social network (Beck, Paul Allen, et al, 2002).

Further, diving deep into social network to analyze the political discussion practices has produced interesting results. Studies have shown that large egocentric networks were more politically engaged (Lake and Huckfeldt 1998) and also discussed politics more often (Moy and Gastil 2006). Study focused on individual's role in a social network and its authority over political influence indicates that people with high betweenness centrality were less inclined to be neutral and were more inclined to attempt political persuasion.

Research questions and Setup

As discussed above, social media has started acting as a game changer in Presidential Elections. This is evident from the amount of expenditures being done&nbsp;on social media which approximately accounts for more than half of the $1 billion budget for digital media&nbsp;(R. Kay Green, 2015). As a part of our project, we will be doing research and analysis of the below questions.

1. Do people use social media as a source of information?
2. How does the information flow through the candidate's social network?
3. Do people with high betweenness centrality acts as political influencers?
4. Can a candidate's primary opponent from the opposition party as well as the same party be identified from their social network?

The data for our analysis has been collected from Twitter for two presidential election candidates: Donald Trump (Republican) and Hillary Clinton (Democrats) using multiple popular and current hashtags. Like: #Trump, #HillaryClinton, #Trump2016, #Hillary2016. Twecoll and NodeXL were used to collect the data from Twitter API and Gephi was used to visualize the network.

Results and Discussions:

In order to answer our first research question, we conducted an online survey to gather information about user's views on social media as an information source. An online survey was created and shared with people in our social network to record their responses. The respondents of the survey were predominantly from the age group of 22-30 spanning across two countries (India and United States of America). In Total, 62 people responded to the survey, the survey provided an overview of what young population thought about the social media, how dependent they are on social media and how social media influences their decisions.

1. How would people like to be informed about global news?

![](http://rameshbalasekaran.com/FinalProject/images/image02.png)

Fig. 1

67.74% of the people relied on social media to get daily updates about the world as opposed to 32.26% of the people who still followed the traditional news channel viewership to gain information.

2\. Which social media website do people visit frequently?

![](http://rameshbalasekaran.com/FinalProject/images/image05.png)&nbsp;

Fig. 2.

After the advent of social media, many people were hooked onto it and started using it almost every day. We can clearly infer from the bar chart that many people use Facebook more frequently as compared to other social networking sites like Twitter, Tumblr etc. But we cannot overlook the fact that of all the people who took the survey almost 80% are from India and since Twitter is not that widely used in India, these stats can be deceiving.

3\. How many Twitter users people generally follow?

![](http://rameshbalasekaran.com/FinalProject/images/image03.png)


Fig. 3.

This result was expected, almost 80% of the people who took our survey follow less than 100 users. 18.03% people follow 100-500 people and 4.92% people follow &gt;500 Twitter users. &nbsp;

4\. Visitors of social media site - consumer or producer of information?

![](http://rameshbalasekaran.com/FinalProject/images/image11.png)

Fig. 4.

In this question we try to categorize our sample into two groups ie Consumer of Information - the person who visits various social networking sites to grasp information about the world and Producer of Information - the person who voices his opinion by sharing, commenting, tweeting etc. From the above bar graph, it is evident that people basically use social media to gain information. Thus social media plays a pivotal role in keeping people informed.

5\. Does social media influence people's decision?

![](http://rameshbalasekaran.com/FinalProject/images/image07.png)

Fig. 5.

From the above graph, we infer that only 29.03% people are influenced by social media. However since we conducted this survey on a sample size of 62 we can expect this % to increase further, Many people do take into consideration other user's opinions expressed on social media eg. movie reviews. Thus, we can conclude from our survey that social media is used extensively by many users as a source of information.

Information flow through social network

@realdonaldtrump analysis

| ----- |
|

Layout &nbsp; &nbsp; &nbsp; : Yifan Hu

Node Size &nbsp;: Betweenness Centrality

Color &nbsp; &nbsp; &nbsp; &nbsp; : Modularity Class

Density &nbsp; &nbsp; &nbsp;: 0.013

 |

Degree Range &nbsp; &nbsp;:&nbsp;6 - 1366

Node &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : 298

Edges &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;: 1184

Average Degree :&nbsp; 7.946

 |

On January 18th, 2016, NodeXL was used to extract tweets with the keyword, 'RealDonaldTrump'. Limit of 10,000 tweets was set and a network was created with people who mentioned '@realdonaldtrump' in their tweets. The network was then loaded and visualized in Gephi. To remove users who are loosely bound in the network, nodes with degree range &lt; 6 were filtered to result in the above network. The directed edges between the nodes represent that the users mentioned each other or replied to each other in their tweets. The node size was adjusted as per the betweenness centrality and the color was set as per the modularity class.

![](http://rameshbalasekaran.com/FinalProject/images/image01.png)

Fig. 6. Donald Trump's Network showing the information propagation

Observations:

From the network visualization, three prominent communities were identified and color coded - Blue, Red, and Green. Primarily, Blue community constitutes of Hillary Clinton and her supporters, Red community consists of Ted Cruz and his supporters and Green community consists of Donald Trump and his supporters. 'ibegoodnow' of green community and 'thegreatfeather' of the pink community have the highest betweenness centrality. Three communities identified form three clusters. Hillary Clinton is connected to the other clusters via only one user, 'MiltonMiller14' while Ted Cruz clusters and Donald Trump clusters are connected via multiple users indicating they belong to the same party. &nbsp;

Analysis:&nbsp;

The presence of the blue community which comprises of Hillary Clinton and her followers is very interesting, as she belongs to the Democrats as opposed to Trump who is a part of the Republicans. Thus, we can clearly observe the two opposing parties and their emerging contenders in this network. Another interesting point to notice is that people who are tweeting about Donald Trump are also tweeting about Hillary Clinton. This can be interpreted as an indication that Trump supporters consider Hillary as his biggest competition and thus, she is mentioned in most of the tweets directed towards Trump. The important node in the red cluster is that of Ted Cruz, who is the member of the Republican party. His presence in this network might be due to the fact that he is competing against Trump to emerge as the presidential candidate for Republicans. The important node in the green cluster is that of Trump himself and his followers who tweet about him and his ongoing campaigns.

The highest betweenness centrality is of Trump supporters who are responsible for the propagation of information from one part of the network to the other. For example, the user 'thegreatfeather'&nbsp;has the highest weight i.e. he has been tweeting extensively in the support of Donald Trump and also has a high betweenness centrality. Some of his tweets are "That's Right we're for Mr Trump", "Mr Trump, make America great again!" etc.

@hillaryclinton analysis

| ----- |
|

Layout &nbsp; &nbsp; &nbsp;: Yifan Hu

Node Size : Betweenness Centrality

Color &nbsp; &nbsp; &nbsp; &nbsp;: Modularity Class

Density &nbsp; &nbsp; : 0.011

 |

Degree Range &nbsp; &nbsp;:&nbsp;3 - 537

Node &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : 204

Edges &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;: 474

Average Degree : 4.64 &nbsp;

 |

On January 18th, 2016, NodeXL was used to extract tweets with keyword, 'hillaryclinton'. Limit of 10,000 tweets was set and a network was created with people who mentioned '@hillaryclinton' in their tweets. The network was then loaded and visualized in Gephi. To remove users who are loosely bound in the network, nodes with degree range &lt; 3 were filtered to result in the above network. The directed edges between the nodes represent that the users mentioned each other or replied to each other in their tweets. The node size was adjusted as per the betweenness centrality and the color was set as per the modularity class.

![](http://rameshbalasekaran.com/FinalProject/images/image08.png)

Fig. 7. Hillary Clinton's Network showing the Information propagation

Observations:

From the network visualization, three prominent communities were identified and color coded as - Purple, Blue, and Green. Primarily, purple community constitutes of &nbsp;Hillary Clinton and her supporters, blue community constitutes of Bernie Sanders and his supporters and the green community consists of Trump and his followers. 'Redrising11' and 'Dyniace' have the highest betweenness centrality in this network and are tweeting extensively in the support of Hillary Clinton. Another Interesting find is that both 'CNN' and 'CNN_politics' are part of Donald Trump's network.

Analysis:

As observed earlier in Trump's network where Hillary Clinton was part of his network; similarly Donald Trump has a fair share in the network of Hillary Clinton which is a strong indication that both the party's supporters consider them as the front runners in the upcoming US Presidential Elections. The edge weight indicates the number of times a person has tweeted about Hillary, surprisingly in this network it was observed that Barack Obama has a direct edge with Hillary Clinton and has been tweeting about her lately.

Also, the presence of Bernie Sanders in this network indicates that he is another candidate trying to emerge as the single most powerful leader for Democrats and has his own cluster and set of supporters. 'Redrising11' comes across as the biggest supporter of Hillary Clinton with various tweets in support of her election campaign. Another interesting observation from the network was the presence of 'CNN' and 'CNN_politics' node in Bernie Sanders community. Many people in Bernie Sanders community not only replied or mentioned Bernie Sanders in their tweets along with Hillary Clinton but also mentioned or replied to CNN. This also shows that when CNN carried out information on Hillary Clinton, many Bernie Sanders followers replied to CNN's tweet and information propagated to Bernie Sanders supporters network as a result.

Visualizing social network of politically active users

#Trump2016 - Visualizing Donald Trump's Social Network

| ----- |
|

Layout &nbsp; &nbsp; &nbsp; &nbsp;: Yifan Hu

Node Size &nbsp; &nbsp;: Betweenness Centrality

Color &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : Modularity Class

Density &nbsp; &nbsp; &nbsp; &nbsp;: 0.073

 |

Degree Range &nbsp; &nbsp;:&nbsp;10 - 557

Node &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : 402

Edges &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;: 11742

Average Degree :&nbsp; 58.418

 |

![](http://rameshbalasekaran.com/FinalProject/images/image17.png)

Fig. 8. Social Network of active Donald Trump followers

On January 19th, 2016, Twecoll was used to extract list of tweets with '#Trump2016' from Twitter. 10,000 tweets were collected after this process. From the dataset a subset of 998 random unique users was parsed and saved as a new file. To the above list two users were added, '@realdonaldtrump'&nbsp;and '@hillaryclinton'. The newly created file was then passed to Twecoll to generate a network from the 1000 nodes. The network was then loaded and visualized in Gephi. To remove users who are loosely bound in the network, nodes with degree range &lt; 10 were filtered to result in the above network. The directed edges between the nodes represents that the source user follows the target user. The node size was adjusted as per the betweenness centrality and the color was set as per the modularity class.

Observations:

From the network visualization, three prominent communities were identified and color coded - Purple, Blue, and Green. 'katrinapierson' of purple community, 'sandiv11' of blue community and 'theratzpack' of the green community have the highest betweenness centrality. The network has a density of 0.073.

Analysis:

Donald Trump's Twitter feed acts as a critical way of communication with his 5.81M followers. This intense network collaboration is evident in Fig. 8. Such kind of network enables rapid communication across all the followers of Trump. Follower's profile consists largely of retweets. 'Retweeting' assists in social interaction, expanding the network and contributes immensely in solidifying Trump's brand. Such a strongly connected social network is a rare find in social network analysis, in order to further confirm that this network was not formed by biased nodes with the maximum edge the whole process was repeated twice with random 1000 nodes and the results were consistent. The degree distribution chart also followed Power law distribution indicating the results were not an anomaly.

&nbsp;![](http://rameshbalasekaran.com/FinalProject/images/image16.png)


Fig. 9. Degree Distribution of Donald Trump Social Network (Random Sampling)

![](http://rameshbalasekaran.com/FinalProject/images/image10.png)

Fig. 10. Social Network of Active Donald Trump Followers (Filtered)

For the above visualization, nodes with degree &lt; 100 have been filtered out to sight a clearer picture. It can be clearly observed that the blue and the green community are well connected. The purple community consists of a lot of politically important people, like realdonaldtrump - official profile for Donald Trump, katrinapierson - National Spokeswoman for Donald Trump's presidential campaign, michaelcohen212 - an executive at the Trump Organization, waynedupreeshow - Writer for The Political Insider. Owing to their importance these individuals have a high number of tweets and a large number of followers. The blue and green community primarily consists of Trump's followers who follow these individuals. These nodes are well connected as followers have a tendency to connect with people who are supporting the same cause, in this case supporting Donald Trump. These nodes are mostly spread across Nevada, Pennsylvania, New York and few other states where Trump enjoys maximum support.

Below figures shows the analysis of the three communities. Random nodes from green, blue and &nbsp;purple community were selected from the network and their bio, followers count and number of tweets and recent tweets from Twitter were analysed to understand the three communities in the network.

![](http://rameshbalasekaran.com/FinalProject/images/image12.png)

Fig. 11. Green Community Analysis (Twitter Account | Bio | Followers Count | Tweets Count)

![](http://rameshbalasekaran.com/FinalProject/images/image15.png)
Fig. 12. Blue Community Analysis (Twitter Account | Bio | Followers Count | Tweets Count)

![](http://rameshbalasekaran.com/FinalProject/images/image14.png)

Fig. 13. Purple Community Analysis (Twitter Account | Bio | Followers Count | Tweets Count)

![](http://rameshbalasekaran.com/FinalProject/images/image04.png)

Fig. 14. Social network of active Donald Trump followers (Degree &lt; 156 filtered)

To analyze the network further, the network was further filtered and visualized. As the degree range keeps on reducing, the number of nodes kept on decreasing significantly. Considering that the purple community belongs to the prominent individuals, the count of purple nodes is comparatively less as to blue nodes and green nodes, because leaders are few while followers are more in number. Amongst the blue and green community, there are few users who have a high number of followers from both the communities. These are those individuals who are significant in transferring of information within a community, like 'philmonaco67' of the blue community.

Egocentric network analysis of Hillary Clinton.

![](http://rameshbalasekaran.com/FinalProject/images/image09.png)

Fig. 15. Egocentric network of Hillary Clinton in Donald Trump's Network

As per the above egocentric network of Hillary Clinton, we can clearly see that Hillary Clinton is followed by lots of unconnected individuals (black dots). Her connections with the green and blue community, who prominently belong to Trump's followers are less as expected. The few connections with the purple community are with those users who are not ardent supporters of Trump and do not tweet about him with as much frequency, like oraztex, ranamayle, paulrdube1. Comparing this network with the sentiment analysis which is discussed in this paper it is clear the nodes connected to Hillary Clinton are the people who use "#Trump2016" in their tweets to convey a negative message about Donald Trump.

#Hillary2016 - Visualizing Hillary Clinton's Social Network

| ----- |
|

Layout &nbsp; &nbsp; &nbsp; &nbsp;: Yifan Hu

Node Size &nbsp; &nbsp;: Betweenness Centrality

Color &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : Modularity Class

Density &nbsp; &nbsp; &nbsp; &nbsp;: 0.048

 |

Degree Range &nbsp; &nbsp;:&nbsp;10 - 492

Node &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : 452

Edges &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;: 9767

Average Degree :&nbsp;43.217

 |

![](http://rameshbalasekaran.com/FinalProject/images/image06.png)

Fig. 16. Social Network of active Hillary Clinton followers

On January 19th, 2016, Twecoll was used to extract list of tweets with '#Hillary2016' from Twitter. 10,000 tweets were collected after this process. From the dataset a subset of 998 random unique users was parsed and saved as a new file. To the above list two users were added, '@realdonaldtrump' and '@hillaryclinton'. The newly created file was then passed to Twecoll to generate a network from the 1000 nodes. The network was then loaded and visualized in Gephi. To remove users who are loosely bound in the network, nodes with degree range &lt; 10 were filtered to result in the above network. The directed edges between the nodes represents that the source user follows the target user. The node size was adjusted as per the betweenness centrality and the color was set as per the modularity class.

Observations:

From the network visualization, three prominent communities were identified and color coded - Purple, Blue, and Green. 'hillary2016press' of purple community, 'lostdiva' of blue community and 'night_rider2014' of the green community have the highest betweenness centrality. In purple community 'hillaryclinton', 'stylistkavin' and 'hillary2016press' had a high betweenness centrality as compared to other nodes and formed a clique. There was a clear divide between the green community and the rest of the communities.

Analysis:

From the above visualization it can be clearly seen that all the communities are internally well connected. The green community is primarily dominated by Republicans, like '[libertarianWE',][18][&nbsp;'][19][KevniChang][20]' etc. The purple community primarily consists of Hillary Clinton's supporters, like 'Hillary_HQ', '777sjr', 'renayws' etc. Blue community consists of Bernie supporters, like 'bernieartists', 'adamnguy'&nbsp;etc. The purple and blue community are much more closely knit as compared to the green community which is apparent as they support the Democrat party. 'stylistkavin', 'hillary2016pres' and 'hillaryclinton' are the most prominent users in the purple community and forms a clique within themselves indicating they are strongly connected.

![](http://rameshbalasekaran.com/FinalProject/images/image18.png)

Fig. 17. Egocentric&nbsp;network analysis of Donald J. Trump in Hillary Clinton's network

Egocentric network analysis of Donald J. Trump reveals interesting observation, There is clear divide between the green community and the rest of the network in Hillary Clinton's network, Interestingly these people are bridged by Donald Trump to the rest of the network indicating these people who are tweeting with hashtag #Hillary2016 are not following Hillary directly and are using the hashtag to tweet negative information about Hillary, Further analysis indicates these people tweeting about her decision in benghazi attacks by including #HillaryforPrison in their tweets.

Sentiment Analysis:

In our attempt to understand the public reaction garnered by Donald Trump and Hillary Clinton, we performed sentimental analysis in R using a few popular hashtags like #Trump2016 and #Hillary2016.

| ----- |
|

![](http://rameshbalasekaran.com/FinalProject/images/image13.png)

 |

![](http://rameshbalasekaran.com/FinalProject/images/image00.png)

 |
|

#Trump2016

 |

#Hillary2016

 |
|

Fig. 18.

 |

Fig. 19.

 |

At first we collected 1500 tweets using Twitter API's and various packages in R. The tweets collected were then processed i.e. made ready for sentiment analysis by removing spaces, hyperlinks, punctuations and other unnecessary content. The final result is displayed in Fig. 18. and Fig. 19.

From the graphs we can infer that there is not a significant difference between the public reactions received by Donald Trump and Hillary Clinton. This is a clear indication as to &nbsp;how fierce this battle is and there is not much which separates the two. On examining closely we found out that the negative comments received by Hillary are briefly more in number as compared to Trump. This can impact the results of the upcoming elections if the two candidate emerge as the winners from their respective parties.

Combining these results with the social network analysis provides fruitful insights, Hillary Clinton's network had a huge chunk of people following Donald Trump and Bernie Sanders. Sentiment analysis of tweets containing #Hillary2016 also showed 13-15% tweets with negative rating indicating in Twitter even though Hillary is the favourite among the Democrats, she has many people who are against her. Alternatively Trump has more tweets which has neutral polarity and very tightly connected social network indicating Trump has good social media strategy and it's working well with less than 10% people expressing view against Donald Trump.

Conclusion:

From our survey results, we found out that social media plays a huge role in dissipating information across the globe. Many people are hooked onto social networking sites like Twitter, Facebook, Tumblr, etc. and share their views on varied subjects around the world. Thus, it acts as a source of information for many people and is therefore used extensively in the upcoming U.S. Presidential elections.

Social network analysis of Donald Trump and Hillary Clinton gave a strong indication that they are the frontrunners from Republicans and Democrats respectively. We also found out certain Twitter users in their network who are responsible for spreading information about them and tweet extensively to show their support. For example, thegreatfeather is an ardent follower of Donald Trump with tweets like "That's Right we're for Mr Trump", "Mr Trump, make America great again!" etc. Visualizing information propagation for both the candidates indicates the speed in which information spreads about Trump is more compared to Hillary Clinton. Twitter statistics also indicates the same with ~10,000 tweets per 15 minute for Donald Trump while Hillary had only ~3000 tweets for the same period.

Trump's presence on social media has been very boisterous since he joined the presidential race. His crude and loud comments on Twitter attract a lot of attention and evoke reaction amongst the public. On the other hand, Clinton's record so far has been very professional and politically-correct which doesn't provide much entertainment. This inevitably results in him being the 'social media darling' with a powerful presence.

Comparing Hillary Clinton's and Donald Trump's social network indicates Donald Trump as a clear winner in his social media strategy with his well formed and strongly connected social network which propagates positive sentiments across his network. The strongly connected social network provides a perfect medium to reiterate his view across his social network multiple times and establish interaction among his loyal followers. Downside of Donald Trump's social network is its lack of weak ties that spread information outside the social network. While Hillary Clinton's social network contained diversified communities Donald Trump had only strong followers in his social network. This also provides a medium for Hillary Clinton to reach out to different communities.

References&nbsp;

Soumitra Dutta, Matthew Fraser. 2008 Barack Obama and the Facebook Election, US News, Retrived 01/17/2016 from http://www.usnews.com/opinion/articles/2008/11/19/

barack-obama-and-the-facebook-election

Reuters, September 2015. How Twitter '$Cashtags' are changing US presidential campaigns,

The Times of India Retrived 01/17/2016 from http://timesofindia.indiatimes.com/tech/

tech-news/How-Twitter-Cashtags-are-changing-US-presidential-campaigns/articleshow/48986972.cms

R. Kay Green, 2015. The Game Changer: Social Media and the 2016 Presidential Election. Huffpost Politics. Retrived 01/17/2016 from http://www.huffingtonpost.com/r-kay-green/

the-game-changer-social-m_b_8568432.html.

[Drew Hendricks][24]. (May 2013) Complete History of Social Media: Then And Now, Small Business trends, Retrived 01/17/2016 from [http://smallbiztrends.com/2013/05/][25]

[the-complete-history-of-social-media-infographic.html][26].

Andrew Paul Williams , Kaye D. Trammell , Monica Postelnicu , Kristen D. Landreville &amp; Justin D. Martin (2005) Blogging and Hyperlinking: use of the Web to enhance viability during the 2004 US campaign, Journalism Studies, 6:2, 177-186, DOI: 10.1080/14616700500057262

Williams, C., and Gulati, G. 2008. What is a Social Network Worth? Facebook and Vote Share in the 2008 Presidential Primaries. In Annual Meeting of the American Political Science Association, 1-17. Boston, MA.

Tumasjan, A., Sprenger, T. O., Sandner, P. G., &amp; Welpe, I. M. (2010). Predicting Elections with Twitter: What 140 Characters Reveal about Political Sentiment. ICWSM, 10, 178-185.

O'Connor, B., Balasubramanyan, R., Routledge, B. R., &amp; Smith, N. A. (2010). From Tweets to Polls: Linking Text Sentiment to Public Opinion Time Series.ICWSM, 11(122-129), 1-2.

Gayo Avello, D., Metaxas, P. T., &amp; Mustafaraj, E. (2011). Limits of electoral predictions using twitter. In Proceedings of the Fifth International AAAI Conference on Weblogs and Social Media. Association for the Advancement of Artificial Intelligence.

Bond, R. M., Fariss, C. J., Jones, J. J., Kramer, A. D., Marlow, C., Settle, J. E., &amp; Fowler, J. H. (2012). A 61-million-person experiment in social influence and political mobilization. Nature, 489(7415), 295-298.

Beck, P. A., Dalton, R. J., Greene, S., &amp; Huckfeldt, R. (2002). The social calculus of voting: Interpersonal, media, and organizational influences on presidential choices. American Political Science Review, 96(01), 57-73.

Lake, Ronald La Due, and Robert Huckfeldt. 1998. "Social Capital, Social Networks, and Political Participation." Political Psychology 19 (3): 567–84.

Moy, Patricia, and John Gastil. 2006. "Predicting Deliberative Conversation: The Impact of Discussion Networks, Media Use, and Political Cognitions." Political Communication 23 (4): 443–60.

Miller, P. R., Bobkowski, P. S., Maliniak, D., &amp; Rapoport, R. B. (2015). Talking Politics on Facebook Network Centrality and Political Discussion Practices in Social Media.&nbsp;Political Research Quarterly, 1065912915580135.

Acknowledgment

For analysis, open source python code 'Twecoll' was used to collect tweets and form a network from the nodes parsed from the tweets: [https://github.com/jdevoo/twecoll][27]

All the datasets mentioned in this paper and Gephi files can be downloaded from Github repository at this link: [https://github.com/Rameshb-umd/Social-Network-Analysis][28]

Apoorva Ajmani, Karan Kashyap, Ramesh Balasekaran

[1]: https://www.google.com/url?q=https://github.com/Rameshb-umd/Social-Network-Analysis/&amp;sa=D&amp;ust=1454381107668000&amp;usg=AFQjCNFh-qJYzpLRWPaiKF_-ucacOCXnVw
[2]: http://rameshbalasekaran.com/images/image02.png ""
[3]: http://rameshbalasekaran.com/images/image05.png ""
[4]: http://rameshbalasekaran.com/images/image03.png ""
[5]: http://rameshbalasekaran.com/images/image11.png ""
[6]: http://rameshbalasekaran.com/images/image07.png ""
[7]: http://rameshbalasekaran.com/images/image01.png ""
[8]: http://rameshbalasekaran.com/images/image08.png ""
[9]: http://rameshbalasekaran.com/images/image17.png ""
[10]: http://rameshbalasekaran.com/images/image16.png ""
[11]: http://rameshbalasekaran.com/images/image10.png ""
[12]: http://rameshbalasekaran.com/images/image12.png ""
[13]: http://rameshbalasekaran.com/images/image15.png ""
[14]: http://rameshbalasekaran.com/images/image14.png ""
[15]: http://rameshbalasekaran.com/images/image04.png ""
[16]: http://rameshbalasekaran.com/images/image09.png ""
[17]: http://rameshbalasekaran.com/images/image06.png ""
[18]: https://www.google.com/url?q=https://twitter.com/libertarianWE&amp;sa=D&amp;ust=1454381107742000&amp;usg=AFQjCNEGHQlvWwTVQrpQIlj6pQBdzHAr8g
[19]: https://www.google.com/url?q=https://twitter.com/libertarianWE&amp;sa=D&amp;ust=1454381107743000&amp;usg=AFQjCNF9DDsk59tZdYiyTeWpBqH3mjzT9w
[20]: https://www.google.com/url?q=https://twitter.com/KevniChang&amp;sa=D&amp;ust=1454381107743000&amp;usg=AFQjCNFHz8ednFMUoeSF89HeSVNM7kVYQw
[21]: http://rameshbalasekaran.com/images/image18.png ""
[22]: http://rameshbalasekaran.com/images/image13.jpg ""
[23]: http://rameshbalasekaran.com/images/image00.jpg ""
[24]: https://www.google.com/url?q=http://smallbiztrends.com/author/drew-hendricks&amp;sa=D&amp;ust=1454381107761000&amp;usg=AFQjCNGSSht0pkRBAuufc_T-BLvSpQACMA
[25]: https://www.google.com/url?q=http://smallbiztrends.com/2013/05/the-complete-history-of-social-media-infographic.html&amp;sa=D&amp;ust=1454381107762000&amp;usg=AFQjCNF0MGePOKTxUSaQPb4ddqYRuaXg3w
[26]: https://www.google.com/url?q=http://smallbiztrends.com/2013/05/the-complete-history-of-social-media-infographic.html&amp;sa=D&amp;ust=1454381107763000&amp;usg=AFQjCNFGTeg_VlyX7UGFJNGAjOl6tjgn4A
[27]: https://www.google.com/url?q=https://github.com/jdevoo/twecoll&amp;sa=D&amp;ust=1454381107781000&amp;usg=AFQjCNFxjJH9qbiOij9MgpxuSbhkq0RG-Q
[28]: https://www.google.com/url?q=https://github.com/Rameshb-umd/Social-Network-Analysis&amp;sa=D&amp;ust=1454381107782000&amp;usg=AFQjCNFM3WRW60iDgo0OijC4WnC3zay46Q
  
