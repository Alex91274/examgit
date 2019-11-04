git branch dev = crée la branche dev
git branch = affiche toutes les branches
git chechout branche = se deplacer sur la branche donnée
git checkout -b branche = crée la branche et se déplace dessus
git branch -d branche = supprime la branche (sauf si elle n'est pas propre car modifications présentes)
git merge branche = ajoute les modif de la branche donnée a celle sur laquelle on est
git branch --no-merged = affiche les branches non mergées
git stash = remise les modifications non commitées

git push origin master =  publie la branche master dans le depot sur le serveur origin

git remote = liste depots distants
git remote add = ajoute depot distant
git remote rm nom = renomme le depot en "nom" (rm peut etre dit rename)
git fetch origin = recupere la branche origin sans la fusionner
git remote show branche = donne les infos sur la branche 