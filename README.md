# Sorting-Algorithms
This was a university assignmnet set during an "Artificial Inteligence" module. 
A set of 3 programs were to be developed in Python using sorting algorithms to sort a strip of random colours into an organised 
order.

The following was the assignment:

“Welcome! You’re our new employee, right? You should already know that our company specialises in software for editing and 
managing large collections of photographs. Some of our valued customers want to be able to browse their photograph collection in a 
visually pleasing fashion with similar coloured photographs following each other. We are not really sure what that means but you 
can interpret that as having some ordering on the dominant colour of consecutive photographs. You have a month to prototype some 
ideas and report your results. 

Colours used in computer graphics are based on a particular model.  The model you pick depends on the range of colours you need in
a graphic and whether it is going to be output to print media or to screen. There are various colour models available. Some 
examples are:  Black & White, Grayscale, RGB (Red, Green and Blue), CMYK (Cyan, Magenta, Yellow and Black),  and HSB (Hue, 
Saturation & Brightness).

In this assignment, we will consider the RGB (Links to an external site.) model. Red, green, and blue can be combined in various
proportions to obtain any colour in the visible spectrum.  In our representation R, G, B can each range from 0 to 1. Where 0 
indicates absence and 1 full intensity. 
You have given 3  datasets with increasing size to support your implementation and testing:
1. 10 Colours (col10.txt)
2. 100 Colours (col100.txt)
3. 500 Colours (col500.txt)
The files contain rows of three floating-point values. Each row represents a colour by its red, green, blue coordinates. The 
first uncommented line is the number of colours.

To solve this problem, your implementation should encode a candidate solution as an ordering of indices, not as an ordering of 
the colours themselves. To clarify this, let us assume that your dataset has 5 colours (each colour represented with its RGB 
coordinates) and it is stored in a list called c.  An ordering of the colours (i.e a candidate solution to your problem) should 
be encoded as a list of indices of length 5, where each element in the list is an index in the c list. 
For example,  a solution encoded as e s = [1, 0, 2, 4, 3], represents the following ordering of colours c[1] c[0] c[2] c[4] c[3]. 

Your task is to provide a more aesthetically pleasing ordering of a list of colours. To complete your task, you are asked to 
implement 3 different algorithms. 
1. Multi-start hill-climbing algorithm
2. Clustering-based algorithm
3. Algorithm of your choice

