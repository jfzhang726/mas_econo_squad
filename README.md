# mas_econo_squad

This is a small demonstration of building a group of collaborative agents using AutoGen framework. 

<br>

Notebook economics.ipynb demonstrates two scenarios.

### Scenario 1: A team consisting of a product manager and a developer working on coding task


### Scenario 2: More Complex Task: Retrieve and Analyse RBA (Reserve Bank of Australia) meeting minutes

The team of agents are given the link to RBA Monetary Policy meeting minutes, and are expected to predict whether interest rate will be raised in the next month or not.

The task requries both expertises in coding/data processing and in domain of economics.

A more diversed team is built:
- Planner
- Software Engineer
- Economist
- Code Executor 
- Critic

Interaction among the agents is interesting.  

For instance, during the conversation, Critic pointed out that the document is too long to fit 2000 token limit and told Sofeware Engineer to cut document into smaller pieces.



To do: 
- Design more detailed SOP (Standard Operating Procedure)