![image](https://github.com/MathisCastell/Calculatrice/assets/148212506/c85a031a-bdef-49e3-b712-bb97f4d6c54d)


Classe Calculator:

La classe Calculator est définie pour représenter la calculatrice.
Le constructeur __init__ initialise les variables nécessaires pour effectuer les calculs (phase1, phase2, final, entry, text, signe).
La méthode init réinitialise les variables de la calculatrice.
afficher_Nb met à jour la valeur affichée à l'écran avec le contenu de text.
La méthode operation examine l'opération à effectuer (+, -, *, /) en fonction du contenu de text et appelle la méthode appropriée.
Les méthodes Plus, Sous, Div, et Mult effectuent les opérations correspondantes et mettent à jour l'affichage.
Fonctions Button1 à ButtonE:

Ces fonctions sont utilisées comme gestionnaires d'événements pour les boutons numériques (de 0 à 9), le point décimal, et les opérations arithmétiques (+, -, *, /, =).
Elles modifient le texte (calculatrice.text) en conséquence et mettent à jour l'affichage.
Fenêtre Tkinter:

Une fenêtre Tkinter (fen) est créée avec une taille de 200x240 pixels, un titre "Calculatrice v1.0", une couleur de fond "SkyBlue2", et un relief "raised".
Un objet Calculator (calculatrice) est créé.
Un widget Entry (ECRAN) est utilisé pour afficher le texte de la calculatrice.
Des boutons numériques, opérations, et autres commandes sont créés à l'aide de la classe Button de Tkinter. Chaque bouton est associé à une fonction spécifique définie précédemment.
Les boutons sont disposés à l'aide de la méthode place.
Boucle principale (fen.mainloop()):

La boucle principale de Tkinter est utilisée pour surveiller les événements et maintenir l'interface utilisateur active.
Lorsque vous exécutez ce script, une petite interface graphique de calculatrice apparaît, et vous pouvez effectuer des opérations en cliquant sur les boutons. La classe Calculator gère la logique des calculs et met à jour l'interface utilisateur en conséquence. Les fonctions Button1 à ButtonE sont liées aux boutons pour réagir aux événements de clic.
