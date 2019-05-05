### Mushroom Toxicity Analysis
### By Joshua E. Jodesty

##### Problem:
"There is no simple rule for determining the edibility of a mushroom" - The Audubon Society Field Guide to North American Mushrooms
##### Dataset:
* 8124 descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family.
* Binary Classification: Edible (4208) or Poisonous (3916)
* Feature Transformation and Significance: 
    * 26 Polytomous Variables transformed into 117 Bernoulli Variables
    * Discerned 21 important/significant Bernoulli Variable features determining mushroom toxicity in order to maintain model performance without overfitting
* Characteristics: Cap, Gill, Stalk, Odor, Veil, Rings, Spores, Habitat, etc.
* Characteristic Descriptions: Color, Shape, Size, Smell, etc.

##### Steps:
* 1. Data Extraction, Cleansing, & Transformation
* 2. Modeling & Feature Importances: Create Model with Random Forest Classifier in order to determine important Bernoulli Variable features determining mushroom toxicity
* 3. Modeling & Evaluation: 
    * 3A. Create 21 Models with Random Forest Classifier; Fit each model with 1 to 21 features; Record cross-valdated evaluation metrics of each model
    * 3B. Plot an interpret evaluation metrics in order to determine Significant Bernoulli Variable features determining mushroom toxicity 
* 4. Evaluate Models created with multiple estimators/algorithms/techniques; Chose Random Forest Classifier 
* 5. Create & Evaluate final model with RandomForestClassifier, fitted with the correct range of features

##### Future Developements:
* Develope model that can Identify Mushrooms based on given given characteristics

###### Data Source
UCI Dataset via:
* Mushroom records drawn from The Audubon Society Field Guide to North American Mushrooms (1981). G. H. Lincoff (Pres.), New York: Alfred A. Knopf 
* Donor: [Jeff Schlimmer] (Jeffrey.Schlimmer@a.gp.cs.cmu.edu)

##### This repository contains an IPython Notebook providing a walkthrough of my project I delivered at Metis
