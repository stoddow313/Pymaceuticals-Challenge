## Pymaceuticals Inc. 

### Background 
In this project, I looked through two datasets provided. These datasets contained information on the number of mice being tested with different treatments and how things like body weight could affect the tumor volume. 249 mice with SCC tumor growth were treated with various drug regimens, and over the course of 45 days were observed and measured. This allowed me to properly compare the performance of Pymaceuticals' drug of interest, Capomulin, to the other drug regimens used. 

The following steps were taken to create multiple visualizations: 

At first we started by getting a count of the mice that were being observed in the study. I followed that by checking if there were any duplicate mice in the study and cleaning up the dataframe to only show the unique Mice ID. I used that dataframe to create a summary table that lists each of the drug regimen with the mean, median, variance, stdev, and stderr of tumor volume. I also created a similar table using the aggregate function to make the table more concise. 

After doing that, I was able to utilize the cleaned dataframe to create various bar and pie charts comparing the weight of the mice to the average tumor volume. Following that step, I also created boxplots and line graphs by calculating the quartiles, quantiles and charting them. Below will be our visualizations. 

### Observations 

Looking through our data and charts, there are a few different things we were able to observe. 
First is that of the drugs used as treatement for the tumors, Capomulin and Ramicane had the greatest effect in reducing the tumor size. 
Secondly, we saw a strong positive correlation between mouse weight and average tumor volume (0.84). This indicates to us that as mouse weight increases, average tumor volume will also. 
And our final observation is that while all the drugs were tested, Capomulin and Ramicane had the most test subjects. 
