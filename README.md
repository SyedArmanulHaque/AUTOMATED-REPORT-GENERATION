# AUTOMATED-REPORT-GENERATION

***COMPANY*** : CODTECH IT SOLUTION

***NAME*** : SYED ARMANUL HAQUE

***INTERN ID*** : CT04DN1420

***DOMAIN*** : PYTHON PROGRAMMIN

***DURATION*** : 4 WEEKS 

***MENTOR*** : NEELA SANTOSH

****This Python script is used to read data from a CSV file containing cricketers' performance statistics and generate a well-structured PDF report using the fpdf library. The CSV file, named cricketers1.csv, is expected to contain data in columns such as Name, Team, Runs, and Wickets for each player.
The first part of the code reads the data using Python’s built-in csv module.The data from each row is added to a list called cricketers. The Runs and Wickets values are converted to integers so they can be used for calculations.After reading the data, the script analyzes it. It calculates the total number of players by counting the list elements. It then adds up all the runs to get the total runs and computes the average by dividing this total by the number of players. To find the best performer, it uses the max function to identify the player with the highest number of runs.
The script then creates a PDF report using the fpdf library. A custom class PDF is defined, which includes a header displaying the report title and a footer showing the page number. T
A new PDF document is created, and a page is added. The script sets the font and writes key statistics like total players, average runs, and top scorer’s name and score.
At the top of the PDF, key performance metrics are displayed:
Total Players: 5
Indicates that the report contains data for five individual cricketers.
Average Runs: 9740.00
This is the average number of runs scored by the players listed. It shows a high performance level, considering the players included are all international stars.
Top Scorer: Virat Kohli (12000 runs)
Among the players listed, Virat Kohli from India has scored the highest number of runs, making him the standout performer in terms of batting.****

*Output:
![Image](https://github.com/user-attachments/assets/3472e37f-6d2f-4eb8-b369-9fedb6099e1d)
