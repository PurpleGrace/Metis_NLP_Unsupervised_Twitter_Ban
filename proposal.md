# NLP & Unsupervised Learning project
## who support twitter banning accounts and who do not?

### Question/Need:

- What is the question behind your analysis? What is the purpose of the model/system you plan to build?

<span style="color:lightseagreen">
Twitter is one of largest social media platform in the world. In recent years, there are controversies about twitter's behavior of banning or deleting people's account or tweets, in which circumstances the tweets are about higyly sentitive or controverisal topics and Twitter claims that deleted tweets violated its public policies. In this project, we aim to find out people's attitude about twitter banning or deleting, who/what group are prone to support Twitter's banning operation and who/ what group would against.

</span>

- Who benefits from exploring this question or building this model/system?

<span style="color:lightseagreen">
People have different attitude due to their different world views and standards. The project may help political groups, non profit organizations, advertisement companies to recognize potential supporters, donors, customers and etc.

</span>


### Data Description:

- What dataset(s) do you plan to use, and how will you obtain the data?

<span style="color:lightseagreen">
Tweepy API will be used to pull text and numerical data from Twitter, the query will be about "banned by twitter" or "deleted by twitter". The project plan to pull at least 10,000 tweets, including tweet content, like numbers, retweet numbers, tweet author id Description, geo and etc.



</span>

- What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?

<span style="color:lightseagreen">
Data pulled by tweepy API will be transformed to DataFrame. Each row of the dataset represents one tweet info, including tweet content, like numbers, retweet numbers, tweet author id Description, geo and etc.
</span>

- If modeling, what will you predict as your target?

<span style="color:lightseagreen">

</span>


### Tools:

- How do you intend to meet the tools requirement of the project?
<span style="color:lightseagreen">

  - libraries like RE, NLTK will be used to vectorize context data.
  - sklearn,gensim will be used for dimention reduction, topic modeling
  - sklearn for clustering
  - matplotlib, seaborn for data visualization  
</span>

- Are you planning in advance to need or use additional tools beyond those required?    

<span style="color:lightseagreen">

 - Tableau might be used for EDA visualization.
 - Tweepy API will be used for data scraping.

</span>


### MVP Goal:


What would a minimum viable product (MVP) look like for this project?

<span style="color:lightseagreen">

The MVP for the project will provide sentiment analysis to show if people are positive or negative about Twitter's banning and deleting behavior.

</span>
