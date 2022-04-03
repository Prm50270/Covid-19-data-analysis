# Covid-19-data-analysis
Download the zip from githhub and unzip it in any directory.

Python packages required to successfully run assign1.sh:

-json: Used for converting json to dictionary and vice versa
-csv: Used for writing in csv file
-pandas: Used for handling dataset
-numpy: Used to perform vaious mathematical operation in array
-scipy.signal.find_peaks: Used for finding the peaks
-datetime : Used for generating dates to traverse
-Openpyxl: Used for reading excel
-Operator: Used to add the list
-math: Used for mathematical operation
-collections : Used for maintaining dictionaries
 
Some info regarding assumptions:

For Question1 I named the .sh file as q1.sh.
In Question4 I used the active cases for peak calculation and -1 for denoting the peak not found. 
In Question3 and 4 I discarded all the entries which are ambigious like unknown,other state except for those state which has only entry mentioned as State_Unknown
If values of cases,active cases,population left is negative in that case I assigned them as 0.
In Question5 I started calculation from 17 Jan 2021.
In Question9 I wrote weekly rate of vaccination in csv file.
In case of ratio calculation I used NA when there is division by zero.
In Question3 and 4 I started the calculation from 26 April 2020.
For the overlapping weeks calculation I left the last week of thursday to saturday so total weeks are 135.

For running the assign1.sh:

Make working directory as folder - '21111049-assign1'
Use command -> sh assign1.sh to completely run assignment1

Total execution time:2 min 38 sec
