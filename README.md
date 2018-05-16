# Spam-Ham-Classification
Python code for Spam Ham classification of e-mails using Naive-Bayes Classifier and Logistic Regression methods, with and without stop words.
## Running 
### Naive Bayes
Run the following command - <br><i>python naiveBayes.py 'spam training folder' 'ham training folder' 'spam test folder' 'ham test folder' 'stop Word file location'</i>

### Logistic Regression
Run the following command -<br> <i>python logisticRegressionMain.py 'spam training folder' 'ham training folder' 'spam test folder' 'ham test folder' 'learningConst' 'penaly Lambda' 'num of Iterations' 'stopWords location file'</i>

## Output
### Naive Bayes
Accuracy without removing stopwords=94.56% <br>
Accuracy after removing stopwords=93.93%

### Logistic Regression

Learning Const | Lambda  | Iterations| Accuracy W/O StopWords|  Accuracyafter Removing StopWords
-------------- | ------- |-----------| ----------------------| --------------------------
0.01           |  2      |  10       | 92.46                 | 89.74
0.01           | 3       |  20       | 89.12                 | 86.82
0.001          |  1      | 20        |  88.91                | 87.029
0.0001         | 1       | 30        |   86.40               | 79.07
0.0001         | 2       | 50        |  87.23                | 81.38
0.01           | 2       | 10        |  92.05                | 92.25
