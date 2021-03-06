# lbann_cosmogan

Repository with 
These are Generative Adversarial Neural Networks used on Cosmology data, built on LBANN.

The original code in keras is here: https://github.com/pzharrington/ExaGAN

An earlier version of the code in lbann is here: https://github.com/LLNL/lbann/tree/develop/applications/physics/cosmology/ExaGAN

Data: 
The original data can be extracted from https://portal.nersc.gov/project/m3363/
A subset can be accessed here : https://portal.nersc.gov/project/m3363/cosmoUniverse_2019_05_4parE/22309462/

- 0a_data_preprocessing:
Codes for obtaining slices from the original hdf5 files.
- 0b_view_data:
Codes to view sample images and explore normalization functions of input images.
- 1_train: 
Contains the scripts to train the model and batch scripts to run it.
- 2_ create_images: 
Contains the scripts to use the stored models and create new images. (Nothing in yet).
- 3_analysis:
Contains scripts that analyze the produced images.
