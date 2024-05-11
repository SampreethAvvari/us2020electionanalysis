# Sentiment Analysis on the Fake News Spread in Twitter during 2020 US Presidential Elections

Authors: Sampreeth Avvari, Barath Rama Shankar, Dhruv Sridhar  
Emails: spa9659@nyu.edu, br2543@nyu.edu, ds7395@nyu.edu  
Institution: New York University

## Folder Structure

Below is the structure of the `us2020electionanalysis` project, organized for clarity:

```plaintext
us2020electionanalysis/
├── README.md                  # Overview and project instructions
├── report.pdf                 # Detailed report of the findings
├── sentiment analysis/
│   └── sentiment_analysis.ipynb   # Notebook for sentiment analysis
└── fake news detection/
    ├── fake_news_detection_finetuning.ipynb   # Notebook for fine-tuning the fake news detection model
    └── fake_news_detection_inference.ipynb    # Notebook for performing inference with the fake news detection model
```

## Abstract
This research evaluates political sentiment analysis to reveal trends in digital discourse during the 2020 U.S. Presidential Elections. Utilizing advanced AI models like Few-shot Llama 3 and RoBERTa, we analyzed millions of tweets to detect fake news, classify sentiment, and identify key topics. This study aims to understand the polarized emotions and attitudes prevalent during the elections and assess Twitter’s content moderation for potential partisan bias. The influence of social media on political discourse is significant, especially during events like the U.S. presidential elections. Our study leverages social media data to provide direct insights into public sentiment, where users express support or disdain for candidates. By categorizing tweets and analyzing sentiment, we explore the nature of political emotions during the election season.

## Key Objectives
- **Model Optimization**: Fine-tuning the Few-shot Llama 3 model for detecting fake news in U.S. elections.
- **Sentiment Classification**: Using RoBERTa to classify tweets by sentiment into pro or anti-candidate categories.
- **Topics Modeling**: Examining election season topics and their variations with sentiment changes.
- **Misinformation Mapping**: Measuring fake news spread across states and assessing geographical and temporal trends.
- **Geographic Distribution**: Studying regional sentiment distribution to gauge localized political engagement.
- **Behavioral Insights**: Exploring user patterns in political support, focusing on antagonistic versus supportive expressions in misinformation-laden tweets.

## Methodology
The methodology includes fine-tuning LLaMa 3 model for enhanced detection of misinformation and classifying tweets based on sentiment using RoBERTa model. We also performed topic modeling to infer the discussion themes across different political leanings using LDA.

### Datasets
1. **[LIAR Dataset](https://huggingface.co/datasets/liar)**: Benchmark Dataset for Fake News Detection. Used for finetuning our model to detect fake news in tweets. 
2. **[US 2020 Election Tweets Dataset](https://www.kaggle.com/datasets/manchunhui/us-election-2020-tweets)**: Compiled to analyze public sentiment on Twitter for the 2020 U.S. Presidential Election.

### Models Used
- **Fake News Detection**: Employing the fine-tuned LLAMA-3 8B model.
- **Sentiment Analysis**: Utilizing the RoBERTa-base sentiment analysis model trained on a large corpus of tweets.
- **Topic Modeling**: Applying LDA for generative statistical modeling to uncover latent topics in tweets.

## Results
The analysis shows a significant presence of both fake and negative news about candidates, with notable differences in tweet volume between candidates. Our findings highlight the role of misinformation and sentiment in shaping public discourse during the elections. The analysis shows a significant presence of both fake and negative tweets about Trump during the peak election season, with his name appearing in approximately in 52% of the tweets compared to just 4% mentioning ”Joe” or ”Biden”. This disparity underscores the extent of discussion surrounding Trump, with the majority (60%) of the mentions being negative. So, ”Trump” trumped over ”Joe”?

It also identified distinct strategies in Twitter use by political groups, with anti-democratic narratives focusing on personal attacks, and pro-democratic ones promoting unity and voter mobilization. These results underscore the effectiveness of AI in analyzing online misinformation and sentiment, emphasizing the importance of ongoing research to enhance understanding of social media’s influence on public opinion and electoral outcomes.

## References
1. Knight Foundation Study on misinformation: [Link to Study](https://knightfoundation.org/features/misinfo/)
2. IEEE Paper on Identifying Tweets with Fake News: [Link to Paper](https://hi.switchy.io/MWgY)
3. More studies and references included in the full report.

---
