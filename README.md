# SAS & Quantum Computing Integration
This repository contains Jupyter notebooks and projects consisting of using
various Quantum Computing technologies and integrating them with SAS. Most of
the project consist of hybrid approaches to Quantum Machine Learning using SAS
various Quantum vendors such as DWave, Xanadu and IBM.

Most examples consist of using SAS for either/both initial data manipulations
and visualization of quantum results.

It is recommended that Anaconda is used to create segregated environments for
each quantum vendor, for example create an environment for D-Wave and a
separate one for each vendor (e.g. conda create -n D-Wave python=3.8). After
each environment is created it is necessary to activate it
(e.g. conda activate D-Wave). Once the environment is activated it is
necessary to install and configure each quantum vendor's programming SDK
following the instructions on each vendors website. In addition, it is
necessary to install various helper applications each vendor needs such as
pandas, numpy, matplotlib, itertools, etc. It is also necessary to install and
configure saspy (https://sassoftware.github.io/saspy/). It will need to be
configured to a local installation of SAS or a sever installation following the
steps in the documentation. *** It is import to note that some examples use SAS
to read in data. The datafile that is being imported needs to be located
locally to the SAS installation and the path modified as needed.

##Some Important Links
If you used anaconda to create the environments as mentioned above, it is note
necessary to redo this step as mentioned in vendor specific documentations.
###saspy:
https://sassoftware.github.io/saspy/
###DWave Ocean SDK:
https://docs.ocean.dwavesys.com/en/stable/getting_started.html
###Xanadu (PennyLane) & the quantum Device and machine learning addins
https://pennylane.ai/install.html
###IBM Qiskit:
https://qiskit.org/documentation/getting_started.html
