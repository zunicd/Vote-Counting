## Vote Counting - PyPoll

The dataset *Resources/election_data.csv* contains a set of poll data. It is composed of three columns: **Voter ID**, **County**, and **Candidate**. The Python script *`main.py`* analyzes the votes and calculates each of the following:

• The total number of votes cast

• A complete list of candidates who received votes

• The percentage of votes each candidate won

• The total number of votes each candidate won

• The winner of the election based on popular vote


In addition, the script prints the analysis to the terminal and saves to a text file *election_results.txt*:

    Election Results
    -------------------------
    Total Votes: 3521001
    -------------------------
    Khan: 63.000% (2218231)
    Correy: 20.000% (704200)
    Li: 14.000% (492940)
    O'Tooley: 3.000% (105630)
    -------------------------
    Winner: Khan
    -------------------------

By default, the script uses Python lists:

    # Toggle which scripts to run (1 to run, 0 to skip)
    usingLists = 1
    usingDicts = 0

To use dictionaries, update the script:

    usingLists = 0
    usingDicts = 1

save it and rerun it.

