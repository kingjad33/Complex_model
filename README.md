# Complex_model
Purpose: How does the level of brown spot needle blight infection affect the growth rate of loblolly pine trees? How much growth would be lost in a tree that is severely diseased vs a tree with no disease?

Entities, state variables, and scales: This model has one entity, tress. State variables are the amount of disease present on the tree- none, low, medium, high. This pattern will be compared based on how many trees I currently have that are low, medium, or high. I need to ensure that not all the trees are low and not all are high. 

Process overview: The processes of the model will include how much disease is present on the tree, thinning, cutting dying trees, normal death of a forest (1-3%), and yearly growth.

Design concepts: I want to address how the disease affects loblolly pine tree growth. A model will be created to see how growth changes within each disease level. Each tree will get randomly assigned diseased and can only get more diseased. No tree can recover from disease since that is how it seems to be playing out in nature. The model will consider natural death, which is typically 1-3% within a stand. On top of this, some trees may die from the disease.

Initialization: 1 acre of loblolly pine will be looked at, starting with 600 trees, which has a spacing of 8 x 9 ft, and will get thinned on a 10-year rotation, starting at age 15. Every thinning will bring the BA down to 80 ft squared per acre. This pattern will be checked by comparing the number of trees present in the acre to the age of the tree, the older the tree, the fewer total trees. All trees will start at age 1 and grow until age 35. The outcome will be compared to a normal stand of 400-500 boards produced. Since BSNB reduces growth, the boards produced should be less than 400-500. 

Input data: The environment will remain constant and not consider temperature or rainfall.

Submodels: population size will decrease as the stand is thinned and dying trees are removed.
