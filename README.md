# Taxation Perception

A sentiment analysis on how taxation is perceived in Romania.  
We've questioned Romanian people on how they perceive the national tax system. We've analyzed their responses to
four questions:  
1. What displeases you about the Romanian tax system ?  
2. If you were the Minister of Public Finance, what would you change about the Romanian tax system?  
3. In your opinion, what does the current tax system offer you?  
4. What will motivate you to trust the fiscal system?

Based on the responses, we've computed sentiment scores based on a pre-trained sentiment analysis BERT model to build a global picture over taxpayers’ perceptions and how they impact trust in the taxation system. The sentiment analysis model was developed within:  
_Cioban, Ș. (2021). Cross-Domain Sentiment Analysis of the Natural Romanian Language. In International Conference on Digital Economy (pp. 172-180). Cham: Springer International Publishing._  


The methodology increased in complexity as it was gradually developed from exploratory analysis, consisting in topic modelling of text corpora, to a bi-variate analysis of the documents on tax perception against the trustworthiness indicator of the fiscal system of Romania, and to a multi-variate predictive model using the sentiment expressed within the text corpora alongside other indicators to predict the measure of trust in the fiscal system. 


## Studies
Our experiments that have been developed up to now is published in the following papers:
### :one: Modelling taxpayers’ behaviour based on prediction of trust using sentiment analysis  
Fiscal systems depend on taxpayer's behaviour in terms of their willingness to comply or engage in fraud, deeply rooted in trustworthiness. To gain insights into taxpayers' perceptions and their influence on trust within taxation system, we use survey data to analyse word frequencies, sentiments, attitudes. Our approach utilizes natural language processing in conjunction with machine learning techniques. We highlight a notable correlation: taxpayers who lack trust in fiscal system tend to employ a higher frequency of negative words and exhibit limited word diversity in their expressions. The presence of negative sentiments may potentially foster fraudulent behaviours in the future.  
Check out the output of this analysis in the [sent_analysis_814_database](blob/main/sent_analysis_814_database.ipynb) notebook.  

### :two: Is Trust a Valid Indicator of Tax Compliance Behaviour? A Study on Taxpayers’ Public Perception Using Sentiment Analysis Tools  
Compliant behaviour in the field of taxes has a profound impact on the economic and social field. Tackling the tax evasion phenomenon is not an easy thing to do. That is why there are several public institutions that are preoccupied with discovering and punishing it. The discovery of the actions that rely on the sphere of tax evasion can come through the Tax Authority which in turn is able to punish it by a fine. Fraudsters in the tax field are using more sophisticated techniques and technological tools that make the discovery very difficult. Identifying and combating tax evasion is a complex process and knowledge from various fields is needed. Our study tries to identify those variables relating to taxpayers’ behaviour that could be tackled by the Tax Authority in order to control this phenomenon. We achieved this objective by the use of NLP algorithms for analysing free speech answers on an online survey. In this sense, our research hypothesis is that trustworthiness in the State is positively correlated with an optimistic perception of the fiscal system. We analysed what is the structure of perception and which are the words that are most frequent. Results are in accordance with the literature review of the factors that impact compliant behaviour and confirm our hypothesis. The utility of results relies on the fact that in the context of smart governance, and Public Authorities should look at citizens’ perception of tax policies and services in order to adapt its actions for an efficient collection of revenues to the State's budget.   
Check out the output of this analysis in the [sent_analysis_704_database](blob/main/sent_analysis_704_database.ipynb) notebook.  

## Licence
If you would like to use these results or any of the visualizations or data presented, you are free to do so under an [MIT license](blob/main/LICENSE). 

## Cite
If you would like to refer to it in publications or other scientific works, please use the following:  
_Coita, I. F., Cioban, Ș., & Codruța, M. (2022). Is Trust a Valid Indicator of Tax Compliance Behaviour? A Study on Taxpayers’ Public Perception Using Sentiment Analysis Tools. In Digitalization and Big Data for Resilience and Economic Intelligence: 4th International Conference on Economics and Social Sciences, ICESS 2021, Bucharest, Romania (pp. 99-108). Cham: Springer International Publishing._  
_Coita, I. F., Belbe, Ș., Mare, C., Osterrieder, J., & Hopp, C. (2023). Modelling taxpayers’ behaviour based on prediction of trust using sentiment analysis. Finance Research Letters, 58, 104549._  