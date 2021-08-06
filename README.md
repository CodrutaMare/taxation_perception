# Taxation Perception
A sentiment analysis on how taxation is perceived in Romania.
We've questioned 814 Romanian people on how they perceive the national tax system. We've analyzed their reponses to
three questions:
1. What displeases you about the Romanian tax system ?
2. If you were the Minister of Public Finance, what would you change about the Romanian tax system? 
3. In your opinion, what does the current tax system offer you?  
4. What will motivate you to trust the fiscal system?

Based on the responses, we've computed word frequencies to deliver a word cloud of the most frequent words for each
question and we've computed sentiment scores based on a pre-trained sentiment analysis BERT model, which was trained on
a Romanian database and can be downloaded from https://github.com/stefanacioban/romanian_sentiment_predictor.

Trustworthiness in the fiscal system is a key issue, impacting the way taxpayers act in relation to paying or defrauding. When developing general public policies and specific ones for combating tax fraud, governments are more attentive to public opinion. Using survey data, we assessed word frequencies, sentiments and attitudes to build a global picture over taxpayers’ perceptions and how they impact trust in the taxation system. Natural language processing along with other statistical and machine learning tools emphasize that taxpayers that do not trust the fiscal system use more negative words with lower frequencies and less diverse.

By computing the mode for the binary sentiment indexes, we were able to generate an overall polarity score for each response. This measure of sentiment expressed from each taxpayer’s response together with the variable representing their opinion about the fiscal system were used to further train and test different statistical, ML and DL-based models for the prediction of the dependent variable, the binary measure of trust in the Romanian fiscal system.

Work that has been up to now is published in the following papers:
Coita, I., Mare, C. (2021). The Utility of Neural Model in Predicting Tax Avoidance Behavior, presented and accepted to be published in the conference: Intelligent Decision Technologies 2021 - Proceedings of the 13th KES (KES-IDT-21), which was held on June 12 – 14, 2021 – virtual conference and accepted for publication in the Springer Volume of the KES Smart Innovation Systems and Technologies series, indexing in Scopus and Thomson-Reuters (CPCI) and the Web of Science.

Coita, I., Cioban, S., Mare, C. (2021a). Mining Tax-Payers Opinions in Predicting the Trustworthiness of the Fiscal System, under review to The Singapore Economic Review, ISSN (print): 0217-5908, ISSN (online): 1793-6837.

Coita, I., Cioban S., Mare, C. (2021b). Is Trust a Valid Indicator of Tax Compliance Behaviour? A Study on Taxpayers’ Public Perception Using Sentiment Analysis Tools, accepted to the conference: The 4th International Conference on Economics and Social Sciences which was held in June 10th – 11th, 2021 – Bucharest, Romania and accepted for publication in the Sciendo (De Gruyter) in a Conference Proceedings Volume indexed Web of Science (CPCI).



