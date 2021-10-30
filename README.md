# Data-Cleaning-using-Python
TThe Project is handling the missing value using Python. The first thing is to load the libraries and the dataset. Then, get an idea of what's going on with the data. In this case, I'm looking to see if I see any missing values, which will be represented with Nan or None. It helps me to identify the dataset within Nan or none value. Yes, it looks like a missing value in the dataset below the table

Data Sources: https://www.kaggle.com/aparnashastry/building-permit-applications-data

### Table 1

![image](https://user-images.githubusercontent.com/80365882/137971507-889e2eaa-6906-4abe-ac59-73c2ab19060c.png)

### Step 1 get the number of missing value

to get the missing value, use the code isnull().sum()


![image](https://user-images.githubusercontent.com/80365882/137971566-46949cc8-5bcd-4cfc-a00b-fa12b6c49d43.png)

it looks like a lot of missing values in the dataset. So, we must see how much percentage of the missing value is in the dataset. Because it might be helpful to see what percentage of the values in our dataset were missing to give us a better sense of the scale of the problem.

### Step 2 how many percent is the missing value

### Table 2

![image](https://user-images.githubusercontent.com/80365882/137971618-1480a6e6-57bb-4e60-b17b-7c169d4b007b.png)


From the above data, one-fourth (1/4) of the dataset is empty. The above information helps us to look at some of the columns with missing values and try to figure out what might be going on with them.

### Step 3 Number of missing value in the first 10th columens

This step helps us how the missing value affects our data analysis. we must know the missing value is because it wasn't recorded or because it doesn’t exist? if the value is don’t exist it is better to record it as Nan otherwise if it is missed value because of not recorded we have to guess based on the values in that column and row.

### Step 4 remove all the rows that contain a missing value

### Table 3: Clean data

![image](https://user-images.githubusercontent.com/80365882/137971684-87b75ff9-7e32-4a11-a661-d1119acbd893.png)


### Step 5 Check how much data we lose

### Table 4

![image](https://user-images.githubusercontent.com/80365882/137971916-468fe7d1-c9eb-40d5-95af-e1dbc20c9683.png)


# Clean dataset

### Table 5

![image](https://user-images.githubusercontent.com/80365882/137972105-a84358e1-2e68-4f2b-b8bb-e6c0b873ab8c.png)

# Printing Percentage of Orginal Dataset and Clean dataset

### Table 6

![image](https://user-images.githubusercontent.com/80365882/137972310-072bc273-5613-47bc-baa4-e6d14d460ae4.png)




