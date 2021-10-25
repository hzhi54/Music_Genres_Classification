# MVP

So far for my projects, I've tested three different models to classify genres for music. The three models are Logistic Regression, 
K-Nearest Neighbor Classifier, and Decision Tree Model. Here is the result below: 

Logistic Regression:

    Accuracy:  0.3918918918918919
    Precision:  0.356630831999753
    Recall:  0.39031085471575816
    F1-Score:  0.35638298906971216
    
KNN Classifier:

    Accuracy:  0.44894894894894893
    Precision:  0.4426861990835417
    Recall:  0.44816873606244734
    F1-Score:  0.44062617462672654

Decision Tree(Depth 5):

    Accuracy:  0.4219219219219219
    Precision:  0.5309277662737862
    Recall:  0.4195804951915404
    F1-Score:  0.39327693203409886

Decision Tree(Depth 10):

    Accuracy:  0.581081081081081
    Precision:  0.5832742629178063
    Recall:  0.5793904855876355
    F1-Score:  0.5794937635094984
    
 
For this upcoming week, I going to use more model to see which models best classifies this problem. I also trying to implement them with optimized parameters
to find out the best results for each model. For example, what is the best depth for the a decision tree model to use like you can see depth 5 scores lower
than depth 10. Then I will use this result to create a ROC graph to see when each model will have the turn of false positive rates. I also record a piano piece
played by me, and let the model classify which category will it be. The answer should be Classical because I will be playing 5-10 seconds of Canon in D and 
Fur Elise and they are categorized as classical music.

