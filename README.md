# Credit_model


[![Gmail Badge](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:reejugn.kim@gmail.com)](mailto:reejung.kim@gmail.com) 
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=www.linkedin.com/in/reejungkim/)](https://www.linkedin.com/in/reejungkim/) 
[![Git page](http://img.shields.io/badge/-Portfolio-black?style=flat-square&logo=github&link=https://reejungkim.github.io/)](https://reejungkim.github.io/)
<br></br>

[View code: PSI calculation](https://github.com/reejungkim/Credit_model/blob/main/PSI%20calculation.ipynb)

[View code: Scorecard](https://nbviewer.jupyter.org/github/reejungkim/Credit_model/blob/main/scorecard.ipynb)

[View code: bankruptcy prediction](https://nbviewer.jupyter.org/github/reejungkim/Credit_model/blob/main/Predicting%20bankruptcies.ipynb)
- feature reduction: recursive feature selection with cross validation (RFECV)
- classifier models applied: random forest, gradientboost, xgboost, lightGBM
- hyperparameter optimization: RandomSearchCV, GridSearch 
- metrics for model evaluation: confusion matrix, ROC-AUC, accuracy, precision, recall, f1-score, support
- metrics for feature importance: feature importance, Shapley values, Morris sensitivity
<img src="img/roc.png" height="200" width="300"> 


#### ROC explanation

<img src="img/auc1.png" height="100" width="200"> <img src="img/auc07.png" height="100" width="200"> <img src="img/auc05.png" height="100" width="200"> 

#### Binary claissifier evaluation metrics explanation:

<img src="img/EvaluationMetrics.png" height="200" width="470"> 
  (trade-off between Precision and Recall)


#### Model explainer

<img src="img/feature_importance.png" height="200" width="400"> <img src="img/shap.png" height="200" width="400"> <img src="img/morris.png" height="200" width="400"> 



### References 
- [sklearn GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
- [Towards Data Science model tuning](https://towardsdatascience.com/streamline-model-tuning-on-bankruptcy-predictions-aabbc2fe62c0)
- [RFECV](https://process-mining.tistory.com/138)
- [소매금융 신용평가 및 스코어링모형의 적합성 검증 PPT](https://slidesplayer.org/slide/17900551/https://slidesplayer.org/slide/17900551/)
- [2021 가명정보 활용 우수사례 대상 카카오뱅크 유튜브](https://www.youtube.com/watch?v=Ieqvp8n5PnE&ab_channel=K-ICT%EB%B9%85%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%84%BC%ED%84%B0)
- [카뱅 신용평가모델 삼프로 유튜브](https://www.youtube.com/watch?v=XwMwmpyNsdA&ab_channel=%EC%82%BC%ED%94%84%EB%A1%9CTV_%EA%B2%BD%EC%A0%9C%EC%9D%98%EC%8B%A0%EA%B3%BC%ED%95%A8%EA%BB%98)

