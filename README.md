# Election-Analysis

## Overview of Election Analysis
We are provided with a large, tabulated Data File of Us Congressional Precinct in Colorado election. We need to report back to client certain data, such as percentage of votes for each candidate, winning candidate name, number of total votes, etc. Basically we need to provide election results.

### Election Audit Results
After we created a code, we got the outcome which is displayed in image attached below.

![Screenshot (50)](https://user-images.githubusercontent.com/116606765/202612315-3d73b726-7b81-4f60-8bc7-f7b9564e72ec.png)

Here we are going to address the outcomes.

•How many votes were cast in this congressional election?
  Total Votes: 369,711
  
•Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  County Votes:
  
    Jefferson: 10.5% (38,855)
    
    Denver: 82.8% (306,055)
    
    Arapahoe: 6.7% (24,801)


    
•Which county had the largest number of votes?
  Denver!
  
  [Election Results](https://user-images.githubusercontent.com/116606765/202619663-f276121a-86c3-442d-8207-ccf47c8152db.png)

  
•Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

  Charles Casper Stockham: 23.0% (85,213)
  
  Diana DeGette: 73.8% (272,892)
  
  Raymon Anthony Doane: 3.1% (11,606)
  
•Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

  Winner: Diana DeGette
  
  Winning Vote Count: 272,892
  
  Winning Percentage: 73.8%

## Election Audit Summery
This script can be used by Colorado election commission for various elections such as, Local Elections, Senatorial Districts, Financial campaigns, etc., with certain adjustments of course.
For example, we need to change the source where we are going to take information from, so file_to_load would have a different source of info.

  file_to_load 👌 = os.path.join("..", "Resources", "election_results.csv")-this is the original one.
  
Same goes for file_to_save. 
If the data is different, we would also have to adjust our variables. say if we are sorting for cities and not counties, we would have to set up different variable and assign correct date type.

winning_county = 0 can become winning_city=0

and that will be changed through the whole script.
