# ECE2112-PA-3

**Made by Siean Ivar B. Corporal | 2ECE-A**

**Objectives**
  1. load a CSV dataset into a Pandas DataFrame;
  2. select rows and columns using positional and label-based indexing;
  3. filter records using conditions on a DataFrame column; and
  4. extract a well-defined subset of data without changing the source data.

# **POSITIONAL AND LABEL-BASED SLICING**
  In this part of the experiment, a csv file containing a dataframe was stored in a variable named `cars` where the shape and the column names of 
  the dataframe were displayed. Specific rows and columns were also displayed using the following syntax:
  
  1. `cars.shape` - This syntax was used to display the shape of the dataframe showing the number rows and columns.
  2. `cars.columns.tolist()` - This syntax was used to display the column names itself and is outputted in a form of a horizontal list.
  3. `cars.iloc` - This syntax was used to store specific rows in a variable named cars_6_to_10.
  4. `cars_6_to_10.loc` - This syntax was used to display the data stored on specific columns in cars_6_to_10.

# **MODEL LOOKUP**
  In this part of the experiment, boolean indexing was used to locate specific rows from the dataframe.
  The following syntax were used:

  1. `cars['Model']` - This syntax was used to locate specific rows under the column name "Model" in the dataframe. The boolean expression `==` was
  also used to find a specific model name.
  2. `display()` - This syntax was used to display the data inside a variable. This was used instead of print() because it outputted the dataframe itself
     along with the row and column names.
  3. `pontiac.loc` - This syntax was used to only display the data under specific columns in the variable pontiac.

# **MULTI-MODEL SUBSETTING**
  In this part of the experiment, specific models were displayed using boolean indexing.
  The following syntax were used:

  1. `cars['Model']` - This syntax was used to locate specific rows under the column name "Model" in the dataframe. The boolean expression `|` and `==` was
  also used to find a specific model name. The data collected from this syntax was stored under the variable name selected_cars.
  2. `selected_cars.loc` - This syntax was used to store specific rows in the variable named selected_cars.
  3. `selected_cars.shape` - This syntax was used to display the shape of the dataframe showing the number rows and columns.
  4. `display()` - This syntax was used to display the data inside a variable. This was used instead of print() because it outputted the dataframe itself
     along with the row and column names.
