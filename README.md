# Election Analysis Summary
The Election Commission requested additional information after reviewing the initial report required to complete the audit and understand and demographics of the area's voting population. Below is a list of additional information requested  
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout

# Purpose
We used the election_results.csv file to create loops, conditional statements with memberships, logical operators, and generate print statements to analyze the data to provide the requested results.  As one of the requirements, the program can be used for future elections, and the output is run from a command line. Below is a sample of how the data would look when running from the command line: 

![PyPoll_Challenge_Solution_cmd-line_screen_capture](https://user-images.githubusercontent.com/17502725/142344746-38b92dce-c4ad-470a-bae4-f7aadcb1b123.PNG)

# Election Analysis Overview 
## Election Outcomes
The counties under review are Jefferson, Denver, and Arapahoe.  There was a total of 369,711 qualified voters that cast their votes in the three counties. Below is a breakdown by Total Votes Cast, Voting Information by County, Largest County Turnout, Candidates Outcome, and Campaign Winner.  There is a limited amount of data that we have to work with, to determine more demographics information, such as gender, singled, married, etc.  

## Total Votes Cast:
369,711

## Voting Information by County:
Denver had the highest voter turnout with 306,055 representing 82.8% of the voting population, Jefferson with 38,855 or 10.5%, and Arapahoe with 24,801 votes or 6.7% of total cast votes. 

  Jefferson | Denver | Arapahoe 
|:-------:|-------------:|:---------:|
38,855 | 306,055 | 24,801 | 
10.5% | 82.8% | 6.7% |
    
## Largest County Turnout
As shown above, Denver had the largest county turnout of all three counties represented by the votes cast.   

## Candidates Outcomes
Below is further insight into how each candidate performed in the election. First, we looked at the number of votes and the percentage of votes received. Candidate Diana DeGette took a commanding lead with 272,892 votes or 73.8% of the votes, followed by Charles Casper Stockham with 85,213 votes or 23.0%, and Raymon Anthony Doane with 11,606 votes or 3.1%. 
 
Candidate | Total Votes | %
|:------------------------|-------------:|:---------:|
Charles Casper Stockham | 85,213| 23.0% |
Diana DeGette| 272,892 | 73.8% |
Raymon Anthony Doane | 11,606 | 3.1%|
  
## Campaign Winner
Candidate Diana DeGette was the clear winner in the election.

Winner | Winning Vote Count | Winning Percentage 
|:--------------|----------:|:--------------:|
Diana DeGette | 272,892 | 73.8% | 
 
# Conclusion
We initially determined the number of voters, followed by breaking down the county votes and calculated the the associated percentages, determine which county has the highest turnout, a breakdown of the candidate votes received and percentages, and identifying the winner of the campaign. The election commission can use the program in future elections and generate output by extracting information from the election results file.  There is a clear correlation between the winner, Candidate Diana DeGette, county turnout in Denver, and votes cast.

Using the program for future election will assist in validating the voter information and help in the prediction of the winners with some certainity.  A recommendation would be to to expand the information for greater insight of who is voting, gender, marital status, education levels, etc. Adding more content will require the code to be updated for futher use, but would not take that long to do.       

Thank you for the opportunity to assist you with the audit analysis.   
