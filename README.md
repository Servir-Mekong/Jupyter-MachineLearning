# Jupyter-MacineLearning
Generic ML library

**1: Download and install ANACONDA [(Select 3.5 python and 64 bit for ML installation)](https://www.anaconda.com/download/#windows)**

NOTE: DO NOT CHECK ANYHTING UNDER THE ADVANCED OPTIONS TAB DURING INSTALL (This will destroy your ArcGIS Installation)

**2: Add Community package management system**

Start "Anaconda Prompt" with admin privileges
```
conda config --prepend channels conda-forge
```
//START HERE IF YOU HAVE ANACONDA INSTALLED

**3: Create Tensorflow environment**
```
conda create -n tfe python=3.5
conda activate tfe
conda install jupyter
conda install pandas
conda install matplotlib
conda install numpy
conda install scikit-learn
```

**4. Install [Tesorflow](https://www.tensorflow.org/)**
```
conda install tensorflow
```

**5. Install [Keras](https://keras.io/)**
```
conda install keras
````

**6: Link a IPython kernel to the gee environment**
```
python -m ipykernel install --name tfe --display-name "Python (tensorflow)"
```
Deactivate gee environment
```
conda deactivate
```

**7: Start Jupyter environment by running the command**

change directory to your notebook folder location
```
jupyter lab
```