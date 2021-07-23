# Election_Analysis

## Overview of Election Audit
The Colorado Board of Elections tasked our team to complete an election audit of a recent local congressional election. 

The audit request required the following items: 
1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved votes. 
3. Calculate the total number of votes per candidate.
4. Calculate the total percentage of votes per candidate winning.
5. Determine the winner of said election based on popular vote.

## Resources used for analysis
* Data source: election_results.csv
* Software: Python, 3.9.6 and Visual Studio Code, 1.57.1

## Election-Audit Results: 
* Candidate Names:
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)

![Final_Election_Results.png](https://github.com/jjpardue/Election_Analysis/blob/07727c1b7341144aa5b1eb7fa73a03acb4fbcc9a/Resources/Final_Election_Results.png)

* Total number votes were cast in this congressional election:
    - Total Votes: 369,711
   
* Number of votes (and the percentage of total votes) for each county in the precinct:
    - Arapahoe: 24,801 votes (6.7%)
    - Denver: 306,055 votes (82.8%)
    - Jefferson: 38,855 votes (10.5%)
    
* County with the largest number of votes:
     - Denver: 306,055 votes (82.8%)

* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)
 
 
 
* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

With 73.8% of the popular vote (272,892 total votes), the winner of this election was Diana DeGette.

## Election-Audit Summary: 
The script written to provide the above analysis is just scratching the surface.

The code is easy to understand and workable should another election committee need to garner voter turn out in greater detail. For example, this project returned three basic categories for analysis: 1.) Ballot ID, 2.) County and 3.) Candidate. Should one desire to gain more insight on *where* votes are coming from or *who* is voting, we could edit the code to include city, city population, voter pronouns, income, etc.

We strongly recommend visiting our firm in the future for such election analyses due to the pure and humble fact that we are, simply stated, the best. XO
