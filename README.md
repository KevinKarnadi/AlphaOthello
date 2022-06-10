## About

This is an Othello AI that I created for the final project of my Introduction to Programming II class (Spring 2021).

## Description

### Implementation

This AI can play the board game Othello by reading the current board and outputting the next move.<br/>
It utilizes the MiniMax algorithm and Alpha-Beta pruning in order to determine the best choice for the next move.

- #### MiniMax Algorithm

  This algorithm will try to look forward for more steps and simulate how the opponent thinks in order to make the best choice with least risk
  
  - ##### Pseudocode:
  
    ![image](https://user-images.githubusercontent.com/86511372/173017529-2f9f4ac7-c391-44ea-8823-fc934f7fe349.png)
  
  - ##### Example:
  
    ![image](https://user-images.githubusercontent.com/86511372/173017724-d1e32ae8-839a-4ae4-825e-9628aee3988f.png)
 
<br/>

- #### Alpha-Beta Pruning
  
  Optimization of the MiniMax algorithm by eliminating branches (decisions) that are not necessary
  
  Alpha: Max. score that the player is assured of in the current search process<br/>
  Beta: Min. score that the opponent is assured of in the current search process<br/>
  If Alpha >= Beta on a player node, or Beta <= Alpha on an opponent node, we can stop to search on this branch
  
  - ##### Pseudocode:
  
    ![image](https://user-images.githubusercontent.com/86511372/173018493-5f394244-ea0d-4ec0-b7b9-528a965a8a74.png)
<!--
<br/>

- #### Heuristic Function

### Screenshots
-->
