# DNN for bound-virtual classification
This repository contains the DNN model construction, training loop code and inference code. The code for the data generation is in `generate_dataset.ipynb`. It contains function that allows you to check the shape of cross section and the parameters used. 

Use the jupyter notebook `experiment.ipynb` to perform DNN model inferences on separable potential and nucleon-nucleon data in <a href=http://nn-online.org> NN-Online</a>. The pretrained models are saved in `generalization` folder. If you want to skip the generation of validation dataset, you may upload the separable validation dataset in `inference_data`. It is already in the `experiment.ipynb` code.  

If you wish to use this code in your work, please cite our papers:
<a href=https://journals.aps.org/prd/abstract/10.1103/PhysRevD.102.016024>PhysRevD.102.01602</a> and
<a href=https://link.springer.com/article/10.1007%2Fs00601-021-01642-z>Few-Body Syst 62, 52 (2021)</a>.
