# Colorado Board of Election Analysis

## Project Overview

I am participating in an election audit for the Colorado Board of Elections where I've been asked to help Tom with the results of a US Congressional precinct in Colorado.
Part of my analysis is reporting the total number of votes cast, the total number of votes each candidate received, the percentage each candidate won, and the winner of the elections based on the popular vote.

For this analysis and to automate the process, I used the Python programming language, which through codes helped me find the data and results I was looking for. Also, another powerful tool I used is VSC Visual Studio Code, which is where I wrote my codes and it allows me to print the results to my command line and to the txt.file I created for this project.

The following are the results that we are going to obtain from this analysis:

1. The total number of votes cast
2. A list with the names of the candidates who participated in the elections
3. The total number of votes each candidate received
4. The percentage of votes each candidate won
5. And he winner of the election based on the popular vote

Let's start!

## Election-Audit Results:
After extensive coding, we have obtained the results from this electoral audit.
Votes were collected through mail-in ballots, punch cards, and direct recording electronic (DRE), and according to our results, the total number of votes cast was 369,711.

The counties that participated in the election are: Arapahoe, Denver and Jefferson. The following image contains the results based on the total number of votes per county, the percentage each county won and the name of the county in which the most votes were cast

![](county_results.png)

Now, I'm going to walk you through the results that each candidate got based on the total number of votes per candidate and the percentage each candidate got. There were three candidates who participated in these elections: Charles Casper Stockham, Diana DeGette and Raymon Anthony Doane.

These are the results:

![](candidate_elections.png)

### And the winner is…

Candidate Diana DeGette, won the election. She received 272,892 votes, which means that she got 73.8% of the total votes. We can clearly see that she was the candidate with the most acceptance of these elections. Second place went to Charles Casper Stockham and third place to Raymon Anthony Doane.
We now know how the total number of votes is divided by county. As you can see, 306,055 votes of the total 369,711 votes came from Denver County, which is 82.8% of the total votes. As a data analyst, i would advise the campaign team staff using all promotional budget in Denver County.

You win Denver, you win the election!

![](winner_results.png)

## Summary

After having obtained the results of these elections, we can see the importance of getting relevant data for this type of analysis.

The code we have used includes three important points: the names of the candidates, the total percentage of votes obtained, and the number of votes each candidate received.
We also aggregate the same data, but by county. This addition allows us to project a detailed and exact result, which we can take advantage of to clearly understand the final result. The code that we used in this analysis can also be used for other local elections.

### Resources

Data Source: election_results.csv
Software: Python 3.7.6, Visual Studio Code 1.71.2