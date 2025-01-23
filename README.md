# This code belongs to the paper "An Ensemble Framework for Text Classification"
This code has been created for running the experiments for the paper "An Ensemble Framework for Text Classification". Specifically, the repository contains two main folders. The first folder is named "experiments" and contains the experiments made in the CLEFIP-0.54M, WIPO-alpha, USPTO-2M, WoS and EURLEX57K. The second folder is named "datasets" and provides links and other details for the datasets. 

Please cite our work as follows:

@inproceedings{kamateri2025ensembleframework,
      title={An Ensemble Framework for Text Classification}, 
      author={Eleni Kamateri and Michail Salampasis},
      year={2025},
      booktitle={Information 2025, 16},
}

**OR**

Citation: Kamateri, E.; Salampasis, M. An Ensemble Framework for Text Classification. Information 2025, 16, x. https://doi.org/10.3390/xxxxx

## Requiquirements
The python environment we used for running all jupyter notebooks and training the Bi-LSTM classifier is Python3. Although we provide the versions we usd for these experiments, newer versions of these programs can be used as well.

Python3 environment (Version 3.6.13):

    tensorflow = 1.11.0
    keras = 2.3.1
    pandas = 1.1.5
    numpy = 1.19.2
    scikit-learn = 0.24.2
    regex = 2021.8.3
    ntlk = 3.6.5
