---
name: Foncteur
type: Matière
---
#GLO-2100 

Un foncteur est une [[Class|class]] qui englobe une [[Fonction|fonction]]. Cela permet d'ajouter des attribue a la [[Fonction|fonction]].

### Syntaxe
---
Pour déclarer un foncteur:
```cpp
class Foncteur {
public:
    int operator()(int a, int b)
    {
        return a < b;
    }
}
```

Il suffit d'écrasé la déclaration de l'opérateur `()`.