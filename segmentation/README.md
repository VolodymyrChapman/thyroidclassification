## Initiate Python (3.7) environment needed for the scripts in the segmentation folder
### Tested on Ubuntu 20.04 (11/02/2022)
### From yml file in this directory:
    
    conda env create -f environment.yml

### Using commands:

    conda create --name ttc_segmentation python=3.7
    conda activate ttc_segmentation
    conda install pytorch opencv pillow numpy scikit-learn openpyxl pytables xgboost seaborn
    conda install -c conda-forge pytorch-lightning albumentations torchvision skrebate mlxtend
    pip install test-tube
