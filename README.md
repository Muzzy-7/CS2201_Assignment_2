# Water Jug Problem – Uninformed Search Strategies
Access the file named "Implementation_of_uninformed_strategies.py" for the code.
## Overview
This project is about the Water Jug Problem. The Water Jug Problem is a problem where we have two jugs.
One jug is 4 liters. The other jug is 3 liters.
The Water Jug Problem starts with both jugs being empty.
We want to get to a point where one of the jugs has 2 liters of water in it.
We use these search strategies to find the solution to the Water Jug Problem.
The Water Jug Problem is an example of how to use the search strategies.

## State Representation
We represent each state of the Water Jug Problem as a pair of numbers.
The pair of numbers is (x, y).
Here x is the amount of water in one jug and y is the amount of water in the jug.
For example (0,0) means both jugs are empty.
(4,0) Means one jug is full and the other jug is empty.
(1,3) Means one jug has 1 liter of water and the other jug has 3 liters of water.
Our goal is to get to a state where x's 2 or y is 2.

## Possible Operations
We can do several things to change the state of the Water Jug Problem.
We can fill one jug or the other jug.
We can empty one jug or the other jug.
We can pour water from one jug to the jug.
These actions help us get to the state.

## Search Strategies Implemented

### Breadth First Search
The Breadth First Search strategy is like looking at all the states that're one step away from the current state. Then we look at all the states that're two steps away. So on.
This strategy uses a queue to keep track of the states.
It is good because it always finds the path to the solution.
The Breadth First Search strategy is useful for the Water Jug Problem.

### Depth First Search

The Depth First Search strategy is like going down a path far as we can. Then we come back. Try a different path. This strategy uses a stack to keep track of the states.
It uses memory than the Breadth First Search strategy. It may not always find the shortest path to the solution.

### Depth Limited Search

The Depth Limited Search strategy is like the Depth First Search strategy. We only go down a path for a certain number of steps. This helps us not get stuck in a loop.
The Depth Limited Search strategy is useful when we know about how steps it will take to get to the solution.

### Iterative Deepening Depth First Search

The Iterative Deepening Depth First Search strategy is like a mix of the Breadth First Search and Depth First Search strategies. We start by looking at all the states that're one step away. 
Then we look at all the states that're two steps away. So on.
We use a stack to keep track of the states. This strategy is good because it finds the path to the solution.It uses less memory than the Breadth First Search strategy.

## Performance Comparison

| Algorithm | Memory Usage | Optimal Solution | Speed | Characteristics |

   BFS      |     High     |      Yes         |   Slower  |    Explores level by level      |

| DFS Low | Not guaranteed | Faster | Goes deep before backtracking |

| DLS | Low | Not guaranteed Moderate | Depth is restricted |

| IDDFS Moderate | Yes Efficient | Combines BFS and DFS advantages |

### Observations

* The Breadth First Search strategy is good for the Water Jug Problem because it always finds the path.
* The Depth First Search strategy uses memory.
* The Depth Limited Search strategy helps us not get stuck in a loop.
* The Iterative Deepening Depth First Search strategy is a mix of the Breadth First Search and Depth First Search strategies.

For the Water Jug Problem the Breadth First Search strategy and the Iterative Deepening Depth First Search strategy are generally more effective.
The Water Jug Problem is solved using these search strategies. The search strategies are useful, for the Water Jug Problem. 
We use the Water Jug Problem to test the search strategies.

# Turing Test and Captcha architecture
## Everything is in the file named "Turing_test_and_CAPTCHA"
