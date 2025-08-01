PROJECT OVERVIEW:
This project utilizes a supervised binary classification problem framework that predicts 
whether the connotation of a book review is positive, or non-positive (negative or neutral). 

METHODOLOGY:
I utilize a feedforward neural network, implementing three hidden layers (64, 32, 16 respective units) which each use a ReLU activation function. My data set is split into 
a test and validation set, which will be acted on by my compilation (comprised of a sgd optimizer, a binary cross entropy function, and a loss function).
I accounted for class imbalances, missing book reviews, and missing labels. I employed NLP data cleanign and preprocessing techniques utilizing TF-IDF vectorizers, removing stop words and transforming textual data into numerical features. 

RESULTS:
I analyzed my results by tracking the training and validation losses, as well as the training and validation accuracies. My findings and relationships between the features and labels were visualized via Matplotlib and Seaborn libraries. 

KEY FINDINGS:
- Training and validation losses (respectively) depreciated, while training and validation accuracies increased.
- Data was not overtrained and performed sufficient generalization to new data. 

NEXT STEPS:
- Testing the model on more unseen book review examples to test how scalable my model is.
  
