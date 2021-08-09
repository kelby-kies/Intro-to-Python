# Introduction to Python Workshop
Hosted by the BCB-GSO

Written by Kelby Kies

August 16, 2021

## Purpose
The purpose of this workshop is not to turn you into a computer scientist or an expert Python programmer. The purpose of this workshop is to introduce you to basic syntax/commands of Python and to give you examples of how Python is used in different biological contexts. 

## Outline
## Cloning GitHub repository


## Installation (~ 15 minutes)
Please install Anaconda using the 'Installing_Anaconda_Python' tutorial in this repository



## Python is Awesome! (~5-10 minutes)
### What is Python?
"Python is an easy to learn, powerful programming language. It has efficient high-level data structures and a simple but effective approach to object-oriented programming. Python’s elegant syntax and dynamic typing, together with its interpreted nature, make it an ideal language for scripting and rapid application development in many areas on most platforms."

<https://docs.python.org/3.6/tutorial/>

funny python meme


### Pros & Cons
|Pros | Cons | 
|:-----|:----:|
|efficient high level data structures|speed limitations|
|support object oriented programming|issues with threading|
|simple syntax|Not native to mobile environment|
|versatile|high memory consumption|
|easy to use||
|fast to develop||
|Has a ton of libraries (Pandas, Numpy, BioPython etc. )||



### Where to get help on Python
- http://www.python.org
- Your BCB-GSO Tutorial! Or any other tutorial out there
- https://wiki/python.org/moin/BeginnersGuide/Programmers
- Google! (This goes for anything in grad school. Google is your friend.) 

Not sure if I am good at programming of good at googling picture

### What could I use Python for?
- writing bioinformatic tools: give examples
- visualizing data
- processing data
- statistical modeling (BCB2)

## The Basics.... (first hour)
### How to run Python

1. Double click on the Anaconda Navigator that we just downloaded
2. Launch a new Jupyter Notebook
3. Navigate to the location where you cloned this tutorial
4. Open up 'TheBasics.ipynb'


### syntax & Basic Structure


### Arithmetic
### Strings
### Variables
define a variable; explain that this variable holds a value
### Lists
We can group objects together in a 'list' 
A list is defined by using [] and separating each object with a ,

x = [1,2,3,4,]

y = ['Hello', 'How', 'are', 'you', 'today?']

You can index a list similar to how we index a string to select a specific character. 
(A string is just a list of characters.)

We can add and remove objects from a list. 
To add: append(), extend() -> puts 2 lists together. 
TO remove: 



### Dictionaries
A dictionary is a collection of key & values pairs. 
You can look up the value of a key using the command: dictionary[key]
How to add a new value to a list: dictionary[key] = new_value



### basic exercises
1. Print the sequence alone (without header '6404|')
2. Print the sequence alone, all in lower-case
3. Print the index of substring 'GAAC' (first occurrence only)
4. Make it a RNA sequence and print it out (change every T to U)
5. Add 'CAGACACGC' to the end of the sequence and print it out


### Functions

#### What is a function?
a function is a chunk of code that takes input values and performs a 'function' on it to get an output. Some functions are simple, but some can be complicated. 

#### Structure of a function
 def function_name(input, values)
 {
 output_value = input * values
 return outpput_value
 }
 TO call a function: 
 function_name(2,4)
 
#### Built in Python functions
Python has many built in functions. One example is print(value)
value is the input value into print and the print function will take that value and print it to the standard out. 

#### Importing new functions using Libraries
One can import a library with < import package_name> to load all of the functions of that package. 

Popular packages used by Biologists: 

* NumPy
* Pandas
* BioPython

 

## Visualizations (2nd hour)
citation: https://www.analyticsvidhya.com/blog/2021/02/an-intuitive-guide-to-visualization-in-python/

one of the most utilized features in Python

**Python Packages for Visualization:**

* **Matplotlib**: uses numPy; comes with a wide variety of plots like line, bar, scatter, historgram, etc.; John Hunter 2022
* **Seaborn**: dataset oriented library for making statistical representations in Python; uses Pandas data structures; 
* **plotly**: interactive, open-source, high-level, declarative and browsers-abased visualization library for Python. scientifc chars, 3D graphs, statistical charts, financial charts; 
* **ggplot**: grammar of graphics implemented in Python; mapping of data to asthetic attributes and geometric objects. 


###How to use the right visualization?
depends on the data type and the question you are asking. 

**Different types of graphs:** 

* bar graphs:
	* **bar chart** ( horizontal) : used to compare metric values across diff. subgroups of data. more groups is better for a bar chart.
	* **column chart** (vertical):  used to compare a single category of data between individual sub-items
	* **grouped bar chart**: used to compare values in certain groups and sub-groups
	* **stacked bar chart**: compare the total sizes across the available groups and composition of different subgroups. 
* **line chart**: used to represent continuous data; trend across time. 
* **histogram**: observe distribution of a single variale with a few data points. 
* **scatter plot**: idetntify relations between 2 variables. can be used when the dependent(y) variable can have multiple values for the independtnt(x) variable. 
* **box plot**: used to show shape of distribution and the sumamry of the data. 





