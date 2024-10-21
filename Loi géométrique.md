---
name: Loi géométrique
type: Matière
---
#STT-2920 

La loi géométrique est la une suite de [[Loi de Bernoulli|lois de Bernoulli]] jusqu'à obtenir le premier succès

$$X \sim \text{Géométrique}(p) \qquad X \sim \text{G}(p)$$

> [!Info]
> $X$: Le nombre d'épreuve avant le premier succès

### Definition
---
###### [[Fonction de masse]]:
$$p_{X}(k) = \mathbb{P}[X = k] = 
\begin{cases}
(1-p)^{k-1}p & \text{si } k \in \{0, 1, 2, \dots, n\} \\
0 & \text{si non}
\end{cases}
$$

###### [[Espérance]]:
$$\mathbb{E}[X] = \frac{1}{p}$$

###### [[Fonction de répartition]]:
$$F(x) = \begin{cases}
0 & \text{si } x \le 0 \\
1-(1-p)^{\lfloor x \rfloor} & \text{si } x > 0
\end{cases}
$$