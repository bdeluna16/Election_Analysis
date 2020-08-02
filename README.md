# Election_Analysis
## Project Overview
A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election:
  1. Calculate the total number of votes.
  2. Get a complete list of candidates who received votes.
  3. Calculate the total number of votes each candidate received.
  4. Calculate the percentage of votes each candidate won.
  5. Determine the winner of the election based on popular vote.

## Resources
* Data Source: election_results.csv
* Software: Python 3.8.3, Visual Studio Code 1.47.3

## Summary
The analysis of the election show that:
* There was a total of 369,711.00 votes in the election
* The candidates were:
  * Charles Casper Stockham
  * Diana DeGette
  * Raymon Anthony Doane
* The candidate results were:
  * Charles Casper Stockham recieved 23.0% of the vote with 85,213 number of votes.
  * Diana DeGette recieved 73.8% of the vote with 272,892 number of votes.
  * Raymon Anthony Doane recieved 3.1% of the vote with 11,607 number of votes.
* The winner of the election was:
  * Diana DeGette who received 73.8% of the vote with 272,892 number of votes.

## Challenge Overview
The Colorado Board of Elections has requested additional data to complete their congressional election audit. They have requested the information below:
  1. The voter turnout for each county.
  2. The percentage of votes from each county out of the total count.
  3. The county with the highest turnout.

## Challenge Summary
 * There was a total of 369,711 votes in the congressional election
 * The voter base for the election was comprised of 3 counties.
 * The results below show the number of votes and perecentage of total votes of the election for each of the 3 counties.

 ![image](https://user-images.githubusercontent.com/67936161/89132957-c1ea5c00-d4cc-11ea-87fc-9adeca2d2ef8.png)

* The data shows that Denver county had the largest number of votes

* The results below show the number of votes each candidate received in the election and the percentage of the total votes they received

![image](https://user-images.githubusercontent.com/67936161/89133052-88feb700-d4cd-11ea-9ea1-af441ddda4db.png)

* The data shows that Diana DeGette was the winner of the election. She received 272,892 votes which made up 73.8% of the total votes

### Summary Statement
The script that I made for this election audit can be used for any election. However, in order to use this for other elections some modifactions will need to be made.
See below for examples of modifications:
  1. The code to set the variables used to output the results in the analyis can be changed to whatever is necessary. 
  2. The code to create the lists/dictionaries of the metrics being measured can be changed as well.
``` 
  Candidate Options and candidate votes.
  candidate_options = []
  candidate_votes = {}

  Create a county list and county votes dictionary.
  candidate_counties = []
  candidate_counties_votes = {}

```
