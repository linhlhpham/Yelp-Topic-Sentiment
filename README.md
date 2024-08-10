Yelp Restaurant Reviews: Sentiment Analysis and Topic Modeling
---

**Project Overview**
- This project analyzed Yelp reviews of California restaurants to understand customer perceptions using advanced text analytics techniques.

**Approaches**
- Text Preprocessing: Reviews were tokenized, normalized, and stemmed to prepare the data for analysis.
- Sentiment Analysis: NLTK's Sentiment Intensity Analyzer was used to calculate sentiment scores for each review.
- Topic Modeling: Latent Dirichlet Allocation (LDA) identified 18 topics, which were grouped into four main categories: service, food, location, and time.
- Linear Regression: This method explored the relationships between sentiment scores, topics, and user ratings.

**Key Findings**
- The LDA model achieved maximum coherence at 18 topics, with 'service' being the predominant topic, accounting for 42% of reviews.
- 'Service' and 'food' topics had the strongest correlation with star ratings, indicating these factors are crucial in customer evaluations.
- The project proposed implementing features like "Yelp Rating Breakdown" and "Summary of Review" to provide businesses with detailed insights into ratings and help customers make informed decisions
