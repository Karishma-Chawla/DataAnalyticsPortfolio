# Election Analysis
## Overview of Election Audit
The project is to assist a Colorado Board of Election employee in election audit of tabulated results of recent local congressional election in Colarado.
Currently this work is being done in excel but the objective is to automate it so it can be repurposed to audit other congressional districts , sentorial districts or local elections. Overall,the following tasks have been given to complete the election audit: 

* Calculate the total number of votes
* Get commplete list of candidates who receieved votes
* Calculate the total number of votes each candidates recieved
* Calculate the % of votes each candidates won
* Determine the winnner of election based on popular votes
* The voter turnout for each county
* The percentage of votes from each county out of the total count
* The county with the highest turnout

## Election-Audit Results:
The analysis of election shows that:

* There were 369,711 cast in the election

* Candidate results: Breakdown of the number of votes and the percentage of the total votes each candidate received.
	* Charles Casper Stockham received 23.0% of votes and 85,213 number of votes
	* Diana DeGette received 73.8% of votes and 272,892 number of votes
	* Raymon Anthony Doane received 3.1% of votes and 11,606 number of votes

* The winner if the election was Diana DeGette who received 73.8% of votes and 272,892 number of votes

* County Results:Breakdown of the number of votes and the percentage of total votes for each county in the precinct is
	* Jefferson: 38,855 votes accounting for 10.5% total votes
	* Denver: 306,055 votes accounting for 82.8% total votes
	* Arapahoe: 24,801 votes accounting for 6.7% total votes

* County with largest number of vote was :Denver
 
<img width="381" alt="Output" src="https://user-images.githubusercontent.com/98617082/159110482-3a799fe6-0512-4f84-97d5-e8b2f16609af.png">


## Election-Audit Summary
Using python, Tom has automated the task of auditing the election results of a congressional election in Colarado. 
The code has automated various calculations including total votes, vote count for each candidate/county, % votes for candidate/county, wnning candidate and county with highest turnout.
This has immense potential to be replicated with minor changes for other congressional districts, sentorial districts or local elections.Two examples of how it can be done is:
The code is scalable as it does limit the number of entries and loops through entire dataset without any upper limit

* Senatorial Elections: For senatorial elections instead of counting votes, the code can be modified to calculated state wise votes/district wise. If the data is available for
for districts/states, the naming convention can change from county to the more representative name. E.g. county_options,county_name can change to county_options or district_name.

 
* Analytics:Since the code is primarly looping through each line and counting the number of votes, any other available data like name of party can be replaced or added to existing data 
to find out the similar parameters like total number of votes, party wise votes, winning party. 

* Future elections: the code can used to conduct election audits in the future elections as well without any changes. 
	


## Resources
Data Source: election_results.csv
Software: Python 3.7.6, Visual Studio code: 1.65.2
