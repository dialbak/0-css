sass c'est un language qui ressemble a du css 
et vu que le navigateur ne comprend pas le sass
on utilise le package npm node-sass pour le compiler en css 

il faut ajouter ensuite une commande dans la package.json pour pouvoir utiliser la commande

 "sass": "node-sass -w scss -o css" 

Sa va watch tous les fichiers dans le dossier sass et ça va les compiler et les mettre en output dans le dossier css 