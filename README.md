j'ai trouvé cette initiation à Git et GitHub très intéressante : 

https://openclassrooms.com/courses/gerer-son-code-avec-git-et-github

ceci n'est pas mal non plus : 
https://www.christopheducamp.com/2013/12/15/github-pour-nuls-partie-1/

Mode opératoire pour créer un nouveau commit dans le terminal :

Dans votre dossier "git", apportez les modifications souhaitées (exemple ici, ajouter dans le README ce mode op).
dans le terminal, la commande 
	git status 
vous indiquera qu'un fichier a été modifié mais n'a pas été "commit" :
	modified:   README.md (apparaitra en rouge)
comme votre fichier a déjà été indéxé dans git, vous avez juste à l'ajouter au commit avec la commande : 
	git commit -a -m "description des modifications apportées"
Git status vous indiquera alors :
	nothing to commit, working directory clean
cela signifie qu'aucun fichier modifié n'est à commit, votre dossier est "clean" !
maintenant, pour pusher vos modifications vers votre dépot GitHub correspondant, entrez simplement la commande :
	git push origin master
