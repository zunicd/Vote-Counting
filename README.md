# Vote Counting - PyPoll

### Objective

The Python script *`main.py`* analyzes the votes from the dataset *Resources/election_data.csv* and calculates each of the following:

- The total number of votes cast
- A complete list of candidates who received votes
- he percentage of votes each candidate won

- The total number of votes each candidate won

- The winner of the election based on popular vote



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



### Tools / Techniques Used:

- Python

### About Data

The dataset *Resources/election_data.csv* contains a set of poll data. 

- **Number of records:**	3,521,001
- **Columns**:
  - Voter ID
  - County
  - Candidate

**NOTE:** The file *Resources/election_data.csv* is 68.26 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB and because of that I zipped the file. Before running the script, the file should be unzipped.