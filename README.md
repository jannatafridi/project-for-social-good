# project-for-social-good
# Unit 3 - Data for Social Good Project 

## Introduction 

Software engineers develop programs to work with data and provide information to a user. Each user has different needs based on the information they are looking for from data. Your goal is to create a data analysis program for your user that stores and analyzes data to provide the information they need. 

## Requirements 

Use your knowledge of object-oriented programming, one-dimensional (1D) arrays, and algorithms to create your data analysis program: 
- **Write a class** – Write a class to represent your user or business and store and analyze their data with no-argument and parameterized constructors. 
- **Create at least two 1D arrays** – Create at least two 1D arrays to store the data that your user needs information about. 
- **Write a method** – Write a method that finds or manipulates the elements in a 1D array to provide the information your user needs. 
- **Implement a toString() method** – Write a toString() method that returns general information about the data (for example, number of values in the dataset). 
- **Document your code** – Use comments to explain the purpose of the methods and code segments and note any preconditions and postconditions. 

## User Story 

Include your User Story you analyzed for your project here. Your User Story should have the following format: 

> As an [Pro Youtuber], <br> 
> I want to [make a lot of Youtube videos], <br> 
> so that I can [receive a Gold Youtube Button]. 

## Dataset 

Dataset: https://www.kaggle.com/datasets/surajjha101/top-youtube-channels-data
- **Subscriber** (int) - the number of subscribers 
- **Views** (int) - the number of views
- **Category** (String) - the category of a video


## UML Diagram 

![UML Diagram for my project](https://docs.google.com/drawings/d/1_dUJLEIxuR2lTvrwjztyTQJMpXV3bYL4kl-tocQrABo/edit?usp=sharing) 

## Description 

For our project, our goal is to help a Youtuber analyze different data sets to help them increase their subscriber count in order to get the Gold Button. The items we needed to complete this task were the number of subscribers, the number of views a video has, and the type of category the video is in. Once we got the dataset from Kaggle, we created three text files; subs, views, and category, to store the values that we can later utilize. Then we created two classes: UserStory and DataRunner. 
Essentially, the UserStory class contains the arrays (subs[], views[], and category[]) to store the elements from our text files. Then we incorprate a constructor to intiliaze the arrays to read the data using the FileReader. Then we use methods to find the answers to the questions we posed in our User Story, such as finding the average subscribers. 
In our DataRunner class, it creates an instance of our UserStory, calls on the methods in our UserStory and prints them out for us to see the results.