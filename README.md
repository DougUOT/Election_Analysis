# Election_Analysis

### Helping a Colorado Board of Election representative Tom in a political race review of the arranged outcomes for the U.S. Legislative region in Colorado.

## Overview of Election Audit

### All of this assignment is intended to report the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the election winner based on popular vote. Tom's manager wants to know if there is a way to automate the process using Python. If this audit is successful with Python, this process and code can be used to audit other constituencies and senatorial districts and local elections.
### There are three fundamental democratic techniques: mail polling forms, punch cards and direct electronic record or DRE counting machines. Polling forms sent via mail are typically counted physically at the principal office. Punch cards are gathered and placed into a machine that arranges the absolute votes and sends the outcomes back to the focal office. At last, the memory cards of the DRE counting machines are shipped off the focal and read by the P.C. This data is in the [election_results.csv](https://github.com/DougUOT/Election_Analysis/blob/master/Resources/election_results.csv) document. Through and through, the votes cast by these three techniques will decide the end-product of the races. After the votes are counted, the objective is to create a vote count report to confirm the rush to the U.S. Congress.
### The project's purpose is that the final code or script developed in Python provides the following information when the script is run in Visual Studio Code or printed to the terminal. The outcomes and data produced in this content were saved in the [election_analysis.txt](https://github.com/DougUOT/Election_Analysis/blob/master/Analysis/election_analysis.txt) record. 

### 1) Calculate the total number of votes cast.
### 2) Get a complete list of candidates who received votes.
### 3) Calculate the total number of votes each candidate received.
### 4) Calculate the percentage of votes each candidate won.
### 5) Get the voter turnout for each county
### 6) Calculate the percentage of votes from each county out of the total count
### 7) Calculate the county with the highest turnout
### 8) Determine the winner of the election based on the popular vote.

## Purpose of this Election Audit Analysis

### The database with the results of this election could be running using software such as Microsoft Excel. However, the reason for this analysis to have been carried out in Python is precisely to automate the compilation of data, be faster, and use best practices to implement in other elections in different counties.

## Resources

### * Data Source: [election_results.csv](https://github.com/DougUOT/Election_Analysis/blob/master/Resources/election_results.csv)
### * Overview of Election Audit Result: [election_analysis.txt](https://github.com/DougUOT/Election_Analysis/blob/master/Analysis/election_analysis.txt)  
### * Software: Pyton 3.8.8 64-bit, Visual Studio Code, 1.62.2

## Election-Audit Summary

### The Colorado Board of Election received 369711 votes from three different sources mentioned above; mail polling forms, punch cards and direct electronic record or DRE counting machines.

### For this election in Colorado, three candidates were in the election race; Charles Casper Stockham, Diana DeGette and Raymon Anthony Doane. 

### The candidates final results were:

![](https://github.com/DougUOT/Election_Analysis/blob/master/Resources/Election%20Results%20from%20Election_Analysis_txt%20file.png)

#### *Charles Casper Stockham received 85213, which represents 23% of all votes.
#### *Diana DeGette received 272,892 votes, representing 73.8% or nearly three-quarters of the total votes.
#### *Raymon Anthony Doane received 11606 votes, representing 3.1% of all votes.

### Diana DeGette was the victor of the political race; she received the majority of votes with 73.8% representing a total of 272892 votes. 

### Diana DeGette received almost three times more votes than the sum of the other candidates who were running for this election.

### Regarding the county, 24801 votes were registered that came from Arapahoe, which represents 6.7% of the total. The total of 38855 votes came from Jefferson, which represents 10.5%. Furthermore, finally, we had 306055 votes from Denver, representing just over three-quarters with 82.8% of all votes.

### The county with the highest turn was Denver with 82.8% and 306055 votes. Denver was the largest county with Colorado Board Election votes, and the majority of votes came from this county, representing approximately 80 out of every 100 votes from Denver. 

![](https://github.com/DougUOT/Election_Analysis/blob/master/Resources/Elections%20Results%20Additional%20Visualization_.png)

## Business proposal to the election commission

### As this is a process of auditing the result of an election, one of the most vital information to be considered and easily identified would be the results of votes per candidate and votes per count. If this code is used for other elections, with more candidates or counties, the final result would be essential to appear in descending order from the largest to the smallest. In this way, it streamlines the electoral committee for a quick decision on the winner. The same can be implemented for Senate or Congress positions in any election. Furthermore, for cases where there is a certain number of candidates to be elected, for example, if the Senate elects 15 candidates, it will be easy to observe the winners considering the fifteen first placed. 

### Therefore, [PyPoll with two modifications](https://github.com/DougUOT/Election_Analysis/blob/master/PyPoll_Challenge_with%20two%20modifications.py) were made to this code, the first placing the county votes in descending order and the second placing the final result of the most voted candidates in descending order. Python sorted() function was used for the two modifications in the original code.

### The first modification was applied to lines 109, 110 and 111, adding the Sorted function in Python to county votes. The initial results were kept, and additionally, we had the results sorted in descending order for the county votes.

![](https://github.com/DougUOT/Election_Analysis/blob/master/Resources/Capture%20first%20modification%20apllying%20sorted%20function.PNG)
![](https://github.com/DougUOT/Election_Analysis/blob/master/Resources/Capture%20Result%20first%20modification%20Sorted%20function.PNG) 

### The second modification was applied to lines 146, 147 and 148, adding the Sorted function in Python to candidate votes. The initial results were kept, and additionally, we had the results sorted in descending order for the candidate votes. 

![](https://github.com/DougUOT/Election_Analysis/blob/master/Resources/Capture%20second%20modification%20apllying%20sorted%20function.PNG)
![](https://github.com/DougUOT/Election_Analysis/blob/master/Resources/Capture%20Result%20second%20modification%20Sorted%20function.PNG)

## Limitations of this Pyhton Code

### All Python code available in this project (all files with *.py extension) were made considering a variable for load and save, with files available in a local path (lines 9 and 11). There may be some limitations or errors when running Python code. To run those Python codes in this project, it may be necessary to change the path in the lines mentioned above; the file used as base or load for this code is available on Github in the Resources folder, file [Election_Results.csv](https://github.com/DougUOT/Election_Analysis/blob/master/Resources/election_results.csv). Furthermore, the results as saved were recorded in Analysis Folder with the file [election_analysis.txt](https://github.com/DougUOT/Election_Analysis/blob/master/Analysis/election_analysis.txt).
