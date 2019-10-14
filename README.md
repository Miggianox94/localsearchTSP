# LocalSearch-TSP

This is an application of a Local Search algorithm over a real problem modeled as a TSP instance.
You can find the problem details on the (italian)presentation file (Presentazione.pptx).

### Usage
```sh
graphList = [(10,5), (15,8), (19,3)]
```
graphList are the test cases that will be done.
(<number_of_total_nodes>,<number_of_requests>)

### Results interpretation
The execution will create a file for each test instance.
In each file you will find these results:
 - initalSolution:DoubleSpanningTree + SPT:Dijkstra
 - initalSolution:DoubleSpanningTree + SPT:BellmanFordMoore
 - initalSolution:GreedyHamiltonianAlgo + SPT:Dijkstra
 - initalSolution:GreedyHamiltonianAlgo + SPT:BellmanFordMoore

The following metrics are recorded:
 - inital solution cost
 - time of test execution
 - final solution cost and solution edge list
