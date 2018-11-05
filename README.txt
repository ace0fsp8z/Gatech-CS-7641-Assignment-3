Supervised Learning - CS 7641 - HW 3 Readme

Code and necessary data can be found here : 

1. Please make sure you get the files in my github link : https://github.com/bryanmarthin/Gatech-CS-7641-Assignment-3
	- there is a zip file called bmarthin3.zip that contains the files mentioned in number 2 below
	
2. The files you get should contain :
	1. Readme.txt
	2. 2 Python codes : 1 code for white wine data and 1 code for abalone data
		- BM_UnSupervisedLearning_abalone.py
		- BM_UnSupervisedLearning_white_wine_quality.py
	3. various chart in PNG format generated from the code for reference in 2 folders : white wine folder and abalone folder
	4. 2 CSV data sets : abalone data and white wine quality data --> DO NOT rename the files
		- abalone.data.csv
		- winequality-white.csv
	5. Pdf of analysis with name bmarthin3-analysis.pdf

3. Before running the code, make sure you have this python package installed in your PC
	1. pandas
	2. numpy
	3. matplotlib
	4. os
	5. sklearn
	6. datetime
	7. collections
	
4. Upon opening each python code, after importing all the packages, you have to change the variable 'mydir'

5. the variable 'mydir' should be changed to a directory where you extracted the package, or a directory where you store the python codes and the datasets csv.

6. upon running the code, it will create multiple PNGs for the data occurence char

7. each metric in my analysis could be found in the graph as i am using the graph as the core of my analysis. 
	- the data source of the graph comes from a dictionary that is filled after each section iteration

For any questions, feel free to send your email to : bmarthin@gatech.edu

Data Source :
https://archive.ics.uci.edu/ml/datasets/wine+quality
https://archive.ics.uci.edu/ml/datasets/Abalone

Code Reference :
https://stackoverflow.com/questions/52467098/masking-only-a-certain-range-of-indices-in-numpy
https://stackoverflow.com/questions/3594514/how-to-find-most-common-elements-of-a-list
