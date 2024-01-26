
# Projet de mathématiques 

## Algorithmes utilisés en théorie des jeux:

### Les jeux coopératifs:

#### Valeur de Shapley:
La valeur de Shapley est un concept de solution largement utilisé qui distribue la valeur totale de la coalition
parmi ses membres en fonction de leurs contributions marginales à toutes les coalitions possibles.
La valeur Shapley est calculée en considérant tous les ordres possibles dans lesquels les joueurs peuvent rejoindre une coalition.
et faire la moyenne des contributions marginales sur toutes les commandes possibles.

#### noyau:
Le noyau est un ensemble d’allocations de récompenses dans lesquelles aucun sous-ensemble d’acteurs ne peut améliorer sa situation en formant une nouvelle coalition.
Le noyau est un concept de solution qui reflète la stabilité dans le sens où aucun sous-groupe n'est incité à
se séparer et former une coalition par eux-mêmes.

- En théorie des jeux, un jeu coopératif (ou jeu coalitionnel) est un jeu avec compétition entre groupes de joueurs.
(« coalitions ») en raison de la possibilité d'une application externe du comportement coopératif. Ceux-ci s'opposent à
jeux non coopératifs dans lesquels soit il n'y a aucune possibilité de forger des alliances, soit tous les accords doivent être conclus
auto-exécutoire.
Dans les jeux coopératifs, l'accent est mis sur la stabilité et l'équité des résultats obtenus grâce à la coopération et
coordination. Au lieu de l'équilibre de Nash, la théorie des jeux coopératifs utilise souvent des concepts de solution tels que le noyau, le
Valeur de Shapley et nucléole pour évaluer les résultats des jeux coopératifs.-

- L’idée est de trouver des solutions qui tiennent compte de la contribution individuelle de chaque acteur de la coalition. Le
La valeur Shapley attribue à chaque joueur une valeur qui représente sa contribution marginale moyenne sur tous les éléments possibles.
coalitions. Il est calculé en considérant toutes les permutations possibles de joueurs et en mesurant le marginal de chaque joueur.
contribution à chaque étape du processus de formation de la coalition. La valeur de Shapley (ϕiϕi​) pour un joueur ii est calculée par
faire la moyenne de leur contribution marginale sur toutes les coalitions possibles : ϕi=1N!∑π∈ΠNContribution marginale de i dans la coalition
πϕi​=N!1​∑π∈ΠN​​Contribution marginale de i dans la coalition π Ici, NN est le nombre total de joueurs, et ΠNΠN​ désigne le
ensemble de toutes les permutations possibles de joueurs.

### Les jeux non coopératifs:

#### Best Response Dynamics:
Dans une dynamique de meilleure réponse, chaque joueur ajuste à plusieurs reprises sa stratégie pour améliorer
leur propre récompense compte tenu des stratégies actuelles des autres joueurs. Le processus continue jusqu'à ce qu'aucun joueur
est incité à s’écarter unilatéralement de sa stratégie actuelle. Cela pourrait converger vers un équilibre de Nash.

#### Mixed Strategy Nash Equilibrium:
Dans les jeux à stratégies mixtes (où les joueurs choisissent aléatoirement différentes stratégies avec certaines probabilités),
trouver un équilibre de Nash implique de résoudre un système d'équations ou d'inégalités pour déterminer
les probabilités optimales pour chaque joueur. Cela se fait souvent à l'aide de techniques de programmation linéaire.

- Dans un jeu non coopératif, chaque joueur choisit sa stratégie indépendamment des stratégies des autres joueurs mais le joueur
pourrait coopérer avec les autres pour maximiser ses gains et ils se termineront là où la stratégie de chaque joueur est la meilleure réponse
pour les stratégies des autres joueurs, c'est ce que nous appelons l'équilibre de Nash. Tellement déterminé
Équilibre de Nash, nous pourrions utiliser l'algorithme de Lemke Howson.



