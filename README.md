# python-challenge
Using Python scripts to analyze financial records and modernize the vote-counting process.

## Description
This project is divided into two sections – PyBank and PyPoll.

### [PyBank](PyBank)
The .csv file in the "Resources" folder is a financial dataset with two columns, "Date" and "Profit/Losses".

The Python script analyzes and calculates the following:
- total_months: The total number of months in the dataset
- total_net: The net total amount of "Profit/Losses" over the entire period
- net_change: The changes in "Profit/Losses" over the entire period
- average_net_change: The average of the changes in PL
- greatest_increase: The greatest increase in profits (date and amount) over the entire period
- greatest_decrease: The greatest decrease in profits (date and amount) over the entire period

The output file "budget_analysis.txt" is located in the "analysis" folder.

### [PyPoll](PyPoll)
The .csv file in the "Resources" folder is a set of poll data with three columns, "Voter ID", "County", and "Candidate".

The Python script analyzes then, calculates and generates the following:
- total_votes: The total number of votes
- all_candidates: A complete list of candidates who received votes
- vote_percentage: The percentage of votes for each candidate
- no_of_votes: The total number of votes for each candidate
- winning_candidate: The winner of the election

The output file "election_analysis.txt" is located in the "analysis" folder.
