# CSE-350-Final-Project
Final project for UofL-CSE350/550. This project centered around learning the software development process including documentation and development. We were tasked to create an interface for the visualization and analysis of data from exercise trackers (https://support.empatica.com/hc/en-us/articles/360028646091).

In order to load your data into the application place your csv files into the project folder with both metadata.csv and dummy data.csv.

After your data is loaded into the project you will be met with a variety of displayed graphs with yor biometrics displayed. The x axis is time with the Y axis being your different data so you can compare trends and analyze your general health using the application. Below the graphs you will see a variety of buttons that provide you different functions to work with your data.

The Home button will reset the view-frame of the graph to its original position if you have made any changes

The left and right arrows will change between the different views moving either forward or backward

The pan button allows you to move the data in order to see further or previous data with the same zoom

The zoom button allows you to zoom in and out on the data to a Longer or shorter time.

The save button allow you to save an image of the current frame

There is also a display of the x and y value of where your mouse is at on the graph 

The aggregate button gives you an aggregate report of all of the data

The summarize button will summarize the data of a single graph

There is also a slider button to adjust each of the subplots parameters 

# Activity Analyzer
Initializes the program and creates the initial graphs. Responsible for loading the csv data into the file. 

# User Interface
Controls the user interface such as the buttons and calls that then go into the data handling. Updates the graphs depending on the button presses and responds to the mouse activity. 

# Data Handling
Handles the background data for each of the buttons such as what data is to be passed through with the aggregate and summarize function. 
