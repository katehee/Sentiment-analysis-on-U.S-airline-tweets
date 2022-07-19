## Project: Sentiment analysis on U.S airline tweets 

### 1. Objective: 
- Analyze text data from 15000 tweets on US airlines and obtain a more comprehensive views on how traverler feels about U.S airline services and investigate customer likes, dislikes and expectations. 
        
### 2. Project Code and documentation:  
- project_code.ipynb
- final_report.pdf 

## 3. Data: tweet.csv
Kaggle: https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment
15000 tweets on six US airlines 

## 4. Method: 

 (a). Data Preprocessing
 
	- Number of tweets for each airline, distribution of sentiments acorss tweets, main reasons for the negativity, most frequent words appeared in positive and negative tweets 
  
	- EDA : EDA: pie chart, barplot, Plotly, Word Cloud (Tableau) 
	
	- Text: Data cleaning, Tokenization, Train_Test_split, Embedding (Count vectorizer & Tf-idf Vectorizer) 

 (b). Sentiment analysis
 
	- Tested four machine learning classifiers (Losgistic Regression, Naive Bayes, SVM, XGBoost)   
  
	- Hyperparameters are tuned using grid search 
	
	- Performance evaluation metrics used: accuracy & AUC score 
  
  
 (c). Keyword analysis 
 
	- Doc2Vec to calculate the relationship between tweets and words 
  
	- 10 most similar words for each positive and negative keywords from sentiment analysis are retrieved
	

   (d). Conclusion
 
	- Logistic regression performed the best in sentiment classification with an accuracy of 91%
  
	- This proposed model can be used to identify sentiments of future tweets and analyze customer experience and any improvement to be made 
	
  
## 5. techniques/Tools: 
- NLP, logistic regression, naive bayes, SVM, XGboost
- t-SNE plot, tableau, data visualization python libraries 
- text preprocessing for sentiment analysis 
- keyword analysis (Doc2Vec, gensim) 

#### Figures: 
- pos_neg_neut_wordcloud.png (data: WordCloud.xlsx)
- negative_20.png (data: negative_20.xlsx)
- positive_20.png (data: positive_20.xlsx)
- temp-plot.html (interactive radar plots by Plotly)
- tsne_cluster.png 


![0001](https://user-images.githubusercontent.com/89289320/163649479-35296ccc-cc6b-4006-882c-456381128f98.jpg)
![0002](https://user-images.githubusercontent.com/89289320/163649481-0f7cd5e0-1588-437e-8dc9-e96bf1329453.jpg)
![0003](https://user-images.githubusercontent.com/89289320/163649482-6c3e0ddb-a117-4aa2-ab79-77e49a126411.jpg)
![0004](https://user-images.githubusercontent.com/89289320/163649485-d8a4015b-9399-47ea-870e-369356a8e756.jpg)
![0005](https://user-images.githubusercontent.com/89289320/163649487-76dcd08d-fd28-41d6-8a0e-403d40f27c95.jpg)
![0006](https://user-images.githubusercontent.com/89289320/163649488-d245103e-8926-4efe-90f9-da59ea04632e.jpg)
![0007](https://user-images.githubusercontent.com/89289320/163649489-47b73fd6-3ba9-44a5-a279-8eab985c1978.jpg)
![0008](https://user-images.githubusercontent.com/89289320/163649491-511cd2e0-b40a-479d-99b5-e7bb5e743eb2.jpg)
![0009](https://user-images.githubusercontent.com/89289320/163649494-566a0fc4-7f39-4eab-98d7-e664c6a13b2a.jpg)
![0010](https://user-images.githubusercontent.com/89289320/163649495-174eca2a-12b7-4f81-a066-ac7cf16f6497.jpg)
![0011](https://user-images.githubusercontent.com/89289320/163649497-f5f01312-7520-4a6f-8bd2-0423b1102c35.jpg)
![0012](https://user-images.githubusercontent.com/89289320/163649499-67e0c142-50e9-484a-ad71-5aa1a493090f.jpg)
![0013](https://user-images.githubusercontent.com/89289320/163649500-4f81bcf7-dd8c-464c-8075-83686e89e448.jpg)
![0014](https://user-images.githubusercontent.com/89289320/163649502-9124c2bf-b1f1-4c10-8c8d-ff4168c44e7c.jpg)
