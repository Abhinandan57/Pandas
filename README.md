# Pandas
- NumPy is great when it comes to mathematical computing. But it is still a low level tool when it comes to data munging. This is where Pandas prove useful as it uses NumPy and adds several more functionalities on top of it.
- Pandas is built on top of NumPy. Thus it is fast and efficient when it comes to data wrangling.
- Pandas includes features like intrinsic data alignment and offers data operation functions such as merge, groupby, join methods and so on, that makes it efficient for data wrangling and manipulation. It also offers functions for handling missing data values and is a great data standardization tool.  
### Pandas Data structures:  
- Data structures are the basic building blocks that helps data scientists wrangle and analyze data. The 4 main libraries of Pandas data structure are:  
__(1) Series:__ One-dimensional array-like structure used to represent a dataset and can be visualized as a single row dataset. Supports multiple data types such as integer, string and float.  
__(2) DataFrame:__ Two-dimensional labeled array and can be visualized as a typical spreadsheet structure or a SQL database table with rows and columns. It also supports multiple data types such as integer, string, float etc and can be formed in many ways. A Series can be an input to a Data Frame. Another Data Frame can also be an input to it.  
__(3) Panel:__ Three-dimensional labeled array and supports multiple data types. It is mainly used to represent and wrangle three-dimensional datasets and can be visualized as x,y and z axis. Items -> axis 0, Major axis -> rows, Minor axis -> columns  
__(4) Panel 4D:__ Four-dimensional array and not very widely used. It is in experimental phase. 
- Series and DataFrame are the two main data structures which Data Scientists use to tackle real world problems.

# Series:
- Series is a one-dimensional array-like object containing data and labels(or index).
- __Data Types:__ Integer, String, Python Object, Floating Point
- Series can be created in multiple ways with the help of data elements which, if defined properly, act as data input to create a series. Therefore, __data input__ can be an ndarray, dict, scalar, list.
- An ndarray can be used as an input to create Pandas series. The use of ndarry is recommended wherever the dataset is number-centric and requires complex numerical computing.
- A Pandas series can also be created using dictionary and it is very efficient when it comes to indexing or reindexing a dataset for data wrangling purposes. dict works in a key-value fashion, so use it whenever the dataset is structured as key-value pair.
- Scalar data is another way to create Series. It is a stand-alone quantity and works with both vector and scalar datasets that can be used accordingly.
- List is another basic Python data structure which can act as an input to create Pandas series. List can hold a range of values of multiple data types. So if a dataset appears as a list, use list as input to create series.  
__Steps to create a series:__  
- Import Pandas as it is the main library: __import pandas as pd__
- When dealing with ndarray or other NumPy functions, import NumPy: __import numpy as np__
- Apply the syntax and pass the data elements as arguments
__Syntax to create series:__ S = pd.Series(data, index = [index])

# DataFrame:
- Data frame is a way to store data in rectangular grids that can easily be overviewed. Each row of these grids corresponds to measurements or values of an instance, while each column is a vector containing data for a specific variable. DataFrame is a two-dimensional labeled data structure with columns of potentially different data types.
- __Data Types:__ Integer, String, Python Object, Floating point
- __Data Inputs:__ ndarray, dict, list, Series, DataFrame
