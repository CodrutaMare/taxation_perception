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
Our experiments that have been developed up to now are published in the following papers:
### :one: Modelling taxpayers’ behaviour based on prediction of trust using sentiment analysis  
Check out the output of this analysis in the [sent_analysis_814_database](blob/main/sent_analysis_814_database.ipynb) notebook.  
### Cite
If you would like to refer to it in publications or other scientific works, please use the following:  
_Coita, I. F., Belbe, Ș., Mare, C., Osterrieder, J., & Hopp, C. (2023). Modelling taxpayers’ behaviour based on prediction of trust using sentiment analysis. Finance Research Letters, 58, 104549._  

### :two: Is Trust a Valid Indicator of Tax Compliance Behaviour? A Study on Taxpayers’ Public Perception Using Sentiment Analysis Tools  
Check out the output of this analysis in the [sent_analysis_704_database](blob/main/sent_analysis_704_database.ipynb) notebook.  
### Cite
If you would like to refer to it in publications or other scientific works, please use the following:  
_Coita, I. F., Cioban, Ș., & Codruța, M. (2022). Is Trust a Valid Indicator of Tax Compliance Behaviour? A Study on Taxpayers’ Public Perception Using Sentiment Analysis Tools. In Digitalization and Big Data for Resilience and Economic Intelligence: 4th International Conference on Economics and Social Sciences, ICESS 2021, Bucharest, Romania (pp. 99-108). Cham: Springer International Publishing._  

## Licence
If you would like to use these results or any of the visualizations or data presented, you are free to do so under an [MIT license](blob/main/LICENSE). 
