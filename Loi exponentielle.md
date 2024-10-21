---
name: Loi exponentielle
type: Matière
---
#STT-2920 

La [[Loi exponentielle]] est l'équivalent continue de la [[Loi géométrique|loi géométrique]].

$$X \sim \text{Exponentiel}(\lambda) \qquad X \sim \mathcal{E}(\lambda)$$

> [!Info]
> $X$: suit une [[Loi géométrique|loi géométrique]] continue

### Definition
---
###### [[Fonction de densité]]:
$$f_{X}(k) = \mathbb{P}[X = k] = 
\begin{cases}
\lambda e^{-\lambda x} & \text{si } x > 0 \\
0 & \text{sinon}
\end{cases}
$$

###### [[Espérance]]:
$$\mathbb{E}[X] = \frac{1}{\lambda}$$

###### [[Fonction de répartition]]:
$$F(x) = \begin{cases}
0 & \text{si } x \le 0 \\
(1-e^{-\lambda t}) & \text{si } x > 0 \\
\end{cases}
$$