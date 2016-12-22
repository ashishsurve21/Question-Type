# Question-Type
Identify Question Type: Given a question, the aim is to identify the category it belongs to. The four categories to handle for this assignmentare : Who, What, When, Affirmation(yes/no).


Pre-Requisites:

1. Python 3
2. Nltk
3. Sklearn

The code contains two main files: 
  1. FeatureSetClass.py
  2. Qtype.py
  
 In order to run the code, you have to run the Qtype.py file which trains the model if the pretrained model file is absent.
 If it finds the pretrained model then it will load the model and tag the input questions.
 
 Have will have to change the following paths in the Qtpye.py file.
 
1. lib_path : path to the pre-trained model file
2. input :  path to the input file
3. result_path : path to the output file
4. path : path to the training file (if you want to change the training data)
