# Election analysis with python
## Overview of Election Audit
The purpose of this analysis was to help Tom,a Colorado Board of Election employee,to complete and automate using python the following election audit tasks of a recent local congressional. 

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election-Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
   - Charles Casper Stockham
   - Diana DeGette
   - Raymon Anthony Doane
- The candidate results were:
   - Charles Casper Stockham received 23.0% of the vote and 85,213 votes
   - Diana DeGette received 73.8% of the vote and 272,892 votes
   - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes
- **The winner of the election was:**
   - Diana DeGette, who received 73.8% of the vote and 272,892 votes

 ## challenge Overview
 Tom want us to continue helping him to automate also these other election audit tasks:
 1. Get a complete list of counties that had a turnout.
 2. calculate the total number of votes per county.
 3. Calculate the percentage of votes per county.
 4. Determine the largest turnout county.
 
 ## Challenge Summary
 - Counties that had a turnout were:
     - Jefferson with 10.5% of the vote and 38,855 votes
     - Denver with 82.5% of the vote and 306,055 votes
     - Arapahoe with 6.7% of the vote and 24,801 votes
 - **The largest county turnout was:**
     - Denver that had 82.5% of the vote and 306,055 votes
  
 ## Election-Audit Summary
Our PyPoll_Challenge.py code allows us to find votes and percentages by county and candidate. In addition, it is easy to determine in a short time the largest turnout per county and the winner of the election.

The code can be easily reused with some modifications for other election audit processes. What would change would be the election_results.csv file, the reading of this file and some instructions depending on the localities.


