# Projet indépendant pour la classe de français

***

Mon but est de faire une application pour mon projet de cours de français, à déterminer.
Ce n'est pas définitif, mais j'ai quelques idées:
+ Roman visuel français
+ Web Scraper qui vous indique si un mot est féminin ou masculin
+ Une sorte de jeu français? Je ne sais pas
+ Règles grammaticales françaises application "feuille de triche"

***

Je ne sais pas si l'application sera programmée en anglais (peut-être Phaser.js?) Ou en français (Linotte semble intéressante)
[Lien vers la documentation Linotte](http://langagelinotte.free.fr/wordpress/)

***
Voici un exemple de code:
``` linotte
/*
Cliquez sur le bouton LIRE pour exécuter ce programme très simple
*/
principale :
	// Les variables doivent être déclarées avant le mot clé "début" :
	prénom est un texte
	âge & boucle est un nombre
	début
		affiche "Bonjour ! Quel est ton prénom ?"
		demande prénom
		affiche "Bravo " + prénom + ", tu viens de lire ton premier livre Linotte !"		
		// exemple d'utilisation d'une condition :
		affiche "Quel âge as-tu ?"
		demande âge
		si âge <= 18 lis
			affiche "Tu es bien jeune avec tes " + âge + " années !"
			affiche "Mais, tu iras loin dans la programmation !"
		ferme
		sinon lis
			affiche "Tu fais bien plus jeune que tes " + âge + " années !"
			affiche "Avec Linotte, la programmation ne sera plus un secret pour toi !"
		ferme
		attends 2 secondes
		// exemple d'une boucle :
		affiche "En tout cas, moi, je sais compter jusqu'à dix !"
		pour boucle de 1 à 10 affiche boucle
		affiche "à bientôt !"
```
