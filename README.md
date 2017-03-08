# CIDRSimilarityExercise
I was originally programming this exercise in Java, but switched to R for several reasons. The first was the time constraint; I was not able to work on this for the past two weeks, so I wanted to get it out as soon as possible. The second was the fact that R is vectorized, allowing me to minimize looping with the "apply" set of functions. The third reason was that I am very good at parsing strings in R, and I realized I would need that skillset for this project. Lastly, I wanted to take advantage of the data visualization tools and packages in R.

However,I am more than willing to do work in Java. I taught myself a considerable amount of Java over the weekend for this project, and that knowledge isn't going away.

I chose to use an upper triangular matrix to represent the data because the matrix is symmetrical, so only half was needed to display the data. 

0 means no relationship
1 means adjacent
2 means intersecting
3 means contained

In the test text file data, each line is a CIDR block. These were all randomly generated using the fakedata() function in my code.
