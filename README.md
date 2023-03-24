# **project-code-louisville**

##  **About**

This is the final project for the Code Louisville Data Analytics level 1 eduction program.  The goal of it is to use all of the python features that were taught during the course. It will be designed to display the basics of performing a data analysis at a foundational level. The topic is popular guitar makes and models. After a dataframe is imported into the machine the data analysis process will begin.

Git Bash was used to load the repo into Visual Studio Code, set up a virtual environment, and install the requirements.txt for the data analysis.


## **Features**

### **Data Exploration**

-  Document Dataset found at https://www.kaggle.com/datasets/arslankas/guitars
-  Created .ipynb file
-  Preview the dataset with Pandas
    1. list columns
    2. get the number of rows
    3. check the data types for each column
    4. see if any records are missing
    5. preview the dataframe

    


### **Develop Questions**

-  Which manufacturer in the dataset makes the most expensive guitars and which manufacturer makes the least expensive guitars? 

 The most expensive manufacturer is Gibson and the least expensive is Harley Benton in this dataset


-  What is the average price of guitars for the dataset?  

$1738,34


### **Cleaning Data**

-  Created clean.ipynb for cleaning the dataset 
-  Removed the title column from the dataframe using Pandas.
-  No columns need to be corrected

### **Analyze the Data**

-  Created an analyze.ipynb file
-  Convert object data to int32 in the price column with Pandas.
-  Sort the price column in descending order
-  Sort the manufacturer column into groups
-  Display just the head and tail of the dataframe
-  Use Pandas to calculate the average price of the dataframe

### **Plotting the Data**

-  Created a plot.ipynb file
-  Created a bar graph that tells us who has the most/least expensive guitar prices using Pandas and Numpy.
-  Another bar graph that shows the average price using Pandas and Numpy


### **Run the Program**

1. Fork the repository from GitHub
2. Clone the repository
3. Create a virtual environment (python3 -m venv venv)
4. Open the virtual environment ( source venv/Scripts/activate - using gitbash with Windows)
5. Install libraries (pip install -r requirements.txt)
6. Go into the .ipynb that you want to analyze and run all.
7. If any changes need to be made use git add file
8. git commit -m comment
9. git push





