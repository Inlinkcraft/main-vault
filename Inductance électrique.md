---
name: Inductance électrique
type: Matière
---
Objet ou [[Composante électrique|composante]] s'oppose au changement de courant.

## Caractéristique de l'inductance
---
#### Symbole:
```tikz
\usepackage{circuitikz}
\begin{document}
\begin{circuitikz}[american]
\draw (0,0) to[L, l=$I$, v=$V$] (3,0); 
\end{circuitikz} 
\end{document} 
```
#### unité:
Henri: ($H$)
#### Inductance
L'inductance d'un condensateur est décrite par l'équation suivante:
$$L=\frac{\mu N^{2}A}{h} \qquad N \varphi = L\, i$$

## Lois de Faraday
---
L'équation qui décrit une inductance et qui mets en relation le [[Courant électrique|courant]] et la [[Tension électrique|tension]].
$$v = L\frac{di}{dt}$$
^GEL-1000-EQ

## Puissance en inductance
---
La puissance d'un inductance peut se calculer comme suit:
$$p = v \cdot i$$
^GEL-1000-EQ

## Travail en inductance
---
Le travail d'un inductance peut ce calculer comme suit:
$$w=\frac{1}{2}L \, i^2$$
^GEL-1000-EQ