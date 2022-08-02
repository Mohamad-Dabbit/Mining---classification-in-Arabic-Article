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


| Classification      | Feature Extraction | accuracy | Time         | RAM ABOVE 1GB |
| ------------------- | ------------------ | -------- | ------------ | ------------- |
| SVC                 | TfIdf              | 96.043   | 3h 57min 16s | 2.13          |
| NN                  | TfIdf              | 95.921   | 30min 21s    | 1.05GB        |
| Logistic Regression | TfIdf              | 95.735   | 5min 36s     | 0.64          |
| NN                  | Count Vectorizer   | 95.701   | 4min 50s     | 0.86GB        |
| Logistic Regression | Count Vectorizer   | 95.465   | 7min 36s     | 0.79          |
| CNN                 | Embedding          | 95.038   | 5h 56min 21s | 1.6           |
| SVC                 | Count Vectorizer   | 94.591   | 2h 29min 4s  | 2.3           |
| Random Forest       | TfIdf              | 93.791   | 1h 8min 7s   | 3.12          |
| Random Forest       | Count Vectorizer   | 93.69    | 2h 55min 4s  | 2.1           |
| DecisionTree        | Count Vectorizer   | 85.78    | 7min 8s      | 1.6 GB        |
| DecisionTree        | TfIdf              | 85.238   | 7min 51s     | 2.2           |
| NN                  | Embedding          | 80.083   | \>6h         | 1.7           |
| XLNet               | XLNet              | 20.225   | \>6h         |               |


![acc](https://user-images.githubusercontent.com/78812316/182325533-74a143ee-fe69-4d42-a936-8aa190a7013f.jpg)


Dataset Sources:

https://www.kaggle.com/datasets/saurabhshahane/arabic-classification


**The Orginal Code Sources:**

Clean Sources:
https://www.kaggle.com/code/khalilalla/textmining-project


CNN:
https://colab.research.google.com/github/dipanjanS/nlp_workshop_odsc19/blob/master/Module05%20-%20NLP%20Applications/Project07B%20-%20Text%20Classification%20Deep%20Learning%20CNN%20Models.ipynb#scrollTo=iaqFz7ZpdoLC
