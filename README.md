# NLP--Progressive-issues-sentiment-
Contributors viewed tweets regarding a variety of left-leaning issues like legalization of abortion, feminism, Hillary Clinton, etc. They then classified if the tweets in question were for, against, or neutral on the issue (with an option for none of the above). After this, they further classified each statement as to whether they expressed a subjective opinion or gave facts.

## Conseils du prof
- bien faire une évaluation qualitative (pas uniquement quantitative donc)
- de bien suivre les autres consignes (varier les types d'approches, les embeddings, etc.)
- peut-être regarder du côté de l'aspect-based sentiment analysis :
 
Source : https://monkeylearn.com/blog/aspect-based-sentiment-analysis/
Aspect-based sentiment analysis (ABSA) is a text analysis technique that categorizes data by aspect and identifies the sentiment attributed to each one. Aspect-based sentiment analysis can be used to analyze customer feedback by associating specific sentiments with different aspects of a product or service.

When we talk about aspects, we mean the attributes or components of a product or service e.g. “the user experience of a new product,” “the response time for a query or complaint,” or “the ease of integration of new software.”

Here’s a breakdown of what aspect-based sentiment analysis can extract:

Sentiments: positive or negative opinions about a particular aspect
Aspects: the category, feature, or topic that is being talked about

## Data
The dataset contains the following fields:
- unit_id: a unique id for user
- golden: whether the user was included in the gold standard for the model; TRUE or FALSE
- unit_state: state of the observation; one of finalized (for contributor-judged) or golden (for gold standard observations)
- trusted_judgments: number of trusted judgments (int); always 3 for non-golden, and what may be a unique id for gold standard observations
- last_judgment_at: date and time of last contributor judgment; blank for gold standard observations
