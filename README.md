### <a id='overview'>1. Overview</a>

- **Goal**: To compare various models' performance (ML vs. BERT) on the classic spam vs ham message dataset *with or without* the technique of over-/under- sampling and Easy Data Augmentation [EDA](https://github.com/jasonwei20/eda_nlp)
- **Take away**: 
  - For ML models, oversampling with EDA in svc yields the best f1 score (**~.83**) compared to the best-performing NB without EDA (**~.72**) 
  - Even with under sampling, BERT achieved f1 scores **>.95**.  With the implementation of EDA, f1 **>.99**.
  - EDA appears to be a valuable resource for text classification
 
##### Performance of BERT with EDA on spam classification 
!![image](https://user-images.githubusercontent.com/58142773/147840942-fcdfe8bc-f640-45d7-9d2b-1bdc66da4ace.png)

#### Technique / libraries used
- Key libraries: sklearn, nltk, tensorflow, imblearn
- Word embedding: Bag of words, TF-IDF
- Deep learning: BERT
- Overfit prevention in deep learning: EarlyStopping, Dropout
- Sampling: oversampling, undersampling

#### References
- EDA: Easy Data Augmentation Techniques for Boosting Performance on Text Classification Tasks ([paper](https://arxiv.org/abs/1901.11196)) ([repo](https://github.com/jasonwei20/eda_nlp))
- Contextual Augmentation: Data Augmentation by Words with Paradigmatic Relations ([paper](https://arxiv.org/abs/1805.06201)) ([repo](https://github.com/pfnet-research/contextual_augmentation))

### <a id='sam'>2. About the author: Kam Leung Yeung (Sam)</a>
* PhD in Cognitive Psychology, Iowa State University in Ames, Iowa, USA

**Social media**:
* [LinkedIn](https://www.linkedin.com/in/kamleungyeung/)
* [Google Scholar](https://scholar.google.com/citations?user=OwUmaN8AAAAJ)
* [GitHub](https://github.com/k-l-yeung)
* [Tableau](https://public.tableau.com/app/profile/kam.leung.yeung#!/)

**Data source**
- [SMS Spam collection Data Set](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection#)

### <a id='toc'>3. Table of content</a>
1. <a href='#overview'>Overview</a>  
2. <a href='#sam'>About the author: Kam Leung Yeung (Sam)</a> 
3. <a href='#toc'>Table of content</a> 
4. <a href='#rd'>Read data</a>  
5. <a href='#de'>Data exploration</a>  
 - <a href='#wc'>Word clouds of ham and spam texts</a>  
6. <a href='#p'>Preprocessing</a>  
8. <a href='#hid'>Handling imbalanced data</a>  
7. <a href='#fe'>Feature Engineering</a>
9. <a href='#bc'>Build classifiers</a>  
10. <a href='#cp'>Check performance</a>  
10. <a href='#pml'><b>Performance of various ML models</b></a>  
11. <a href='#easy'>Easy data augmentation (EDA) implementation </a>  
12. <a href='#best'><b>Best ML model's</b> confusion matrix, ROC, precision-recall curve</a>  
11. <a href='#mp'>Make prediction</a>  
12. <a href='#sm'>Save models</a>  
16. <a href='#bert'>BERT</a>
  - <a href='#dbm'>Define the BERT model</a>
  - <a href='#ceda'>Compare BERT models with or without EDA</a>
  - <a href='#pberteda'><b>Performance of BERT with EDA. f1 = .99</b></a>
