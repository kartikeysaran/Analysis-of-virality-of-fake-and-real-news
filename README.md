# Analysis of Virality of Fake and Real News

#### The term ”Fake News” has become much more prevalent since the emergence of the internet and social media. Since the United States of America’s 2016 presidential election, this growth has been especially visible, indicating a significant presence and spread of false information online.

Any information that is misinterpreted, taken out of context, or flat-out incorrect and presented as news is considered fake news. Fake news can be produced and disseminated for a number of reasons, including to boost viewership of a news channel or blog, defame or smear specific people or organisations, win political favour, etc. Despite the fact that fake news has always existed, thanks to the internet it is now much simpler to produce and spread to millions of people.

Fake news is purposefully produced to appeal to people’s emotions and prompt an action or response. It exaggerates the drama of real or imagined occurrences. It makes sense that this sensationalism would make fake news more well-known or ”viral” than authentic news. As stated, fake news is very prevalent on the internet and has been the subject of many research papers. People/News agencies post fake news because it gets traction and more views on their posts, which means fake news spreads faster on the internet, or, in other words, it’s more viral than real news.

## Methodology

* ### Selecting Events
  * In order to calculate virality of fake and real news from Twitter data, we have to extract Tweets for specific events. These events should be such events for which we know the real and fake news for so that we can filter the data later. We picked events which are political and non-political in nature. Table 1 show the events:-
    Event | Description | Category
    | :--- | ---: | :---:
      | Mino Raiola | The rumours of Mino Rioalas, a football agent, death keeps appearing | Social
      | Railway Ministry Job Vacancy | Railway Ministry of India posted job vacancy to recruit 9000 RPF | Social
      | Covid Vaccine | Various claims made about the covid vaccine | Health
      | Jahangirpuri Incident | Religious riots on 16th April 2022 in Jahangirpuri, Delhi India | Religious
      | Farmers Protest | Farmers protest was against government bills | Political
* ### Data Collection
  * In order to prepare the Dataset we used the Twitter API provided by Twitter Developer to retrieve Tweets according to the events in the previous section. We signed up for Twitter Developer and wrote a python script to retrieve Tweets and prepare the dataset. We have twitter advanced search methods to filter the real and fake news for an event
* ### Data Processing and Analysis
  * Once we have collected all the data related to the tweets and segregated them we calculated the virality of each tweet and event for both the real news and the fake news.
    * Formula used for calculating Virality <br />
    ``` Virality for an event = Σ No. of Followers Count of every user that performs an activity on the tweet ```
    
## Results

* Fake News Travels 4.1 times faster than Real News
* Activities (Likes, Comments, Share, Retweets etc.) on tweets of Fake news were very high when compared to Activities on tweets of Real News
* While bots do participate in spreading fake news, virality depends more on real humans spreading fake news through posting, retweeting, and sub quoting.
* Fake News keeps reappearing unlike real news, which starts out strong but dies down.
* Fake news is posted by a wider variety of sources as compared to real news.



    
    



