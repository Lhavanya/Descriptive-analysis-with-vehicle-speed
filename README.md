DESCRIPTIVE ANALYSIS WITH VEHICLE SPEED

TOOL USED: Jupyter notebook

DATA SET DESCRIPTION:

•	Dataset consists of 11 columns and 343628 rows.

PRODECURE:
1.	Import numpy, pandas, matplotlib.plot and seaborn. Numpy is used for mathematical and logical operation. Pandas is used for importing and analysing. Matplotlib.plot is used for creating graphs and plotting. Seaborn is used for Statistical visualization. 
2.	To find the strength of the relationship between variables, correlation if calculated.
3.	The asymmetrical statistical distribution among the variables is calculated with skewness.
4.	describe() function is used to describe the basic statistical details such as percentile, mean, standard deviation and so on.
5.	Pairplot is used to visualize the pair wise relationship in the dataset.
6.	norm() is the vector normalization of the data set. Normalization is an important technique to reduce the redundancy in the dataset.
7.	Data set is converted to data frame for further analysis.
8.	Speed range is found.
9.	Drivers who have not violated the speed and the time for the same is found(for the drivers with the driver ID).
10.	Drivers who have not violated the speed in a highway is found(for the drivers with the driver ID).
11.	Next analysis is to detect the outliers in the data with the speed of the driver .Drivers who have violated the speed is found(for the drivers with driver ID).Drivers who have violated the speed in a highway is found(for the drivers with the driver ID). Box plot is used to describe the outliers for visual representation.
12.	The count of speed violation is also found to know how many drivers have violated and put in a data frame. The driver ID and the number of violations for the same is plotted in bar graph
13.	The drivers who have not violated and the count for the same is calculated to find the best driver.
14.	The driver ID’s are grouped and their count of non violation is tabulated as data frame.The driver ID and their non violations are plotted in a form of bar graph.
15.	The speed in the highway is stored in a variable and the maximum speed in the highway for each driver is found.
16.	The count in each functional class is found with count plot.

