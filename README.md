# NLP--Progressive-issues-sentiment-
Contributors viewed tweets regarding a variety of left-leaning issues like legalization of abortion, feminism, Hillary Clinton, etc. They then classified if the tweets in question were for, against, or neutral on the issue (with an option for none of the above). After this, they further classified each statement as to whether they expressed a subjective opinion or gave facts.

## Data
The dataset contains the following fields:
- unit_id: a unique id for user
- golden: whether the user was included in the gold standard for the model; TRUE or FALSE
- unit_state: state of the observation; one of finalized (for contributor-judged) or golden (for gold standard observations)
- trusted_judgments: number of trusted judgments (int); always 3 for non-golden, and what may be a unique id for gold standard observations
- last_judgment_at: date and time of last contributor judgment; blank for gold standard observations
