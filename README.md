# Project1_NLP_Blog_authorship

PROJECT OBJECTIVE: The need is to build a NLP classifier which can use input text parameters to determine the label/s of the blog
### Steps and tasks: 
1. Import and analyze the data set.
   * Removing Duplicates
   * Missing values
   * Visualization by using count plot on age, gender and sign
   * Considering small sub-set from the dataset


2. Perform data pre-processing on the data: 
   * Data cleansing by removing unwanted characters, spaces, stop words etc. Convert text to lowercase. 
   * Target/label merger and transformation
   * Train and test split
   * Vectorization, etc. 

3. Design, train, tune and test the best text classifier.
   * Implementing MultilableBinarizer
   * Used Logistic regression
   * SVM
   * Navie Bayes 

4. Display and explain detail the classification report
   *In this model has 70 classes are there, Classification report gives Precision,Recall ,f1-score and support for each of these classes separately.

   *classes 13,36,46,banking, capricon,leo, libra etc. having 100% precision while some classes like 39 to 45, accounting and taurus etc. having 0% precision.

   *Mostly classes have a high precision greater than 50%. It means that from the total predictions our model has made, approx 50% are correct.

   *Recall for most classes is low. Few classe have both precision and recall 0%, hence there f1 score is also 0. For that classes support are single digit number and     it is very low.

   *Our data was highly imbalanced. Hence the model was biased in predicting the majority classes correctly.

   *The minority classes could not be correclty predicted by our model. Such classes have both Recall and precion as 0.

   *The classes having higher support value(number of actual occurances of the class) have a good precision and recall as well.

   *In this case f1-score is consider because f1-score is the harmonic mean of recall and precion.
  
5. Print the true vs predicted labels for any 5 entries from the dataset.



# Project2_c• PROJECT OBJECTIVE: Design a python based interactive semi - rule based chatbot which can do the following:
 

• PROJECT OBJECTIVE: Design a python based interactive semi - rule based chatbot which can do the following:
1. Start chat session with greetings and ask what the user is looking for. 
2. Accept dynamic text based questions from the user. Reply back with relevant answer from the designed corpus. 
3. End the chat session only if the user requests to end else ask what the user is looking for. Loop continues till the user asks to end it. 

