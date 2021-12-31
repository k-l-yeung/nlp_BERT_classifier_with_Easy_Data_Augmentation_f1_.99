### <a id='overview'>1. Overview</a>

- **Goal**: To compare various models' performance (ML vs. BERT) on the classic spam vs ham message dataset *with or without* the technique of over-/under- sampling and Easy Data Augmentation [EDA](https://github.com/jasonwei20/eda_nlp)
- **Take away**: 
  - For ML models, oversampling with EDA in svc yields the best f1 score (**~.83**) compared to the best-performing NB without EDA (**~.72**) 
  - Even with under sampling, BERT achieved f1 scores **>.95**.  With the implementation of EDA, f1 **>.99**.
  - EDA appears to be a valuable resource for text classification
 
