# A.1

## Class A(#Covid)
Tweets: 97251

Users: 76324

Verified Users: 1392

Non Verified Users: 74932

## Class B (#SushantSinghRajput)
Tweets: 43149
Users: 19159
Verified Users: 119
Non Verified Users: 19040

## Class C (Both)
Tweets: 38
Users: 20
Verified Users: 0
Non Verified Users: 20


# A.3
I've used UMass measure for LDA topic modelling. 
UMass have negative coherence values, so as UMass coherence approaches to 0 the topic coherence gets better.
As the classes are already only about covid or sushant so there would not be many topics.

## Class A (#Covid)
k=1 (#topics)
Keywords in the topic:
1. covid
2. covid-19
3. mask
4. case
5. wear
6. test
7. new
8. make
9. coronavirus
10. death
Keywords shows that the tweets are mostly about new tests, cases, deaths due to coronavirus and also about wearing masks.
 
## Class B (#SushantSinghRajput)
k=2 (Lowest coherence score)

Keywords in Topic0:
1. sushantsinghrajput
2. justice
3. sushant
4. case
5. watch
6. music
7. call
8. get
9. tribute
10. one

Keywords in Topic1:
1. sushantsinghrajput
2. rajeevmasand
3. bollywood
4. fight
5. critic
6. more
7. thank
8. plea
9. blind
10. thi

Keywords in topic0 shows that it is about justice, musical tribute for sushant whereas, keywords in topic1 talks about film critic rajeev masand, about his blind items, and pleas for sushant case.

## Class C 
Because the tweets are less, coherence scores are not very good class C for different values for k.
for k=3, coherence score is least negative.

Keywords in Topic0:
1. fact
2. factcheck
3. hubble
4. interest
5. nasa
6. follow
7. ff7c
8. factsmatter
9. inst
10. birthday

Keywords in Topic1:
1. sushantsinghrajput
2. see
3. thing
4. video
5. bodi
6. taken
7. suspect
8. pic
9. notice
10. hospital

Keywords in Topic2:
1. borrow
2. pound
3. uk
4. billion
5. vocalforlocal
6. reflect
7. fashion
8. person
9. destellocloth
10. inside

Topics are not making sense much. Topic1 seems to be related to sushant. 

## Chatter plot for the Tweets

- Class A (Covid)
Most frequent words in the covid tweets are covid, covid19, masks, new cases, vaccine, wear, people etc.
Most of the top 50 words are classified in positive to neutral category. 
But some words such as ineffective, cystic fibrosis, death are also classified as positive words.
Trump is mostly used in negative tweets.

- Class B (SushantSinghRajput)
Most of the frequent words are in the range -0.5 to 0.5 average sentiment value because in recent days, most of the tweets were about musical tribute to ssr so words such as tribute, musical, watch, special are most used in positive sense.
Words such as articles, cbienquiry, death, questioning, police, articles are mostly used in negative tweets and are in the top 50 most frequent words.

- Class C (Both)
Most of the tweets are retweets and are useless tweets.
so most of the words are repeated many times.
All the top frequent words are classified as positive because of the retweets. After reading tweets text, one can say most of the tweets does not carry much information.



# A.4
1. No of tweets (combining retweets) for covids are more than sushant singh, showing that covid is more trending topic (can be deduced from the fact that the entire world is tweeting about covid and sushant is trending only in india). Covid tweets are more about the latest discoveries or growth rate in covid cases in a geographical region since it's an ongoing event.
 
2. Fraction of users and tweets are more for covid than sushant indicating that number of users tweeting about covid are more than people tweeting about sushant. Users taking part in covid topic is more i.e. there are more number of distinct users.

3. Fraction of tweets which are negative are more for sushant than covid. (result for top 50 frequent words are more negative)

4. Fraction of verified and non-verified accounts is higher for covid than sushant indicating more influential people are tweeting about covid than sushant. Sushant case is not a comparable one but probably it isn't as infuential at a global level as Corona meaning that the virus is affecting that class also.

5. From the retweets graph, Covid tweets have more retweets than sushant retweets (degree centrality). New discoveries in covid is making people tweet and retweet again and again.




# A.5
There is a high correlation between the number of tweets and cases when grouped by countries name.
Correlation value = .84




# A.6

## Class A (Covid)

Graph is not connected. 

Largest Component of the graph contains most of the nodes.
As the largest component have maximum degree centrality of 0.07 which says that most of the nodes are not connected to many nodes. Every node will have sparse connections. As the users/tweets are high, there is less probability that a tweet is shared by many users.

Maximum closeness centrality is 0.11 which shows that most of the nodes are central nodes and are less distant to other nodes like many groups of nodes are connected side by side in a kind of like circle.

Maximum betweeness centrality have the value of 0.29 indicates that 30pect of the shortest paths goes from that node or depend on that node in these large amount of nodes/users retweets so it is an important node. 



## Class B (Sushant)

Graph is not connected and divided into 344 components. Overall graph is not connected.

Largest component have maximum degree centrality of 0.10 indicates nodes have less degrees. Most of the nodes have less edges or corner nodes.
Max closeness centrality of 0.34 indicates that there are less central nodes and graph is spreaded.
Betweenness centrality have value 0.22 indicates there are no such nodes which disconnects the graph by large extent.


## Class C 
There are 4 components with 3 central nodes.

