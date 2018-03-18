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
conda install panda
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
