# Election_Analysis

## Overview of Election Audit

	The goal of this project is to create a python script to automate the organization of data to display election results. 

### Purpose
In this script I initialized a list of candidates and counties and created a dictionary in order to store the candidate's/county's vote count. I then imported a csv file to to be read in python. 
We then used a loop to go through all of the rows in the csv and add candidates and counties that weren't previously in our list and added a vote to the dictionary associated with that county or candidates key.  
After each row passed a vote was added to total votes. Then I took that data and began writing to a file. First I printed the total number of votes then wrote it to a text file. 
Then the script looped through the dictionaries of of the counties and calculated the percentage of votes each of them had along with the number of votes. These were then printed and written into the text file.
Inside this loop if statements and plaeholder variables were used to determine the county with the largest number of votes. After exiting the loop the the county with the largest number of votes was printed and written to the text file.
A similar process was then repeated in order to get the same information regarding the candidates. 


## Election-Audit Results

*How many votes were cast in this congressional election?

*Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

*Which county had the largest number of votes?

*Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

*Which candidate won the election, what was their vote count, and what was their percentage of the total votes?


## Election-Audit Summary
Overall the script written for the election audit was fairly modular. it can be used for any number of candidates due to the utilization of the array and dictionary combination. There are a couple of modifications that could be made 
in order to ensure ease of use and make it more applicable to other elections. Additional information can be tracked about the candidates such as their position which would allow the code to sort through multiple elections at a time. 
The second suggestion I would make in order to organize the more complicated data I would create a candidate class that could be assigned attributes. This could be used to provide things such as party affiliation or demographic information
that would allow for additional political analysis. At this point it would also be advantageous to allow the user to input what specific information the user would like to access. 