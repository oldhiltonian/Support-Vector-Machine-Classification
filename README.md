# Support Vector Machine Classification


## NON-TECHNICAL EXPLANATION
This is a project to demonstrate the use of Support Vector Machines in the prediction of mouse behaviour and mouse genotype based on protein expression levels. 


## DATA & METHODOLOGY
The dataset can be found from Kaggle at [this link](https://www.kaggle.com/datasets/ruslankl/mice-protein-expression).

We import the dataset containing data of mouse protein expression levels. These are numeric (float) variables that contain protein concentrations in the mouse cells. There are three additional binary categorical variables:

    Genotype: Downs Syndrome vs control
    Treatment: Memantine vs Saline
    Behaviour: Stimulated vs Non-Stimulated

There are numerous questions that can be investigated using this dataset.

    Can protein expression be used as predictors for genotype?
    Can protein expression be used as predictors for behaviour?
    Can genotype be used as a proxy for behaviour?
    Can protein expression be used to predict treatment? (The answer should be NO as the mice should have been randomly assigned to treatment groups!)

Once the above 4 Cases have been briefly explored, Case 1 will be revisited and the hyperparameters optimized.

## MODEL 
There are numerous things to consuider in model selection. The first is the fact that this is a classification problem, so our models must be chosen accordingly. The inputs to the model are all numeric (float) values. The key factor in model choice for this application is the high dimensionality of the dataset. There are roughly 70 proteins that are present in the dataset. I believe that the ideal model choice for this application is the Support Vector MAchine, due to their favorable performance in high dimensions.

## HYPERPARAMETER OPTIMSATION
The hyperparameters chosen for optimization are the kernel type and the level of regularization taking place in the model.

## RESULTS

1. Protein expression is a strong predictor of genotype.
2. Protein expression is a strong predictor of mouse behaviour.
3. There is a weak relationship between mouse genotype and mouse behaviour.
4. Protein expression is a strong predictor of treatment type received by the mouse. This is not a good sign as it can indicate that the random assignment of the mice to treatment groups was not sufficient and may in fact have introduced massive bias into the study.

5. Hyperparameter optimization indicated that the linear kernel with a regularization parameter of approximately 2 was the best performing model.



