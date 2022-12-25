# Pre-installation
Due to the dataset being extermly large, you need to manually download the dataset from: https://www.kaggle.com/datasets/kazanova/sentiment140?resource=download

When the dataset is downloaded, make sure to put it in a folder called "dataset" in the same folder where you put the jupyter notebook file.

# Installation

## Option 1
1. Make sure you have a virtual environment, to create a new virtual environment on Linux(Ubuntu) type the following:
```
python3 -m venv venv
source venv/bin/activate
```
2. When you have set up your venv, install all packages by wrting pip install -r requierments.txt

3. Done, you should now be able to run the files

## Option 2
To install the required libraries, follow these steps:

1. Install the scikit-learn library by running the following command:
```py
pip install -U scikit-learn
```

2. Install the scipy library by running the following command:
```py
pip install scipy
```

3. Install the matplotlib library by running the following command:
```py
pip install matplotlib
```

4. Install the numpy library by running the following command:
```py
pip install numpy
```

5. Install the pandas library by running the following command:
```
pip install pandas
```

6. Install the datacleaning library by running the following command:
```py
pip install datacleaning
```

7. Make sure you have all files within the same folder, since they are being imported to main. Note that the dataset does not need to be in the same folder, leave it in the directory "dataset".
Once all of the required libraries have been installed, you should be able to run the code that imports them.