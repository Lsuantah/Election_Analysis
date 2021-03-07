# Election_Analysis

## Project Overview

The objective of this project is to assist the Board of Elections to conduct election audit on a recently conducted congressional precinct election results.
Voting methods used in the election are Mail- In Ballot, Punch Cards and Direct Recording Electronic. Votes counts from all voting method are tabulated to determine the wining candidate. We are provided with the election results data to begin the audit. 

## Audit Method
Python code was used to read through the data and categorized the results by county and verified the total votes cast.

##Results

There were a total vote cast of 369,711.

## Vote by County

. Jefferson County had a total of 38,855 vote cast which amounted to 10.5% of the overall results.

. Denver recorded 306,055 total vote cast which represented 83.8% of all vote cast.

. Arapahoe County had 24,801 vote which is 6.7% of all electoral votes.

. Denver County was determined to be the county with the largest vote cast of 306,055 vote.


## Candidate Results

Charles Casper Stockham got 85,213 votes, 23.0% of the total results.
Diana DeGette received 272,892 vote which represents 73.8% of all votes. 
Raymon Anthony Doane had 11,606, accounting for 3.1% of all votes.

The winning candidate was Diana DeGette who received 272,892 vote which represents a percentage of 73.8%. 


![Election_results](https://user-images.githubusercontent.com/75961117/110253697-c0e54580-7f59-11eb-93f4-e21070a41a84.png)


## Conclusion

The Python code executed perfectly on the election data. Because we did not stipulate a particular county name and candidate names in the code, it can be used to audit any election results data. The code can be editted to fit for the format of the next election file. We can creat additional counts and loops to cover new information(columns) when needed.
Also, the path to the file can be changed to the new data file name and location by using the sample below. 

election_csv = os.path.join( "Resources", "election_results.csv")






