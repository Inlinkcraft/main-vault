---
name: Matrice
type: Matière
---
#MAT-2930

Une matrice est une regroupement de [[Vecteur|vecteur]] dans le but de produire une grille a plusieurs dimension.

### Représentation matriciel d'une équation linéaire
---
Pour représenter une équation linéaire de la forme $a_{1}x_{1} + a_{2}x_{2} +  \dots+ a_{n}x_{n} = b$ à la forme matriciel on utilise:
$$A\vec{x} = \vec{b}$$

- $A$ est la matrice des coefficient
    - 1 ligne de la matrice : 1 équation
    - 1 colonne : 1 variable ($x_n$)
- $\vec{x}$ est le vecteur des inconnue
- $\vec{b}$ est le vecteur des connue

>[!Note]- Version developer
>$$
>\left[ 
>\array
>{
>a_{11} & a_{12} & \dots & a_{1n} \\
>a_{21} & a_{22} & \dots & a_{2n} \\
>\vdots & \vdots & \ddots & \vdots \\
>a_{m1} & a_{m2} & \dots & a_{mn} \\
>}
>\right]
>\left[ 
>\array
>{
>x_{1} \\
>x_{2} \\
>\vdots \\
>x_{n} \\
>}
>\right]
>=
>\left[ 
>\array
>{
>b_{1} \\
>b_{2} \\
>\vdots \\
>b_{m} \\
>}
>\right]
>$$

>[!info]
> Une équation linéaire peut avoir $\infty, 1 \ \text{ou} \ 0$ solution possible

### Matrice augmenté
---
Une matrice augmenté est une représentation simplifier d'une [[Vecteur#Combinaison Linéaire|combinaison linéaire]].

$$\left[ 
\begin{array}{cccc|c}
a_{11} & a_{12} & \dots & a_{1n} & b_1 \\
a_{21} & a_{22} & \dots & a_{2n} & b_2\\
\vdots & \vdots & \ddots & \vdots & \vdots \\
a_{m1} & a_{m2} & \dots & a_{mn} & b_m\\ 
\end{array}
\right]$$

> [!Info]
> $\vec{x}$ : est sous-entendue dans la matrice

> [!Info]
> Lorsqu'on parle d'un rang d'une matrice nous faisons le compte du nombre de ligne qui n'est pas égale à zero