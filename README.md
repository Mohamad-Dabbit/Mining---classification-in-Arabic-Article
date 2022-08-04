# Mining---classification-in-Arabic-Article

In this program, we classify articles in Arabic
Where we first clean the text
Then we convert it to numbers via a feature extraction: 

1- TfIdf 

2- Count Vectorizer

3- Word Embedding

4- XLnet


Then we sort through one of the classifiers:

1-DecisionTree

2-RandomForest

3-CNN

4-Logistic regression

5- SVC

---------------------------
في هذا البرنامج نصنف المقالات باللغة العربية
حيث نقوم بتنظيف النص أولاً

ثم نقوم بتحويله إلى أرقام عن طريق استخراج الميزة:

1- TfIdf 

2- Count Vectorizer

3- Word Embedding

4- XLnet


ثم نقوم بالفرز من خلال أحد المصنفات:



1-DecisionTree

2-RandomForest

3-CNN

4-Logistic regression

5-SVC

---------------------------
Resulte:

النتائج:

| num | Classification      | Feature Extraction | accuracy | Time         | RAM ABOVE 1GB |
| --- | ------------------- | ------------------ | -------- | ------------ | ------------- |
| 1   | SVC                 | TfIdf              | 96.0431  | 3h 57min 16s | 2.13          |
| 2   | Logistic Regression | TfIdf              | 95.7349  | 5min 36s     | 0.64          |
| 3   | NN                  | Count Vectorizer   | 95.7013  | 4min 50s     | 0.86GB        |
| 4   | NN                  | TfIdf              | 95.6278  | 4min 13s     | 1.05GB        |
| 5   | Logistic Regression | Count Vectorizer   | 95.4649  | 7min 36s     | 0.79          |
| 6   | CNN                 | Embedding          | 95.0378  | 5h 56min 21s | 1.6           |
| 7   | SVC                 | Count Vectorizer   | 94.5908  | 2h 29min 4s  | 2.3           |
| 8   | Random Forest       | TfIdf              | 93.7914  | 1h 8min 7s   | 3.12          |
| 9   | Random Forest       | Count Vectorizer   | 93.6903  | 2h 55min 4s  | 2.1           |
| 10  | Decision Tree       | Count Vectorizer   | 85.7799  | 7min 8s      | 1.6 GB        |
| 11  | Decision Tree       | TfIdf              | 85.2384  | 7min 51s     | 2.2           |
| 12  | NN                  | Embedding          | 80.0826  | \>6h         | 1.7           |
| 13  | XLNet               | XLNet              | 20.2247  | \>6h         |               |


![acc](https://user-images.githubusercontent.com/78812316/182844713-82b070ba-c3a8-458e-91b3-738e7f5cd9dc.jpg)


**Sources:**


Dataset Sources:

https://www.kaggle.com/datasets/saurabhshahane/arabic-classification


**The Orginal Code Sources:**

Clean Sources:
https://www.kaggle.com/code/khalilalla/textmining-project


CNN:
https://colab.research.google.com/github/dipanjanS/nlp_workshop_odsc19/blob/master/Module05%20-%20NLP%20Applications/Project07B%20-%20Text%20Classification%20Deep%20Learning%20CNN%20Models.ipynb#scrollTo=iaqFz7ZpdoLC
