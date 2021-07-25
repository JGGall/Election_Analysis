# Election_Analysis: A PyPoll Challenge

## 1. Overview of Election Audit:
A Colorado Board of Elections employee tasked me with completing the election audit of a congressional election in that state by writing Python code in such a way  as to calculate the total number of votes cast, to provide the number of votes cast in each of the district's counties and the percentage of the total vote cast in each county, to determine which county had the largest number of votes, to determine the number of votes each candidate received and the percentage of total votes each candidate received, and to determine the candidate who won the election, along with that person's vote count and percentage of the total votes cast.

## 2. Election-Audit Results:
- There were 369,711 votes cast in this congressional election.
- The district is comprised of three counties:
  - Jefferson County had 38,855 votes, which was 10.5% of the total votes cast in the congressional district.
  - Denver County had 306,055 votes, which was 82.8% of the votes.
  - Arapahoe County had 24,801 votes, which was 6.7% of the votes.
- Denver County had the largest number of votes in the congressional district.
- The candidate results were as follows:
  - Charles Casper Stockham received 85,213 votes, or 23.0% of the vote. 
  - Diana DeGette received 272,892 votes, or 73.8% of the vote.
  - Raymon Anthony Doane received 11,606 votes, or 3.1% of the vote.
- The winner of the election was Diana DeGette, who received 272,892 votes, or 73.8% of the total votes cast in the congressional district.
- This is a screenshot of the script's output to election_analysis.txt:
![Election Results Screenshot.png](https://github.com/JGGall/Election_Analysis/blob/main/Resources/Election%20Results%20Screenshot.png)


## 3. Election-Audit Summary:
The script required to retrieve the election results is a complicated one, but it is very much transferrable to other districts and to other kinds of elections in the state. While the same script would work without alteration in other congressional races, it would need to be modified in other races that take place on election day:
- State senatorial districts are much smaller than U.S. congressional districts, and state house districts are smaller still. While they might include portions of two different counties, it would be necessary to modify the code to provide useful information about votes per precinct rather than votes per county.
- City and school district elections involve candidates who hope to represent even smaller sections of a city (wards, for example) or of a school district, so the code could be modified to capture and analyze information about votes from those smaller geographic areas.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

