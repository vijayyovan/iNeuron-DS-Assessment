# iNeuron-DS-Assessment

iNeuron DS Assessment
vijay6206@gmail.com Switch account
 
Not shared
 
* Indicates required question
Python:

Total Marks: 40
Each question 10 marks 


Question: 1


You have an input dictionary given,

input_dict = {"abc":{"def":{"ghi":{"jkl":{"mno":{"pqr":{"stu":{"vwx":{"yz":"you are finally here !!!"}}}}}}}}}

Task:  You have to write a Python function that will take this input and print it like that,

output = {"abc":["def","ghi","jkl","mno","pqr","stu","vwx","yz"],
 "def":["ghi","jkl","mno","pqr","stu","vwx","yz"],
 "ghi":["jkl","mno","pqr","stu","vwx","yz"],
 "jkl":["mno","pqr","stu","vwx","yz"],
 "mno":["pqr","stu","vwx","yz"],
 "pqr":["stu","vwx","yz"],
 "stu":["vwx","yz"],
 "vwx":["yz"],
 "yz":["you are finally here !!!"]}





Question: 2


Given an array of length ‘N’, where each element denotes the position of a stall. Now you have ‘N’ stalls and an integer ‘K’ which denotes the number of horses that are mad. To prevent the horses from hurting each other, you need to assign the horses to the stalls, such that the minimum distance between any two of them is as large as possible. Return the largest minimum distance.

array: 1,2,4,8,9  &  k=3

O/P: 3

Explanation: 1st horse at stall 1, 2nd horse at stall 4 and 3rd horse at stall 8



Question: 3
Mr. Karthiken works in a door mat manufacturing company. One day, he designed a new door mat with the following specifications:

             a) Mat size must be N X M. (N is an odd natural number, and M is 3 times N.)
              b) The design should have ‘WELCOME’ written in the center.
              c) The design pattern should only use |, . and – characters.

    Sample Design is given above image, Write a python code for this.


Question: 4

Given an array nums of n integers, return an array of all the unique quadruplets [nums[a], nums[b], nums[c], nums[d]] such that:

   a) 0 <= a, b, c, d < n
   b) a, b, c, and d are distinct.
   c) nums[a] + nums[b] + nums[c] + nums[d] == target
SQL:

Total Marks: 40
Each question 10 marks 
Question: 1

Given the following tables:

What will be the result of the query below?

SELECT * FROM runners WHERE id NOT IN (SELECT winner_id FROM races)

Explain your answer and also provide an alternative version of this query that will avoid the issue that it exposes.

Question: 2

Given two tables created as follows
Write a query to fetch values in table test_a that are and not in test_b without using the NOT keyword.
Question: 3

Given the following tables:
Write a query to to get the list of users who took the a training lesson more than once in the same day, grouped by user and training lesson, each ordered from the most recent lesson date to oldest date.

Question: 4

Consider the Employee table below.
Statistics:

Total Marks: 40
Each question 10 marks 

Question: 1

 What is the meaning of six sigma in statistics?  Give proper example


Question: 2

What type of data does not have a log-normal distribution or a Gaussian distribution?  Give proper example


Question: 3

What is the meaning of the five-number summary in Statistics? Give proper example


Question: 4

What is correlation? Give an example with a dataset & graphical representation on jupyter Notebook



Machine learning:

Total Marks: 60
Each question 20 marks   


Question: 1

Imagine you have a dataset where you have different Instagram features like u sername , Caption , Hashtag , Followers , Time_Since_posted , and likes , now your task is to predict the number of likes and Time Since posted and the rest of the features are your input features. Now you have to build a model which can predict the number of likes and Time Since posted. 

Dataset This is the Dataset You can use this dataset for this question. 



 Question: 2

    Train an SVM regressor on : Bengaluru housing dataset

    Must include in details:

  - EDA

  - Feature engineering 




Question: 3

Train and fine tune a decision tree using the wine dataset by following the following steps:-

  1. Use load_wine() to generate wine dataset
  2. Split the dataset into train and test  dataset
  3. Use random search CV to hyperparameter tune the Decision Tree
  4. Try to achieve an accuracy of at least 85%


Grow a random forest using the following steps:-

  1. Continuing the previous question, create 10 subsets of the training dataset. You can use the ShuffleSplit                class for it.
  2. Train 1 decision tree on each subset, using the best hyperparameter values found in the previous question.
  3. Evaluate all the trees on the test dataset. Are they performing better than the tree created in the previous question?


Deep Learning :

Total Marks: 60
Each question 20 marks    


Question: 1

(a) Explain how you can implement DL in a real-world application.

(b) What is the use of Activation function in Artificial Neural Networks? What would be the problem if we don't use it in ANN networks.



Question: 2

Train a Pure ANN with less than 10000 trainable parameters using the MNIST Dataset

Question: 3 

Perform Regression Task using ANN

Note: You are feel free to use any Regression ML dataset
Submission Process


There are Two Types of Questions Theory based Question and Project-based (where you actually have to code)


First and foremost, set up a github repository and save all of your answers there.


Create a Google Doc with written answers to all questions, explaining theory. Keep it in the GitHub repository for easy access.

When coding is required, create a folder in the same GitHub repository, upload your code, and share the repository link for submission.


Eg. Answer. 6 Python  - > GitHub repo link 

Note:

    If you are building any End to end project try to write code in .py file

    If you are only analyzing or doing EDA use .ipynb file

Submit the final GitHub repo link containing all answers, ensuring completeness and easy access for evaluation.

Your Name:  *
Your Email: *
Your Phone Number:  *
Give your submission link:
*
Never submit passwords through Google Forms.
This form was created inside of iNeuron Intelligence Private Limited. Report Abuse
Google Forms
