Data Acquisition and Data Wrangling on Dataset1 Dataset2
* Data Acquisition:
  . Download the provided datasets (dataset1 and dataset2)
  . load these datasets into your environment using pandas

* Data Wrangling Steps:
  . You will need to merge dataset1 and dataset2. depending on the structure of thre datasets, this can be done using methods such as pd.merge() or pd.concat()
  . use pd.unique() to identify unique values in relevant columns, ensuring there are no data duplications or inconsistencies.
  . identify and remove columns that are not necessary for further analysis using df.drop().
  . use df.shape to understand the size of each dataset before and after merging.
  . use df.dtypes to verify the types of data in each column.
  . look for missing values using df.isnull().sum(). decide whether to fill missing values (df.fillna())
  . Validate the correctness of the data.
  . After merging, calculate central tendencies such as mean, median,mode, etc for columns like tem, humidity, windspeed,etc

      * Concatenate Datasets: combine the merged data from task 1 with Dataset3 using pd.concat().
      * Handle missing values: check for the missing values in the combined dataset using.

  * IMPORTANT LIBRARIES TO USE:
    . Pandas: for data manipulation,merging, concatenation, checkin for missing values, etc.
    . NumPy: for handling arrays and performing calculations(e.g., central tendency)
