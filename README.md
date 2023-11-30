# Complex_model
Purpose: How does the level of brown spot needle blight infection affect the growth rate of loblolly pine trees? How much growth would be lost in a tree that is severely diseased vs a tree with no disease?

Entities, state variables, and scales: This model has one entity, tress. State variables are the amount of disease present on the tree- none, low, medium, high. This pattern will be created by looking at my tree cores I have measured and an equation will be made to create a general growth curve. Overall, the more diseased the tree, less growth should occur. 

Process overview: The processes of the model will include how much disease is present on the tree, total radial growth, total height growth, and total disease. One section of code will have disease spreading and the other will have no disease spread and only account for natural problems outside of this fungus.

Design concepts: I want to address how the disease affects loblolly pine tree growth. A model will be created to see how growth changes within each disease level. Each tree will get randomly assigned diseased and can only get more diseased, no recovery since that is how it appears to be in nature. In nature, there is a 1-3% rate of natural death within a stand, which will not be included in this stand. All 600 trees will survive the whole 35 years. 

Initialization: 1 acre of loblolly pine will be looked at, starting with 600 trees. Thinnings occur in regular stands but will not be taken into account in this model. All trees will start at age 1 and grow until age 35 since that is a typical rotation length. The outcome will be compared to a normal stand of around 600 trees harvested. Since BSNB reduces growth, the boards produced should be less. 

Input data: The environment will remain constant and not consider temperature or rainfall.

Submodels: None
