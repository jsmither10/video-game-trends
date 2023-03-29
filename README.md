# Video Game Trend Analysis
---
Researching video game trends over time

This project is an analysis of video game data over time. The final analysis file is written from the perspective of a young professional looking to explore video game data while looking for a job as a video game developer and includes 5 questions to anwser about the industry. 

The raw data file is from Kaggle([link to Kaggle data](https://www.kaggle.com/datasets/thedevastator/global-video-game-sales-ratings?resource=download)). The data that originally came from  Timo Poutanen at the University of Helsinki ([link to Original data source](https://zenodo.org/record/2454579#.Y9Y2c9JBwUE)). It should be noted that the data set used here was initially created tagged and validated by the original author and some fields may have a slight bias dependent on that author. 

The final data used was also edited from the raw file in the following ways:

1. Removed unnecessary columns from the dataframe 
2. Removed null values found in the Year_of_Release, Name, Publisher, and Genre columns. This left the final data set as 16416 rows and 9 columns
2. Update the Year_of_Release column from a float to an int



## Summary

The entire project is done using Python in jupyter notebooks. The following is a guide to accessing the project files:
1. Fork the repository [repo link](https://github.com/jsmither10/video-game-trends.git)  
2. Clone the repository from your Github account
3. Install the **requirements.txt** file to install necessary packages
4. There are two primary files included
    a. The **data-exploration.ipynb** file is the original data exploration of the source file. The source file is found in the data folder in the repository.
    b. The **data-review.ipynb** file is the final project file that runs through the questions, data analysis, and reporting for the data set. This file is broken out into four sections:
    1. Cleaning the Data
    2. Anwsering the Questions
    3. Making Cool Graphs
    4. Final Notes and Thoughts
    

    
## Features
The following features are included in this analysis:
- **Feature 1: Read Data In**
    - Used pandas to read in data downloaded into a dataframe
- **Feature 2: Manipulate and Clean Data**
    - Clean the dataframe to remove columns not relevant for project hypothesis
    - Remove null values from data set
- **Feature 3: Analyze your data!**
    - Counts of Genres
    - Genre Groupby
    - Sales Sums
    - Min and Max values
    - Creating Bins
    - Adding new columns
- **Feature 4: Visualize your data!**
    - Made graphs using Matplotlib. Graphs include:
            - Bar Plots
            - Mulit-line Graphs
            - Grouped Bar Plot
            - Table
- **Feature 5: Interpret your data and graphical output**
    - Analysis included in * *Final Notes and Thoughts* *



