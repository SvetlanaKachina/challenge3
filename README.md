# challenge3
For PyBank  
In order to analyze the financial records of our company, we begin looking at a financial dataset called budget_data.csv. The dataset is composed of two columns: "Date" and "Profit/Losses".

For the actual analysis we need to create a Python script that analyzes the records to calculate each of the following values:

The total number of months included in the dataset
The net total amount of "Profit/Losses" over the entire period
The changes in "Profit/Losses" over the entire period, and then the average of those changes
The greatest increase in profits (date and amount) over the entire period
The greatest decrease in profits (date and amount) over the entire period
Finally, the script after printing is exported to a text file with the results.


At first we declare all of our targeted variables by assigning 0 to the months and total_net as or starting point. As well, while declaring reatest increase with the date, we can start our comparison at 0, for the greatest decrase we ought to pick unreachably (in this case) large number as our strating point.

We then open and read our csv using "with" statement, identifying the Header and extracting our first row to avoid apending to net change list.

In writing out the comparison process, we identify our Total Months, Total net change, and calculate greatest increase as well as decrease.
After, we Generate an output path in order to make it easier for us at the end, identifying required dashes, decimals, etc.

We then print out the output and write text file using "with" statement. 

For PyPoll
In order to help a small, rural town modernize its vote-counting process, we are to create a Python script that analyzes the votes and calculates each of the following values:

The total number of votes cast
A complete list of candidates who received votes
The percentage of votes each candidate won
The total number of votes each candidate won
The winner of the election based on popular vote
Finally, the script after printing is exported to a text file with the results.

After files to load and output declared, we define list of candidate_names and a dictionary of candidate_votes.
We, then, declare winning_candidate ( to have a name at the end), and declare identify our winning_count_tracker at 0 as the starting point.
Using statement "with" we open our csv data file, skipping the header.
Using "loop" we are counting votes for each candidate in order to sort our names and numebrs of votes associated with them.

Further, we convert total votes for the each candidate into percentage using straight math formula. After which, using "if" we compare the results and identify Winning Candidate.
After, we Generate an output path in order to make it easier for us at the end, identifying required dashes, decimals, etc.
We then print out the output and write text file using "with" statement. 
