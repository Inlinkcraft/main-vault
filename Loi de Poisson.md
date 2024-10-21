---
name: Loi de Poisson
type: Matière
---
#STT-2920 

Une [[Variable aléatoire|variable aléatoire]] peut suivre une loi de Poisson d'un paramètre donné $\nu$

$$X \sim \text{Poisson}(\nu) \qquad X \sim \mathcal{P}(\nu)$$

> [!Info]
> $X$: suit la loi de Poisson de moyenne $\nu$.

### Definition
---
###### [[Fonction de masse]]:
$$p_{X}(k) = \mathbb{P}[X = k] = 
\begin{cases}
e^{-\nu}\frac{\nu^{k}}{k!} & \text{si } k \in \{0, 1, 2, \dots\} \\
0 & \text{sinon}
\end{cases}
$$

###### [[Espérance]]:
$$\mathbb{E}[X] = \nu$$

###### [[Fonction de répartition]]:
#TODO 