### NEURON scripts for model

This folder contains files from the original model scripts [ModelDB:124291](https://senselab.med.yale.edu/modeldb/showModel.cshtml?model=124291) and additional tester scripts (in order to create a .mep file, which against LEMS/NeuroML2 implementation could be tested).

To run the scripts, [install NEURON](https://www.neuron.yale.edu/neuron/download) and run:

    git clone https://github.com/OpenSourceBrain/Ferrante2009-DentateGyrusGranuleCell.git  # clone git repository
    cd Ferrante2009-DentateGyrusGranuleCell/NEURON
    nrnivmodl  # compile .mod files
    nrngui test_granulecell.hoc  # runs a simulation (single cell, current clamp) and saves data into granulecell.dat
