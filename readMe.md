# Market Analysis Techniques

This project has been carried out by Jaideep Singh under the guidance of his supersivors as a part of the Thesis requirement at the University of Sydney.

Graph Data can also be found at: https://docs.google.com/spreadsheets/d/1Wl5Liav6NYro0c0XrJhdcTNw3z_gmuQs_bsJEpoQtQw


## File Structure

### Extraction

* transform.ipynb

### Classifiers

* RandomForest.ipynb
* KNN.ipynb	
* NaiveBayes.ipynb	
* NeuralNetwork.ipynb	
* DecisionTree.ipynb
* SVM.ipynb	

These files can be configured to operate either on the entire dataset or perform the analysis on various sectors by toggling the following parameters:

* check_each_sector: Perform a sector wise analysis if True
* less_columns: Use only the columns selected after Feature Selection if True
* minify: output only the precsion for buy signals, recall for sell signals and overall accuracy instead of the entire sklearn classification report if True
* print_data: prints the output as the classifier is run if True

### Feature Elimination 
* PCA.ipynb
* Compare_features_sets.ipynb	
* ExhaustiveFeatureSelection.ipynb	

### Results
* Graph Data and Graphs.zip	




