# README.md
This repository will contain the python file whereby there will be further descriptions explanatory.

The initial step here is to import the respective libraries in the jupyter notebook with the assistance of python language.

Now once the libraries are imported, the next step is to let the use the df function to read the csv format file “Salaries.csv” into the python environment. Through this df function, the basic functions of selecting, removing, adding, & altering the name of rows/column is accessible.

To display the total number of records of this selected data frame, the df.shape functions is used to display the total set of a frame records and similarly another function df.size which shows us the total size of the data frame in terms of total elements.

In addition to this, the code df.columns is used to display the respective column names of the selective data frame and df.dtypes for showing the distinctive types of columns in the data frame. They are classified into types of object or int64 based on the data stored in that particular column.

In the next, df.phd.dtype is used to check a particular type of column from the total set of columns in the data frame. This is used to identify column type of the selective column only as for example here it was “phd”.

Next, to make sure that the data is formatted in terms of data cleaning with .dtype() and .astype() which are used for checking & changing the data type.

The first step, df function with the read_csv code is used to read the Auto.csv file. In the next step, df.dtypes is used to list all the types of the data for every column from the Auto.csv dataframe. However, there will be error shown as the information may not contain the correct or same type of data when the df.info code is runned.

Therefore, converting the datatypes to the proper format will solve the error and this can be done with the help of astype() method whereby it can be checked with .dtype(). 

As per the dataset, bore & stroke are the ones in the different format which are converted from the object to float & int as they are numerical value in the original data set. Once this process is done, we can check the data type by df.dtypes and make sure that those variables are converted to proper format of float & int.
