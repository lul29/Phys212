# How do we make sense of data?

Physics is an experimental science in which we make measurements and try to make sense of the data taken. Because of natural variations in the phenomenon and because of the measurements techniques, the numbers we collect generally vary. We will need to make conclusions by looking at an ensemble of data points. To do so we look at patterns and we use statistics. 

In this class, we will not assume any prior knowledge of statistics and we will not require detailed statistical calculations. Instead we will focus on knowing a few important concepts and we will focus on using statistical tools to visualize and compute for us all the important properties of our dataset. 

In this class we will primarily use StatKey. <a href="http://www.lock5stat.com/StatKey/" target="_blank">StatKey</a> which is a free Javascript application that is used with the textbook "Statistics: Unlocking the Power of Data". 

Things to remember

* you need to create a .csv file with a first row of header (a txt file can also work). For most, using excel may be the easiest. 
* upload the file in StatKey. 


## Analyzing Data

Even in a perfect world, measured quantities normally varies and one goal of physics is to detect real variation on top of normal "noise". 

### Type of variables

* Independent variable: This is the one changed by the scientist. 
* Dependent variable: This is the variable that the scientist observes to see if or how it is affected by changes made in the independent variable. 
* Controlled variable. This is a variable that the scientist will try to keep constant while changing the independent variable. 

In your lab this week you will study how current (measured by angle on compass) depends on the length of the wire. 

|type|variable|
|----
|Independent| length of the wire|
|Dependent| angle|
|Control| type of wire (and diameter), batteries|

There are often multiple control variables. It really refers to anything that you are NOT changing. 

### Two quantitative variables. 

We will often look at cases where we have two quantitative (numerical) variables. We will use the scatterplot to visualize. 

<lrndesign-sidenote label="Definition: Scatterplot" icon="bookmark" bg-color="#c2c2a3">
A scatterplot is a graph with the independent variable (or a function of) as the horizontal axis and the dependent variable (or a function of) as the vertical axis. The paired data is represented as a dot on the graph. 
</lrndesign-sidenote>

When we look at a scatterplot, we are interested to see whether there is a pattern, a trend. 

For example, the image below shows a scatterplot created in Statkey of the ph vs average mercury for 53 different lakes in Florida.

[ciscode|rev=1|tool=elmsmedia|item=4306|entity_type=node|render=display_mode|display_mode=image]

While the data is pretty scattered, a careful observation of this scatterplot reveals there there seems to be a trend in that high ph lakes seems to be low average mercury while the reverse is true of low ph. 

On the right of the image, you see the mean and standard deviation of each variable as well as the sample size. There is also a new statistics we have not seen before called the correlation.

<lrndesign-sidenote label="Definition: Correlation" icon="bookmark" bg-color="#c2c2a3">
The correlation is a measure of the strength and direction of linear association between two variables. 
</lrndesign-sidenote>

The correlation often denoted r is a number between -1 and 1. Values close to +1 or -1 means strong association (positive or negative) while values close to 0 means no association. 

