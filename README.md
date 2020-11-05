# DNN for bound-virtual classification
This repository contains the DNN model construction, training loop code and inference code. The code for the data generation is in `generate_dataset`. It contains function that allows you to check the shape of cross section and the parameters used.

Use the jupyter notebook `experiment` to perform DNN model inferences on separable potential and nucleon-nucleon data in <a href=http://nn-online.org> NN-Online</a>. The pretrained models are saved in `generalization` folder. If you want to skip the generation of validation dataset, you may upload the `.pkl` data in the repository.

If you wish to use this code in your work, please cite our paper:
<a href=https://journals.aps.org/prd/abstract/10.1103/PhysRevD.102.016024>PhysRevD.102.01602</a>.
