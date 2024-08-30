Instructions: 
Open the Jupyter Notebook and load the given “english_big.txt” file and code file  “Feature_extraction_set(Code).ipynb” into the notebook 
Open and Run the code file named “Feature_extraction_set(Code).ipynb”.
The output file obtained is a csv file named “feature_set.csv”.
As per the requirements mentioned the output file should be an arff file for easy loading into weka and for classifying. In the name of efficiency & availability a new feature of weka has been adapted by us where we have loaded  a csv file (which has been obtained from feature set file) for classification(But we have even followed the requirement and proceeded further).
Open weka tool and click on “Experimenter” go to “Analyse” tab then click on “file” button which is present to the right side of the window and load it with the “feature_set.csv” and then click on “open explorer” button and save the file to your device as arff for further use ,for classifying continue with the explorer.
Click on classify tab select 10 folds for cross-validation and for column “label” under classifier click “choose” button then go to trees ->J48 for Decision tree and click on “start” button, the classification starts and shows the classification.
For RandomForest classifier go to the “choose” button again, then go to trees ->RandomForest and click on “start” button, the classification starts and shows the classification.
For Multinomial Naive Bayes classifier go to the “choose” button again, then go to bayes ->NaiveBayesMultinominalText and click on “start” button, the classification starts and shows the classification.
For K-Nearest Neighbors classifier go to the “choose” button again, then go to lazy ->IBk and click on “start” button, the classification starts and shows the classification.
For SVM (LibSVM) classifier go to the “choose” button again, then go to functions ->SMO(for my weka 3.8.6 version only SMO is available for SVM classification) and click on “start” button, the classification starts and shows the classification.
To save the classification output you can right click on the specific classification file present in Result list and “save as model”.
