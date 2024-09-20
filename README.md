Algorithm_comptePhrase est un algorithme qui lit une phrase caractère par caractère afin d’afficher le nombre de caractères, nombre de mots et le nombre de voyelles.
Dans l’agorithm_comptePhrase nous avons déclaré six (06) variables d’on trois (03) compteurs.

DEBUT
Les compteurs num1 (qui compte le nombre de caractere) et num3 (qui compte le nombre de voyelle) sont initialisés à zero (0), le compteur num2 (qui compte le mot nombre de mot) est initialisé à un (01).
L’utilisateur entre les caractères de la phrase à saisir et dans la boucle Repeat l’agorithm_comptePhrase :
Répéter les instructions
-	Lire le caractère entré par l’utilisateur 
La phrase reçoit chaque caractère lu (phrase := phrase + caractère)
Incrémente le nombre de caractère (num1 : = num1 + 1)
-	Si le caractère est une voyelle il incrémente le nombre de voyelle (num3 := num3 + 1) fin si.
-	Si le caractère est une espace, il incrémente le nombre de mot (num2 := num2 + 1) fin si.
Jusqu’a (caractère soit égal à un point (caracter := ‘.’ ) 
Fin.
Afficher la phrase
Afficher le nombre de caractère
Afficher le nombre de mot
Afficher le nombre de voyelle
