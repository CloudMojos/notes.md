# CS50 AI 
> Notes per week by Joshuel Simbulan (https://github.com/CloudMojos)
## Week 0
## Project 0
## Lecture 0: Search 
(Start - 07/18/23) 
(End - 07/19/23) 
(Actual Start - 07/18/23)
(Actual End - 07/22/23)
### AI
- Some rational decision made by computers
- Continuously developed to solve more complex problems
### agent
- entity that perceives and acts on environment
### state
- some configuration of agent and its environment
### initial state
- state where the agent begins
### actions
- choices that can be made in a state
- can be defined as function  Actions(s)
### transition model
- description of what state results from current state
- can be defined as function Result(s, a)
### state space
- set of all states reachable from initial state
- mukha siyang multiverse
### goal test
- way to determine whether a given state is a goal state
### path cost
- numerical cost associated with a given path
### search problems
 - initial state
 - actions
 - transition model
 - goal test
 - path cost function
### optimal solution
- a solution with the lowest path cost
### node
- a data structure that keeps track of
  - a state
  - a parent (node that generated current node)
  - an action (action applied to parent to get node)
  - a path cost (from inital state to node) parang total counter
### frontier
- next states na di pa visited
### Approach to solving search problems
- start with frontier that contains only initial state
- start with empty explored step
- repeat:
  - if the frontier is empty then no sol
  - remove a node from the frontier
  - if node contains goal, return sol
  - else
      - expand node, add resulting nodes to the frontier
### bfs
 - uses queue
 - more memory
 - always optimized???
### dfs
 - uses stack
 - less memory
 - not always optimized
### gbfs
 - more *intelligent*
 - ~~girl best friends~~ greedy best-first search
 -  uses heuristic function
    - heuristic means estimating
    - one example is manhattan distance (yung sa maze, per tile na dinadaanan may distance value from the goal, regardless of walls and obstacles)
### A* search
- uses heuristic function && step cost
- more memory
- still not always optimized but higher chance to find optimized path
### adverserial search problems
- 2 players
- deterministic
### minimax
- 2 players, min player and max player
- supposed to be recursive
- uses utility in terminal state that recurse up to current state
- uses a lot of space and time depending on the number of states
### alpha-beta pruning
- optimization for minimax
- instead of considering all states, yung mga meaningful na lang cinoconsider.
### depth-limited minimax
- example problem ng minimax ay yung chess. sobrang daming states di kayang ma-search lahat
- it is what the title says, depth limited siya para.
- evaluation function is used. kasi di ba sa minimax need nung terminal state para sa utility. pano kung malayo pa sa terminal state, need pa rin ng utility nung current state.

## Week 1
## Project 1
## Lecture 1: Knowledge
(Start - 07/22/23) 
(End - 07/22/23) 
(Actual Start - 07/22/23)
(Actual End - )
### Knowledge
- stored information
### knowledge-based agents
- agents that reason by operating on internal representations of knowledge
- parang dun sa propositional logic
### sentence
- iba ang kahulugan sa ai sa natural language
- an assertion about the world in a knowledge representation language
### propositional logic
- logic of proposition
- proposition symbols
 - P
 - Q
 - R
- logic connectives
 - not
 - and
 - or
 - implication
 - biconditional
### knowledge base
- a set of sentences known by a knowledge-based agent
- entailment
 - alpha entails beta (may symbol dapat yan pero yan yung english)
- inference
 - deriving new sentence from existing sentences
### knowledge engineering
- take a problem and how to distill it down to a knowledge understandable by the computer
- examples of knowledge engineering problem:
  - [clue](https://en.wikipedia.org/wiki/Cluedo) 
 
## Week 2
## Project 2
## Lecture 2: Uncertainty
(Start - 07/23/23) 
(End - 07/23/23) 
(Actual Start - )
(Actual End - )

### Week 3
### Project 3
### Lecture 3: Optimization
(Start - ) 
(End - ) 
(Actual Start - )
(Actual End - )

### Week 4
### Project 4
### Lecture 4: Learning
(Start - ) 
(End - ) 
(Actual Start - )
(Actual End - )

### Week 5
### Project 5
### Lecture 5: Neural Networks
(Start - ) 
(End - ) 
(Actual Start - )
(Actual End - )

### Week 6
### Project 6
### Lecture 6: Language
(Start - ) 
(End - ) 
(Actual Start - )
(Actual End - )
