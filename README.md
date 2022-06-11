# Election Analysis

## Project Overview
In this data analysis project, we will be performing an audit using election information given to us by the Colorado Board of Elections.
We utilized Visual Studio Code with Python.

We will be determining:
1. The total number of votes cast
2. A list of all candidates and how many votes they each recieved
3. The percentage of votes each candidate recieved
4. Voter turnout by county
5. County vote percentage
6. The county with the highest turnout
7. The winner of the election

---

## Election Audit Results
- **Total number of votes:** 369,711
- **County votes:**
   - Jefferson: 10.5% (38,855)
   - Denver: 82.8% (306,055)
   - Arapahoe: 6.7% (24,801)
- **Largest County:** Denver
- **Candidate Votes:**
   - Charles Casper Stockham: 23.0% (85,213)
   - Diana DeGetter: 73.8% (272,892)
   - Raymon Anthony Doane: 3.1% (11,606) 
- **Winner: Diana DeGette**
- **Winning Vote Count: 272,892**
- **Winning Percentage: 73.8%**

---

## Election Audit Summary
This script did a great job at gathering the information we needed

![terminal](https://user-images.githubusercontent.com/19378130/173164432-7a354428-dd82-459d-94ac-0fde83d87ca3.png)

It could easily be used for other election's audits. Aside from using it for other local elections with a differnt set of counties, it could be elaborated a bit more to be used for a country wide election. If we modify the code to include state based code and correct the rows and headers we read, we could get a similar outcome to the one we see here. This would give us the potential to see votes per county per state and really get into the details!

![state list](https://user-images.githubusercontent.com/19378130/173164867-398269a3-47a6-4dd5-a360-b8b6eb827254.png)
