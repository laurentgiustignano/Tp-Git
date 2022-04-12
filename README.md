# Premier Tp Git
Pour la mise en œuvre de Git pour votre projet, vous devez dans un premier temps vous assurer que l’utilitaire Git est installé sur votre ordinateur. Pour illustrer son utilisation, nous allons travailler sur un projet C++ avec CLion. L’avantage de CLion, c’est qu’il intègre Git dans son environnement
## Étape 1 : Créer un nouveau projet à partir du dépôt distant sur Github
Pour cela, il y a plusieurs méthodes :
* Soit directement créer un nouveau projet à partir d’un repository distant.
* Soit dans un projet vide, en choisissant « Get from Version Control » depuis le menu VSC.
* Soit avec la commande `git clone https://github.com/laurentgiustignano/Tp-Git.git`

Dans tous les cas, il faut connaitre l’URL du dépôt distant : https://github.com/laurentgiustignano/Tp-Git.git
En clonant le projet, CLion propose de recréer les paramètres de l'environnement de compilation. Une fois fait, vous pouvez executer le projet et observer l'affichage `hello world!`. 

Au niveau de l’onglet « log » de la toolbar « git », le premier commit `Début Tp-Git` apparaît et contient un projet avec un fichier source main.cpp. 

## Étape 2 : Modifier le fichier main.cpp pour effectuer un affichage d’hello world en français
Ensuite, vous réaliserez un commit en spécifiant le message : `in french`.
Observez la ligne des commits.

## Étape 3 : La classe Demonstration 
* Créer la classe dans les fichiers `.cpp` et `.h` de même nom.
* Ajouter dans un constructeur par défaut l'affichage du texte : `"Je suis le constructeur de Demonstration"`
* Créer un objet de la classe Demonstration dans `main.cpp` et tester
* Si l'affichage du nouveau texte apparait, vous pouvez faire un commit de nom : Classe Demonstration. Sinon, il faut encore corriger votre code...

## Étape 4 : On termine
* Ajouter une fonction void `affiche()` dans `Demonstration.h`
* Définir la fonction pour qu'elle affiche `"un super truc"`
* Utilisez la fonction `affiche()` avec l'objet que vous avez créé et testez
* Si l'affichage du nouveau texte apparait, vous pouvez faire un commit de nom : Fin du TP

## Conclusion
À mesure que vous développez, vous pouvez effectuer des commits pour mémoriser une étape importante de votre développement. De plus, vous pouvez revenir sur n'importe quelle étape que vous aurez enregistrée.