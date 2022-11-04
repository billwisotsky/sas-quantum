# SAS Cluster Analysis and Quantum Variational Classifier
This Jupyter Notebook integrates SAS with Pennylane from Xanadu Quantum.
The Quantum Variational Classifier was taken from the PennyLane demo
website:
https://pennylane.ai/qml/demos/tutorial_variational_classifier.html

## Code Explanation
The 1st part imports and scaled CSV of the common iris dataset that is found
built into sashelp.class. A scaled version was used so it could be embedded
into quantum states without too much manipulation. Then a bunch of SASPY
classes are used to examine and graph the imported data. Only the variables
SepalLength and SepalWidth were used as well as only Setosa and Versicolor
species.

***** The CSV that is located located here needs to be local to the
      SAS installation whether its is local or on a server.

The 2nd part runs a cluster analysis in SAS, formats the output data and
then graphs the data show correct incorrect classifications

The 3rd part uploads the data into python and then runs PennyLane machine
learning algorithms for quantum variational classifier. It then graphs the
results

The final part downloads the result arrays from PennyLane back into SAS,
performs relevant data manipulation and then graphs the results in SAS.

## Some Important Links
If you used anaconda to create the environments as mentioned above, it is note
necessary to redo this step as mentioned in vendor specific documentations.
### saspy:
https://sassoftware.github.io/saspy/
### Xanadu (PennyLane) & the quantum Device and machine learning addins
https://pennylane.ai/install.html
