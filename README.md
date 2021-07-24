# The-Mushroom-Analysis
Mushroom project of Phase 1 Datatrained

Though field experts determine that is that there is no simple set of rules to identify whether a mushroom is edible or not, it seems like with these algorithms we can get pretty close based upon numerical characteristics. The models above identified specific traits that seem to heavily influence the chance that a mushroom could be edible. Specifically, when tuning the logistic regression lasso model, there are a few coefficients identified that play an important role in the classification process. 

* **Gill Size**: If the gills are narrow, the mushroom is likly to be poisonous.  If they are broad, then it’s more likely to be edible. 

* **Ring Type**: Pendant ring types are very likely to be edible. Evanescent and large ring types are likely to be poisonous. 

* **Cap Surface**: If the mushroom has a more fibrous surface, it’s more likely to be edible. Smooth or scaly mushrooms are slightly more likely to be poisonous. 

* **Bruises**: If the mushroom has bruises, it’s likely to be edible. If the mushroom does not have bruises, it’s more likely to be poisonous. 

* **Spore Print Color**: Black and brown are highly likely to be edible. Tan and white colors are highly likely to be poisonous. 
