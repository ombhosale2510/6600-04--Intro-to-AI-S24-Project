### Directory Contents
- cleaned/: This directory contains the cleaned dataset used for training and testing the models.
- dataset/: This directory holds the original raw dataset before preprocessing.

## Jupyter Notebooks
1. preprocessing.ipynb
    This notebook details the preprocessing steps applied to the raw MRI images, including resizing and cropping.
    
2. remove_duplicates.ipynb
    This notebook is used to identify and remove duplicate images from the dataset.
    
3. resnet.ipynb
    This notebook contains the implementation and training of a ResNet50 model for the MRI classification task.
    
4. densenet.ipynb
    This notebook contains the implementation and training of a DenseNet121 model for the MRI classification task.
    
5. GRU_and_LSTM_multi_class.ipynb
    This notebook includes the implementation of GRU and LSTM models for multi-class classification of MRI images.

The project implementation began with `preprocessing.ipynb`, where the raw MRI images were resized and cropped to 256x256 dimensions and saved to the `cleaned/` directory. Following this, `remove_duplicates.ipynb` was used to identify and remove duplicate images from the dataset. Once the dataset was prepared, `resnet.ipynb` was implemented to train and evaluate the ResNet50 model, followed by `densenet.ipynb` for the DenseNet121 model. Lastly, `GRU_and_LSTM_multi_class.ipynb` was developed to train and evaluate GRU and LSTM models for multi-class classification. Additionally, EfficientNet was implemented on Google Colab due to technical limitations, and the corresponding Colab notebook is provided here: https://drive.google.com/file/d/1qdNURatihf_mRYdHcPtvDsPFlU1UGCHs.