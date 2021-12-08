# Team_SmartWorkers
Transport decision making for Fairfax County

#### Team_SmartWorkers/% mismatch based on Transport Unit ID and related features.twbx
The Visualization shows % mismatch and various influential features. There were specific unit ID's (fire station units) who's behavior was inclined from normal behavior. 

#### Team_SmartWorkers/Facilities frequently visited by Units.twbx
The dashboard shows us the frequently visited facilities by units. Whenever any incident occurs fire personnel take the victims to hospitals. This visualization focuses on the top three hospitals preferred by every unit.

#### Team_SmartWorkers/Model-1_Random_Forest_using_GridSearchCV.ipynb
#### Model 1 - Random_Forest
Final model contains features from units, incidents, patients and facilities dataset merged
Also the distance between each unit and facilities were added using haversine formulae
Dataset used - Patients, Units, Incidents, facilities datasets merged with distance between each Unit ID and facility
F1-score - 0.70, Accuracy- 74%

#### Team_SmartWorkers/Model-2_to_6_using_DecisionTree_RandomForest_top20features.ipynb
#### Model 2- Random_Forest
Dataset used -  Patients, Units, Incidents and  facilities datasets merged
F1-score -0.91, Accuracy- 93%

#### Model 3 - Decision Tree
Dataset used -  Patients, Units, Incidents and  facilities datasets merged
F1-score -0.61, Accuracy- 67%

#### Model 5 - Decision Tree
Dataset used -  Patients, Units, Incidents, facilities datasets merged - Only Top 20 important features
F1-score -0.62, Accuracy- 67%

#### Model 6- Random_Forest
Dataset used - Patients, Units, Incidents, facilities datasets merged - Only Top 20 important features
F1-score -0.93, Accuracy- 94%

#### Team_SmartWorkers/Model_7_to_8_using_RF_LightGBM.ipynb
#### Model 7- Random_Forest
Dataset used - Patients, Units, Incidents, facilities datasets merged - By removing top 3 influential features
F1-score -0.64, Accuracy- 71%

#### Model 8- LightGBM
Dataset used -Patients, Units, Incidents, facilities datasets merged - By removing top 3 influential features
F1-score -0.7,Accuracy- 69%

#### Model 9 - Logistic Regression
Dataset used -With 2 features - TransportUnitID, TransportLOC 
F1-score -0.7,Accuracy- 72%


