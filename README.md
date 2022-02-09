# CIDRSimilarityExercise

I chose to use an upper triangular matrix to represent the data because the matrix is symmetrical, so only half was needed to display the data. 

0 means no relationship
1 means adjacent
2 means intersecting
3 means contained

In the test text file data, each line is a CIDR block. These were all randomly generated using the fakedata() function in my code.

The input for the final function, pepper, is a list of blocks of IP addresses in CIDR notation in character string format. The output is the plot.

In addition to taking in a list of blocks as an input, pepper also takes in a random string as it's second argument (so as to distinguish the graphs from each other). 

An example input list would look like:

[[1]]
"234.255.255.255/16"
"123.0.23.0/8"
[[2]]
"34.19.66.120/20"
"34.11.15.42/13"
"141.32.12.15/6"

