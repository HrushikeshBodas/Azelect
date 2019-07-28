# Azelect
Repo for Codefundo Project 

# The Idea
To implement a blockchain based voting application, where the voters will cast their vote for the election

It is assumed that the voter has authenticated. The application generates a unique token based on the voter ID and the time of vote, which is registered as part of the vote.

Each block of the blockchain contains the token, and the vote cast. 

# How will this help?
- This implementation allows the voter to check that the vote he casted was indeed made by him.
- Counting of votes becomes easier, as the vote which is on each block has to be checked.
- Post election scrutiny is possible, as every vote cast is preserved in the blockchain.
