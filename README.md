# Moview review prediction model

This model uses IMDB movie review datasets and Support Vector Machine(SVM) as classifiers to predict if the review is positive or negative. Label "1" indicates the positive reviews while "0" indicates negative reviews.


### **Features adopted in this model:**
1. Word frequency
2. Term frequency–inverse document frequency (TF-IDF)
3. Word Length

### **Features adopted in the final model:**
Word frequency and TF-IDF.<br/>
Chi-Square and Select K Best methodologies has been adopted for feature selection to select top 500 relevant feature to predict positive and negative reviews.


### **Instructions to run from terminal:**
1. Make sure you have installed Jupyter Notebook, use command "$ jupyter notebook" in command.
2. Run the "part2code.ipynb" file in jupyter notebook from top to bottom.
3. Since training model and predicting performs an exhaustive evaluation of all the models across all the features, it may takes a long time to execute.
