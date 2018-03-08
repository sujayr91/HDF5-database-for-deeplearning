# Creating HDF5 database [Data container for deep learning training/test data]

* Intro:

    * When dealing with large datasamples, loading data from imagefile/excel file in to numpy makes training slow.
    * This tutorial creates a hdf5 database from the samples. The hdf5 contains train , test datasets.
    * To know about how to use the hdf5 file for the training data loader, check the repo https://github.com/sujayr91/TimeSeries_Classification_LSTM

* Requirements:
    * Install h5py package: pip install h5py
    * python 3

* Usage:

    * Organize data in to folders for each label[this assumes data samples are in csv, for image data change file load ex: PIL.Image]
    * Use createhdf5database.py for creating hdf5 datasets. 

