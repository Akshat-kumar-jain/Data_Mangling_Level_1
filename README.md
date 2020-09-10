# Data_Mangling_Level_1

## **Essentials of Data Science using Julia**
### Mini Projects cum Periodic Assessments
###       (Data Mangling Level I)

Problem Statements:

### **1. Play with Titanic dataset, and Perform following**

a. Load Titanic Dataset into Julia DataFrame using CSV package.

b. Explore and demonstrate , Size, Type of Each Col, describe it, check
missing and null values.

c. Create a separate DataFrame for categorical features(other than
numeric features).

d. Sort DataFrame according to Names.

e. Analysis of survived columns according to category(survived, died).

f. Analysis of Pclass columns according to category(first,
second,third)class.

g. Analysis of sex column according to category(male, female)- result
should be same as above.

### **2. Create the following given DataFrame, and perform below given operations.**

a. Some values in the the FlightNumber column are missing. These
numbers are meant to increase by 10 with each row so 10055 and
10075 need to be put in place. Fill in these missing numbers and make
the column an integer column (instead of a float column).

b. The From_To column would be better as two separate columns! Split
each string on the underscore delimiter _ to give a new temporary
DataFrame with the correct values. Assign the correct column names
to this temporary DataFrame.

c. Notice how the capitalisation of the city names is all mixed up in this
temporary DataFrame. Standardise the strings so that only the first
letter is uppercase (e.g. "londON" should become "London".)

d. Delete the From_To column from df and attach the temporary
DataFrame from the previous questions.

e. In the RecentDelays column, the values have been entered into the
DataFrame as a list. We would like each first value in its own column,
each second value in its own column, and so on. If there isn't an Nth
value, the value should be NaN.

