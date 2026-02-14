# Solutions d'Algorithmes : Snail & Suite Numérique

## 1. Snail Traversal (Spirale)
**Méthode :** Contraction de bornes.
- On définit `top`, `bottom`, `left`, `right`.
- On parcourt les quatre directions de manière cyclique.
- Après chaque direction, on réduit l'espace de jeu en incrémentant/décrémentant les bornes.
## 2. Consecutive Numbers (Chaîne consécutive)
**Méthode :** Simulation par préfixe.
- On ne sait pas si le premier nombre est 9, 99 ou 999.
- On essaie donc toutes les longueurs de départ possibles.
- Pour chaque départ, on génère la suite logique ($+1$).
- Si la suite générée "match" parfaitement la chaîne `ch`, la fonction renvoie `True`.
- **Cas particuliers :** Les zéros non significatifs sont rejetés au début de l'analyse.
