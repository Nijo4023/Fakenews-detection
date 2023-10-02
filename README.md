# FakeNews-detection
FakeNews detection using NLP
Dataset collection:
        Dataset was collected from Kaggle.com
        Dataset link:https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset
        The dataset contains articles of title and text along with labels of genuine and fake news
Modules used:
        pandas:it is a library used for Data Manipulation
        numpy :it is library used to perform numerical calculations
        sklearn: it is a machine learning library used in python contains many inbuilt algorithms
Data preprocessing:
      step1:First clean the dataset by filling or ignoring the missing values
      step2:concatinate the two datasets contains true and fake news and suffle the data
      step3:Categorize the data 
      step4:Convert the text into numerical form by using TfidfVectorizer it is one of the Feature extraction method
      step5:split the data into training and testing
      step6:train the model using LogisticRegression algorithm
      How LogisticRegression work:
                  Logistic regression is a data analysis technique that uses mathematics to find the relationships between two data factors. It then uses this relationship to predict the value of one of those     
      factors based on the other. The prediction usually has a finite number of outcomes, like yes
      step7:Find the Accuracy score,precision,recall,f1-score,rou-auc
Manual testing:
      Test the model by giving input and check the output
      
      
    
