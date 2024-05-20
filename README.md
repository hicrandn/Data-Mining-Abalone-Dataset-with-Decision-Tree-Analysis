Data Mining Abalone Dataset with Decision Tree Analysis

Objective The objective is to predict the age of abalone from physical measurements. The age of an abalone is typically determined by cutting the shell through the cone, staining it, and counting the number of rings under a microscope, which is tedious and time-consuming. Other measurements that are easier to obtain can be used to estimate the age. Additional information such as weather and location (which influences food availability) might be necessary to solve the problem. Samples with missing values (mostly missing predicted values) were removed from the original data, and ranges of continuous values were scaled for use with an Artificial Neural Network (scaled by dividing by 200).

Methodology The dataset was obtained from http://archive.ics.uci.edu/ml/datasets/Abalone. The data was then checked to ensure there were no missing values.

Feature Types and Names: Sex: Represents the gender of the abalone and is a categorical value (Male, Female, or Infant). Length: The longest measurement of the abalone shell in millimeters. Continuous numerical value. Diameter: Measurement perpendicular to the length of the abalone shell in millimeters. Continuous numerical value. Height: The height of the shell in millimeters. Continuous numerical value. Whole Weight: The weight of the abalone in grams. Continuous numerical value. Shucked Weight: The weight of the abalone's meat in grams. Continuous numerical value. Viscera Weight: The weight of the abalone after gutting in grams. Continuous numerical value. Shell Weight: The weight of the abalone shell after drying in grams. Continuous numerical value. Rings: This is the target variable and will be used to train the model. It relates to the age of the abalone, with the age being the number of rings plus 1.5 years. Continuous numerical value.

Classification Report for Abalone Age Prediction Precision, Recall, and F1-Score for Each Age Group: Middle-aged: Precision: 0.61 Recall: 0.21 F1-Score: 0.32 Support: 234

Old: Precision: 0.53 Recall: 0.86 F1-Score: 0.65 Support: 295

Young: Precision: 0.80 Recall: 0.72 F1-Score: 0.76 Support: 307

Overall Performance Metrics: Accuracy: 0.63 Macro Average Precision: 0.65 Recall: 0.60 F1-Score: 0.58

Weighted Average Precision: 0.65 Recall: 0.63 F1-Score: 0.60

This classification report provides the detailed performance metrics of the decision tree model used for predicting the age categories of abalones. The metrics include precision, recall, F1-score, and support for each age group (middle-aged, old, and young). The overall accuracy of the model is 0.63, with macro and weighted averages provided for precision, recall, and F1-score. Improvement in Model Score:0.64
