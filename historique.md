git log -x = affiche les x derniers commit
git log --author "x" = affiche les log des commit faits par la personne x
git log --since=x.day = affiche  les log depuis x jours
git log --before="annee-mois-jour" = affiche les logs depuis tel jour
git log fichier = affiche log du fichier donné

git blame mot = affiche les commit dans lesquels le mot est présent
git diff = affiche les changements d'un fichier depuis le dernier ajout dans git
git diff HEAD-x = voir le diff mais de x commit en arriere
git HEAD-x HEAD = voir la diff entre le dernier commit et le commit-x
git log hache1 hache2 = affiche les log entre deux commit en recup les haches avec un git commit
git diff stat = affiche les stat des changements de valeur dans un fichier

git restore = annule la modification
git restore --staged = pareil mais si git add a été fait

git reset HEAD-x = annule et revient au commit-x et garde les modifs dans le dossier
avec la commande --soft = garde les modifs dans la branche
avec la commande --hard = supprime tout (dangereux)

git checkout hache fichier = retour a l'etat initial du fichier (git init)
git revert = crée un nouveau commit pour expliquer modif et revient aux modif précédentes
