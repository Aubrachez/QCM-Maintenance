# /!\ IMPORTANT À LIRE /!\
# QCM-Maintenance
### Comment ça fonctionne 
* J'ai fait un QCM pour navigateur web pour le cours de maintenance.
* 4 Réponses 1 seule bonne.
* Quand tu cliques sur la bonne elle s'éclaire en vert sinon elle s'éclaire en rouge et éclair en vert la correcte.
* Les questions et les réponses ne sont pas chaque fois dans le même ordre. 
* Votre nombre de bonne et mauvaise réponses s'affiche dans la console du navigateur pour l'ouvrir suffit d'appuyer sur `Ctrl` +`Alt` +`J`
* Pour relancer le quiz il faut rafraichir la page.


## Comment l'installer sur ton ordi et l'utiliser
1) Assure toi d'avoir python sur ton ordinateur _Pour ça va dans ton terminal et tape `python -v`_
2) Crée un dossier maintenance sur ton bureau
3) Télécharge les 2 fichiers et mets les dans le dossier maintenance sur ton bureau
4) Ouvre un terminal windows
5)  Déplace toi avec la commande `cd desktop\maintenance `  dans le terminal 
   Tu devrais voir un truc du style `C:\Users\gregoire\desktop\maintenance>` 
6) Quand tu es dans le bon dossier avec le terminal tape la commande `python -m http.server` 
7) Ouvre un navigateur web et dans la barre url tape : http://localhost:8000/index.html
8) Normalement c'est bon.


## Ajouter des questions 
Dans le fichier question.json, ajouter ce code entre deux question
 `{
                "question": "Question",
                "options": ["Réponse 1", "Réponse 2", "Réponse 3", "Réponse 4"],
                "answer": "Bonne réponse"
 }, `

 
## Modifier des questions
Prendre la question dans le fichier question.json 
modifier les réponses possibles dans otpions ou modifier la bonne réponse dans answer
 `{
                "question": "Question",
                "options": ["Réponse 1", "Réponse 2", "Réponse 3", "Réponse 4"],
                "answer": "Bonne réponse"
 }, `
