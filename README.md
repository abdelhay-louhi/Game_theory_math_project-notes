
# Math project

## Algorithms used in game theory:

### For cooperative games:
#### Shapley Value:
The Shapley value is a widely used solution concept that distributes the total value of the coalition  
among its members based on their marginal contributions to all possible coalitions.  
The Shapley value is calculated by considering all possible orders in which players can join a coalition  
and averaging the marginal contributions over all possible orders.
#### Core:
The core is a set of payoff allocations where no subset of players can improve their situation by forming a new coalition.
The core is a solution concept that reflects stability in the sense that no subgroup has an incentive  
to break away and form a coalition on their own.


### For non-cooperative games:
#### Best Response Dynamics:
In a best response dynamic, each player repeatedly adjusts their strategy to improve  
their own payoff given the current strategies of the other players. The process continues until no player 
has an incentive to unilaterally deviate from their current strategy. This might converge to a Nash equilibrium.
#### Mixed Strategy Nash Equilibrium:
In games with mixed strategies (where players randomize over different strategies with certain probabilities),  
finding a Nash equilibrium involves solving a system of equations or inequalities to determine  
the optimal probabilities for each player. This is often done using linear programming techniques.

## notes:
- In non Cooperative game each player choose his strategy independently of the other players strategies but the player
could cooperate with the others to maximize its payoff and they will end where each player strategy is the best response  
to the other players strategies that's what we call Nash equilibrium. So determinate 
Nash equilibrium we could use Lemke Howson Algorithm.

- In game theory, a cooperative game (or coalitional game) is a game with competition between groups of players   
("coalitions") due to the possibility of external enforcement of cooperative behavior. Those are opposed to 
non-cooperative games in which there is either no possibility to forge alliances or all agreements need to be 
self-enforcing.
In cooperative games, the focus is on the stability and fairness of outcomes achieved through cooperation and 
coordination. Instead of Nash equilibrium, cooperative game theory often employs solution concepts such as the core, the 
Shapley value, and the nucleolus to evaluate the outcomes of cooperative games.-

- The idea is to find solutions that take into account the individual contribution of each player to the coalition. The 
Shapley value assigns each player a value that represents their average marginal contribution across all possible 
coalitions. It is calculated by considering all possible permutations of players and measuring each player's marginal 
contribution at each step of the coalition formation process. The Shapley value (ϕiϕi​) for a player ii is computed by 
averaging their marginal contribution over all possible coalitions: ϕi=1N!∑π∈ΠNMarginal Contribution of i in coalition 
πϕi​=N!1​∑π∈ΠN​​Marginal Contribution of i in coalition π Here, NN is the total number of players, and ΠNΠN​ denotes the 
set of all possible permutations of players.

