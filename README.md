# MyRep

Tasks done:
Create 3 separate '.csv'* files named 'detail.csv', 'detailVol.csv' and 'detailTemp.csv'.

Combine all the data in sheets named like "Detail_67_" only, among the two data files provided, and save into 'detail.csv'
Combine all the data in sheets named like "DetailVol_67_" only, among the two data files provided, and save into 'detailVol.csv'
Combine all the data in sheets named like "DetailTemp_67_" only, among the two data files provided, and save into 'detailTemp.csv' Provide attention to the column 'Record Index' which provided index values to avoid mismatching the rows while combining multiple files.
Apply down-sampling method to reduce the sampling rate to 1 sample/minute. Appy the same to 'detail.csv', 'detailVol.csv' and 'detailTemp.csv' and creating 3 files named 'detailDownsampled.csv', 'detailVolDownsampled.csv' and 'detailTempDownsampled.csv'

Apply low pass filter technique for noise removal on the data set for 'detailVolDownsampled.csv' and show the distribution of the dataset through visualization, also provide explanation of the same.

Run profile for all the functions; use cProfile for Python for profiling of individual functions.

Run unit test on each function,i.e., write test cases for each function. Use unittest for the same.

Try to maintain Coding Style Guide PEP-8, and use pylint or flake8 to check the code for PEP-8 violations.
