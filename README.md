
![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

The goal of this project is to combine data wrangling, cleaning, and manipulation with Pandas.


# Project: Data Cleaning and Manipulation with Pandas

## Shark Attacks Files

### Goal:

In this project our primary goal was clean the dataset provided by using pandas. 

### Procedure:

In short, we proceed as follows:

. Data exploration: Here we have an insight of the data set by looking the data types in question, which is the information valuable in this context, etc.There are many ```NaN``` values in critical fields, such as the Shark species. Our focus is try to maintain this valuable information.

. Delete duplicated columns and filling ```NaN``` values plan:

* The unnamed columns 22 and 23 should be dropped, because are almost entirely null.

* Due to the relevance of the ```"Species"``` column in the data set, we cannot drop this column, even when the percentage of ```NaN```'s there is near to 50%.

* The column ```"Time"``` and ```"Year"``` seems to be irrelevant. However we will explore it further.

* The columns ```"Country"```, ```"Area"``` and ```"Location"``` are related, so it might be possible to infer the missing values one from the others.

* The column ```"Age"``` maybe can be infered from anothers after further inspection and it seems to be relevant also in our context so we decided not to drop it.

. Cleaning and parsing the column ```"Date"```.
. Droping irrelevant rows based on ```NaN```'s counting by columns
. Droping the column ```"Case Number"```, ```"Year"``` and ```"original order"```.
. Filling values in ```"Injury"``` and ```"Fatal(Y/N)"``` 
. Exporting data frame as .csv file 


