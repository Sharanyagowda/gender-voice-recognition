# Gender voice recognition
Even if gender recognition by voice is a trivial task for humans, it's not for machines.
Through this project, I'll propose a method to classify male/female voices through DSP and basic ML techniques.

Check [README.ipynb](README.ipynb) for more informations.

## Some considerations about the project
This project was my first ML project. It was done for a university course and it's not production ready.

If you are going to use it, keep in mind that:
* some samples could be too much correlated (more than one recording was collected from the same person);
* it needs more data;
* the prediction model overfits due to the fact that I didn't choose the hyperparameter trough a separated validation dataset.
