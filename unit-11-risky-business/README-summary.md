# Unit 11 - Risky Business
 
![Credit Risk](Images/credit-risk.jpg)  

### Summary.md, responses to analsysis questions and conclusions are forthcoming as insight/code corrections are commited. Seeking advice from Instructors. 

## Supplemental  

<details ><summary>Disclose</summary>  

#### Note  

<sup><a id="ref100">100</a></sup> Brownlee, Jason (2020-08-26). Stratified Train-Test Splits. Retrieved from [machinelearningmastery.com](https://machinelearningmastery.com/train-test-split-for-evaluating-machine-learning-algorithms/).  

<blockquote style="border-left: 0px solid #ccc; color: rgb(88, 166, 255);"><details><summary>Disclose 100</summary>  

Stratified Train-Test Splits  

One final consideration is for classification problems only.  

Some classification problems do not have a balanced number of examples for each class label. As such, it is desirable to split the dataset into train and test sets in a way that preserves the same proportions of examples in each class as observed in the original dataset.  

This is called a stratified train-test split.  

We can achieve this by setting the “stratify” argument to the y component of the original dataset. This will be used by the train_test_split() function to ensure that both the train and test sets have the proportion of examples in each class that is present in the provided “y” array.</details></blockquote>  

<sup><a id="ref101">100</a></sup> Nik (2022-01-05). Splitting Your Dataset with Scitkit-Learn train_test_split. Retrieved from [datagy.io](https://datagy.io/sklearn-train-test-split/).  

<blockquote style="border-left: 0px solid #ccc; color: rgb(88, 166, 255);"><details><summary>Disclose 101</summary>  

Splitting Your Dataset with Scitkit-Learn train_test_split  

You now have four different variables created: a testing and training dataset for each X and y. We asked Scikit-Learn to stratify the dataset. This can be helpful when you’re trying to classify an imbalanced dataset, where there isn’t a balance between the different classes.</details></blockquote>  

</details>