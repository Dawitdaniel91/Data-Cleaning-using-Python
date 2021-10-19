# Data-Cleaning-using-Python
The Project is handling the missing value using Python. The first thing is load the libraries and the dataset.Then, get an idea of what's going on with the data. In this case, I'm looking to see if I see any missing values, which will be reprsented with NaN or None.It helps me to identify the dataset within NaN or none value.Yes, it looks like missing value in the dataset below the table

### Table 1

![image](https://user-images.githubusercontent.com/80365882/137971507-889e2eaa-6906-4abe-ac59-73c2ab19060c.png)

### Step 1 git the number of missing value

to get the missing value, use the code isnull().sum()

### Table 2

![image](https://user-images.githubusercontent.com/80365882/137971566-46949cc8-5bcd-4cfc-a00b-fa12b6c49d43.png)

it looks like a lot of missing value in the dataset. So, we have to see how much percentage of the missing value in the dataset. Becouse it might be helpful to see what percentage of the values in our dataset were missing to give us a better sense of the scale of the problem.

### Step 2 how many percent is the missing value

### Table 3

![image](https://user-images.githubusercontent.com/80365882/137971618-1480a6e6-57bb-4e60-b17b-7c169d4b007b.png)


From the above data, one fourth(1/4) of the dataset is empity.The above information help us to look at some of the columns with missing values and try to figure out what might be going on with them.

### Step 3 Number of missing value in the first 10th columens

This steps helps us how the missing value affect our data analysis. we have to know the missing value is becuase of it wasn't recorded or becuase it dosen't exist? if the value is doesn't exist it is better to record as Nan otherwise if it is missed value becouse of not recorded we have to geuss based on the values in that column and row.

### Step 4 remove all the rows that contain a missing value

### Table 4

![image](https://user-images.githubusercontent.com/80365882/137971684-87b75ff9-7e32-4a11-a661-d1119acbd893.png)


### Step 5 Check how much data we lose

### Table 5

![image](https://user-images.githubusercontent.com/80365882/137971916-468fe7d1-c9eb-40d5-95af-e1dbc20c9683.png)





