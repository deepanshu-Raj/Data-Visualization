# Data_Visualization [![Codacy Badge](https://app.codacy.com/project/badge/Grade/2632856d420648b49390ce00eb97c387)](https://www.codacy.com/manual/berlin.7.11.99/Data_Visualization?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=deepanshu-Raj/Data_Visualization&amp;utm_campaign=Badge_Grade)
Various plots for data visualisation

## Reference repo : <a href="https://github.com/deepanshu-Raj/Data_Visualization/blob/master/Data_Visualization.ipynb"><code>Repo</code></a>

## Run Instructions:

If using Collab : you can simply copy the code snippets and tweak the parameters to obtain various plots or change the data, to change the plots accordingly.<br><br>
If you want to run the code on your local envoirnment :
    
   - <b>Download & Install python3 :</b> <code>https://www.python.org/downloads/</code>
   - <b>Either install Jupyter-lab or install Jupyter-notebook (install any one, Jupyter-lab preferred)</b>
   
      - <b>For installing Jupyter-Lab :</b>
        ![image](https://user-images.githubusercontent.com/54600788/116506259-87d2ad00-a8da-11eb-94d9-0c913ea9888f.png)
      - <b>For installing Jupyter-Notebook :</b> 
        ![image](https://user-images.githubusercontent.com/54600788/116506383-c6686780-a8da-11eb-9dee-e078d4a7743b.png)

     
   - <b>Install Matplotlib :</b> <code>pip install matplotlib</code>
   - <b>Install Seaborn :</b> <code>pip install seaborn</code>
   - <b>Install Numpy :</b> <code>pip install numpy</code>  

### All the pip commands are to be run in your terminal(For windows users)

# Index :

A - pyplot methods()  
--------------------------------------------
1 : <b>Line plot</b>
    
   A line graph is commonly used to display change over time as a series of data points connected by straight line segments on two axes. Line graphs are useful in that they show data variables and trends very clearly and can help to make predictions about the results of data not yet recorded.
   
   ![image](https://user-images.githubusercontent.com/54600788/116516839-bc9b3000-a8eb-11eb-89e4-e585519dc9e0.png)

    
2 : <b>Scatter plot</b>

   Scatter plot's primary uses are to observe and show relationships between two numeric variables. The dots in a scatter plot not only report the values of individual data points, but also patterns when the data are taken as a whole.
   
   ![image](https://user-images.githubusercontent.com/54600788/116516893-cf156980-a8eb-11eb-8e74-a7b08f41a73d.png)


3 : <b>Bar Plot</b>
    
   Bar graphs are used to compare things between different groups or to track changes over time. However, when trying to measure change over time, bar graphs are best when the changes are larger.
   
   ![image](https://user-images.githubusercontent.com/54600788/116516940-ddfc1c00-a8eb-11eb-96b1-d1f59fd0c0d1.png)


4 : <b>Pie Chart</b>

   There are two primary use cases for a pie chart: If you want your audience to have a general sense of the part-to-whole relationship in your data and comparing the precise sizes of the slices is less important. To convey that one segment of the total is relatively small or large.
   
   ![image](https://user-images.githubusercontent.com/54600788/116516987-ed7b6500-a8eb-11eb-9d27-2c69c8a796f3.png)


5 : <b>Histogram(Normal Distribution)</b>

   A histogram is used to summarize discrete or continuous data. In other words, it provides a visual interpretation. This requires focusing on the main points, factsof numerical data by showing the number of data points that fall within a specified range of values (called “bins”). It is similar to a vertical bar graph.
   
   ![image](https://user-images.githubusercontent.com/54600788/116517024-f9672700-a8eb-11eb-971d-b442d91b01f4.png)


B - seaborn methods() 
--------------------------------------------
1 : <b>Bar Plot</b>
    
   ![image](https://user-images.githubusercontent.com/54600788/116517054-04ba5280-a8ec-11eb-9cc2-54e5355fc5c9.png)

    
2 : <b>Count Plot</b>

   It is used to Show the counts of observations in each categorical bin using bars.
   
   ![image](https://user-images.githubusercontent.com/54600788/116517087-113eab00-a8ec-11eb-86cb-76255255b184.png)


3 : <b>Box Plot</b>

   A box and whisker plot (sometimes called a boxplot) is a graph that presents information from a five-number summary.A box and whisker plot is a way of summarizing a set of data measured on an interval scale. It is often used in explanatory data analysis. This type of graph is used to show the shape of the distribution, its central value, and its variability.
    
   ![image](https://user-images.githubusercontent.com/54600788/116516268-0afbff00-a8eb-11eb-965b-c666a2e557c9.png)
    
   


4 : <b>Violin Plot</b>

   Violin plots are used when you want to observe the distribution of numeric data, and are especially useful when you want to make a comparison of distributions between multiple groups. The peaks, valleys, and tails of each group's density curve can be compared to see where groups are similar or different.
   
   ![image](https://user-images.githubusercontent.com/54600788/116517177-37fce180-a8ec-11eb-9276-7994335d0797.png)


5 : <b>Distribution Plot & KDE Plot && Joint Plot</b>

   <code><a href="https://www.geeksforgeeks.org/seaborn-distribution-plots/#:~:text=It%20provides%20a%20high%2Dlevel,examining%20univariate%20and%20bivariate%20distributions.">Read this for information about distribution plot!!</a></code>
   
   ![image](https://user-images.githubusercontent.com/54600788/116517200-421ee000-a8ec-11eb-983e-1cd7ee336c45.png)
    
   ![image](https://user-images.githubusercontent.com/54600788/116517246-519e2900-a8ec-11eb-945f-857350367766.png)

   

6 : <b>Heat Map</b>
   
   Heatmaps are used to show relationships between two variables, one plotted on each axis. By observing how cell colors change across each axis, you can observe if there are any patterns in value for one or both variables.
   
   ![image](https://user-images.githubusercontent.com/54600788/116517302-64b0f900-a8ec-11eb-8dd4-e8ea86951e8e.png)

