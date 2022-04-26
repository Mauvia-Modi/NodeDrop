# NodeDrop
The public repo for NodeDrop, my final project of Trustworthy Machine Learning at RPI.

There are only two jupyter notebooks. 

The target model notebook has code to prepare the victim model, trained with NodeDrop. Then, the predictions of the model are saved for both it's training and test sets.
The shadow model notebook has code that trains the shadow and attack model, and then simulates a complete attack on the victim model.

The degree of each individual node was determined using a simple piece of code not included here. The degree mapping can be found in cora/deg_labelled.csv.

The CSVs found hold the predictions of the shadow model and victim model, and comments in the code explain their genesis and purpose.

The PDF holds the slide deck with a complete presentation of results.
