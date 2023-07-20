## Pymaceuticals Inc. 

### Background 
In this project, I looked through two datasets provided. These datasets contained information on the number of mice being tested with different treatments and how things like body weight could affect the tumor volume. 249 mice with SCC tumor growth were treated with various drug regimens, and over the course of 45 days were observed and measured. This allowed me to properly compare the performance of Pymaceuticals' drug of interest, Capomulin, to the other drug regimens used. 

The following steps were taken to create multiple visualizations: 

At first we started by getting a count of the mice that were being observed in the study. I followed that by checking if there were any duplicate mice in the study and cleaning up the dataframe to only show the unique Mice ID. I used that dataframe to create a summary table that lists each of the drug regimen with the mean, median, variance, stdev, and stderr of tumor volume. I also created a similar table using the aggregate function to make the table more concise. 

After doing that, I was able to utilize the cleaned dataframe to create various bar and pie charts comparing the weight of the mice to the average tumor volume. Following that step, I also created boxplots and line graphs by calculating the quartiles, quantiles and charting them. And I finished off by creating scatterplots, and then calculating the regression and correlation. Below will be our visualizations. 

Summary Table & Aggregate: 

![image](https://github.com/stoddow313/Pymaceuticals-Challenge/assets/134353666/4d951622-9463-4d02-98f4-40ccde980416)
![image](https://github.com/stoddow313/Pymaceuticals-Challenge/assets/134353666/89afce10-bda6-481e-a94e-8dfc9cf145f5)

Bar & Pie Charts: 

![image](https://github.com/stoddow313/Pymaceuticals-Challenge/assets/134353666/731aee00-645f-48fe-8760-af413e004561)
![image](https://github.com/stoddow313/Pymaceuticals-Challenge/assets/134353666/4ca9bbb3-3c8e-4a42-8579-d0f3160eedef)
![image](https://github.com/stoddow313/Pymaceuticals-Challenge/assets/134353666/01bac236-e056-4321-954f-33576fe03a04)
![image](https://github.com/stoddow313/Pymaceuticals-Challenge/assets/134353666/e819180b-a1b1-4e47-9f26-e8a44008d232)

Boxplot & Line charts: 

![image](https://github.com/stoddow313/Pymaceuticals-Challenge/assets/134353666/6697e411-3c49-4d94-a08a-4ead421a3d22)
![image](https://github.com/stoddow313/Pymaceuticals-Challenge/assets/134353666/02ad2283-6316-407e-9d51-592df35d0867)

Correlation & Regression ScatterPlots:

![image](https://github.com/stoddow313/Pymaceuticals-Challenge/assets/134353666/478440e5-187a-4bba-b29a-10c3940a8eb4)
![image](https://github.com/stoddow313/Pymaceuticals-Challenge/assets/134353666/39799ccd-75c2-4640-a31d-a20ab41ec99c)

### Observations 

Looking through our data and charts, there are a few different things we were able to observe. 
First is that of the drugs used as treatement for the tumors, Capomulin and Ramicane had the greatest effect in reducing the tumor size. 
Secondly, we saw a strong positive correlation between mouse weight and average tumor volume (0.84). This indicates to us that as mouse weight increases, average tumor volume will also. 
And our final observation is that while all the drugs were tested, Capomulin and Ramicane had the most test subjects. 
