# Complex_model
Purpose: How does the level of brown spot needle blight infection affect the growth rate of loblolly pine trees? How much growth would be lost in a tree that is severely diseased vs a tree with no disease?

Entities, state variables, and scales: This model has one entity, tress. State variables are the amount amount of disease present on the tree- none, low, medium, high.

Process overview: The processes of the model will include how much disease is present on the tree, thinning, cutting dying trees, normal death of a forest (1-3%), and yearly growth.

Design concepts: I want to address how disease presents affects loblolly pine tree growth. A model will be created to see how growth changes within each disease level. Each tree will get randomly assigned diseased and can only get more diseased. No tree can recover drom disease since that is how it seems to be playing out in nature. The model will take into account natural death which is typically 1-3% withing a stand. On top of this, some trees may die from the disease.

Initialization: 1 acre of loblolly pine will be looked at, starting with 600 trees and will get thinned on a 5 year rotation.

Input data: The environment will remain constant and will not take into account temperature or rainfall.

Submodels: population size will decrease as the stand is thinned and dying trees are removed.
