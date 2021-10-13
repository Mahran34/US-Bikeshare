# US-Bikeshare 
Basic Udacity project to explore bikeshare data using pandas 

# Project Overview 
In this project, we will make use of Python to explore data related to bike share systems for three major cities in the United States—Chicago, New York City, and Washington.
we will write code to import the data and answer interesting questions about it by computing descriptive statistics.
we will also write a script that takes in raw input to create an interactive experience in the terminal to present these statistics. 

# How to Run
You can input 'python bikeshare.py' on your terminal to run this program. I use Anaconda's command prompt on a Windows 10. 

# Project Details
The program takes user input for the city (e.g. Chicago), month for which the user wants to view data (e.g. May; also includes an 'all' option for no month filter), and day for which the user wants to view data (e.g. Sunday; also includes an 'all' option for no day filter).
Upon receiving the user input, it goes ahead and asks the user if they want to view the raw data (5 rows of data initially) or not. Following the input received, the program prints the following details:
- Most popular month 
- Most popular day 
- Most popular hour 
- Most popular start station 
- Most popular end station 
- Most popular combination of start and end stations 
- Total trip duration time 
- Average trip duration time 
- Maximum trip duration time 
- Minimum trip duration time 
- Types of users by number 
- Types of users by gender (if available) - The oldest user (if available) -
- The youngest user (if available) 
- The most common birth year amongst users (if available) 
- Finally, the user is prompted with the choice of restarting the program or not. 
 
# Requirements 
- Language: Python 3.xx 
- Libraries: pandas, numpy, time 

# Project Data 
All data provided by Udacity: 
- chicago.csv - Stored in the data folder, the chicago.csv file is the dataset containing all bikeshare information for the city of Chicago. 
- new_york_city.csv - Dataset containing all bikeshare information for the city of New York. 
- washington.csv - Dataset containing all bikeshare information for the city of Washington. Note: washington doesn't include the 'Gender' or 'Birth Year' informations. 

# Author: 
- https://github.com/Mahran34
