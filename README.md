# CS300-Data-Structure-Algorithm-Project-
Advertising Assistance Program - Code Project

The focus of the problems in the projects for this course was to work on information extracted from a municipal government data feed containing bids submitted for auction of property. The data set was provided in two comma-separated files:
1.	eBid_Monthly_Sales.csv (larger set of 12,023 bids)
2.	eBid_Monthly_Sales_Dec_2016.csv (smaller set of 76 bids)

My first approach was to explore the sorting algorithms then analyze the data sets that were provided as input. I then explored all the possible methods by which the data could be stored. I then thought of all the possible operations I might perform on my data and what kind of time and space complexity each data structure gives me. As per the requirements I was then able to choose the appropriate data structure.

In regards to roadblocks, one seemingly major obstacle I encountered was failing to consider variables that would help in management of the list of bids which typically should be declared by either struct keyword within main() function, or by declaring the variable at the time of defining the structure. E.g., use the structure’s name as a type and declare my variable from it. I did not do this until later when I reread the requirements/tasks. Another obstacle I encountered was failing to make sure to check for key collisions and using the chaining technique with a linked list to store the additional bids. I was sure to implement the print logic, which was pretty straightforward, but then I was a bit confused on how to proceed with iterating/the (for, while) loop. Though these were not as difficult in terms of understanding the logic, they were a bit challenging to implement at the beginning and as I now know, my approach/solution to these obstacles was to go back and reread the requirements/tasks, as well as taking breaks. Stepping away for a while and/or engaging in some type of relaxing activity was extremely helpful. 

Note:
Invoking a selection sort and reporting timing result was interestingly not as challenging because it required Initializing a timer variable before loading bids, completing the method call to load the bids, and then calculating elapsed time and display result. Important to note that calculation of elapse time considers current clock ticks minus starting clock ticks.

My knowledge has exponentially expanded thanks to being able to understand the time and space complexity different data structures provide and ways by which (scenarios) one might want to implement them. 

Through these projects, my way of writing programs has changed to where I now understand that it is key to optimize for the reader of the code, not the writer as code is read more than it is written. I now know how important it is to initiate default values, use design patterns, process flowcharts, start with pseudocode as much as possible, separate code, code in small blocks, use small files and so many other tips and tricks on how to write programs that are maintainable, readable, and adaptable.  

Kind regards,

Denis.

