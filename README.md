# Software-Testing-and-Maintenance
Software testing and maintenance play a critical role in ensuring the quality, and thus the success, of a software product. Software testing is the single most widely used approach to detecting software bugs, and often consumes more than 50% of the cost of software development. Software maintenance is key to provide continuity of service, and is mainly concerned with how to control and manage software changes and evolution after the major features are released.

This course covered the fundamental concepts, principles, methods, and techniques for performing effective software testing and maintenance. Topics covered include the notion of test adequacy, graph-based coverage criteria, control flow-based testing, data flow-based testing, combinatorial testing, regression testing, configuration management and software refactoring.

In this repository, I have attached my homeowrk assignments and the final project for this class. 

## Homeworks
The homeworks were on different topics like definitions, theory, pairwise testing, node coverage, edge coverage, test paths, du-paths, reachability, infection, propagation, etc.

## Project
For the project, I was provided with a java code which had about 15 bugs in it. To fix these bugs, we had to first understand the flow fo the code by making Control Flow Graphs. Once this was done, I had to form all the possible test path that can be taken in the program to understand where it could go wrong. For each test case, I needed to figure out input values, actual output values, and output values from the code.

After the testing plan was in place, I had to write test functions for java using JUnit for each of those functions. Then I had to put these test values in JUnit and see the output value by the program, and compare it to the actual output value. If the actual output and the output received by program were different, then this meant that there was a bug.

Once I knew the functions that has the bug, I had to find the lines that were causing these faults and errors. After finding the fault, I had to find the code that would give us the desired output. Then this new code went in to Junit testing again to see everything worked. Once we received desired output for all cases, all the bugs were removed from the given code. 
