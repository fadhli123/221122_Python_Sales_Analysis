# 221122_Python_Sales_Analysis

In this project I'll try to analysis one year sales data using python in jupyert notebook including the visualization.
You can also check my jupyter notebook file [221122_Sales_Analysis_Project - Jupyter Notebook.pdf](https://github.com/fadhli123/221122_Python_Sales_Analysis/files/10166368/221122_Sales_Analysis_Project.-.Jupyter.Notebook.pdf) in this repository because I also put comments and markdowns for each steps to help understad the process of this project.

## Importing Libraries and Merging Data

lets start by importing necessary libraries. After that, because the sales data is separated in each month, we need to merging this data into one single sheet.
![image](https://user-images.githubusercontent.com/110689945/205911263-d30f476e-a760-479f-a40a-23e1a42b2e45.png)
Now we have merged data in [all_data.csv](https://github.com/fadhli123/221122_Python_Sales_Analysis/files/10166396/all_data.csv). Lets continue to data cleaning!

## Data Cleaning

As you can see below when I check the merged data, this data is not perfectly merged as desired. There is some null rows and some column headers is interpreted as data.

![image](https://user-images.githubusercontent.com/110689945/205913547-4f16462f-af39-428e-8989-cebccb6f0e4a.png)

![image](https://user-images.githubusercontent.com/110689945/205913432-ca55d873-7082-4e3a-9594-0eb52c137707.png)

So we know what is need to be done, let's drop the rows that contain null and column headers, then change the numerical data type to int.

![image](https://user-images.githubusercontent.com/110689945/205914060-1669518c-3f61-4d71-8263-985906a877d9.png)

![image](https://user-images.githubusercontent.com/110689945/205914268-929039fe-7044-4e42-a6c3-cf07b5ed0007.png)

## Adding New Necessary Column

Before start to analysis, we need to adding some columns such as Month Number, Sales and City Name
![image](https://user-images.githubusercontent.com/110689945/205915002-d01d6646-89fa-43f7-9c8a-b94fe9b01ae5.png)

## Data Analysis and Visualization

Data analysis in term of business always related to the business question. So my analysis is based on business question that the answer can help give the business insight.

![image](https://user-images.githubusercontent.com/110689945/205915801-756e3cf8-622b-4ba2-9d6b-41f12c5209d8.png)
![image](https://user-images.githubusercontent.com/110689945/205915934-504a3260-71ef-4fec-aef6-70f4b3ce8331.png)
From the analysis above we have the insight of the best month for sales is December. Maybe it is related to Christmas and New Year so sales can increase.

What about the best city for sales?
![image](https://user-images.githubusercontent.com/110689945/205916646-2a9a6da2-5372-45f5-9f80-6df933b3fa1c.png)
![image](https://user-images.githubusercontent.com/110689945/205916857-135f091f-4e6a-48f5-936a-1a3d1cbe6d1a.png)
We now answer the question that based on data San Francisco is the best city for sales.

Now lets find out what time is the peak of sales?
![image](https://user-images.githubusercontent.com/110689945/205917447-5ee7ef56-39ba-4919-b823-2ee65b012be1.png)
![image](https://user-images.githubusercontent.com/110689945/205917644-a6a99eba-e564-41e3-beb5-d7e46a7f996d.png)

What about most sales product?
![image](https://user-images.githubusercontent.com/110689945/205917913-8359cae9-0549-4d62-8322-ba3c2b2e74bc.png)
![image](https://user-images.githubusercontent.com/110689945/205918000-a519244e-74f1-4afa-96eb-cf71a4fbe470.png)










