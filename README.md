# Spam_Classifier

Spam classification is important to detect unwanted and unsolicited messages, which are often capable of defrauding the readers and causing losses.     
The dataset that we're using contains 5569 entries, of which 745 are spam.

##  Libraries used  
Pandas    
Numpy   
Sklearn   
Nltk    
Re

##    Process   
First, we manipulate the dataset to remove all Non-Alphabet characters from the data.  
Then we Lemmatize the words that are left in the messages, after which we Vecorize them using the TFID Vectorizer.    
Lastly, we fit this data into a model that uses the Multiomial NB algorithm.      

After our model is trained, we use model evaluation parameters to check the performance of the model by making the Confusion Matrix       
<img width="418" alt="Screenshot 2023-01-07 at 1 55 16 PM" src="https://user-images.githubusercontent.com/72307339/211141299-aabc1e4e-62a4-40f6-9d9c-de536c9efe9c.png">     
From the confusion matrix, we can get the following parameters:   

<img width="174" alt="Screenshot 2023-01-07 at 1 55 39 PM" src="https://user-images.githubusercontent.com/72307339/211141314-6adda181-fa92-44e1-b7ef-615e4ba2e5ec.png">       
Thank you!

