# Cartographie 3D des Programmes Publics 🇫🇷

Ce projet propose une visualisation interactive en 3D de 100 programmes d'intervention publique. 

L'analyse positionne chaque programme selon 3 axes (Territoire, Stratégie, Levier) et représente son budget par la taille de la bulle.

## 📂 Contenu du dépôt

* `Programmes_avec_budget_et_coordonnees_v2.csv` : Le fichier de données contenant les scores vectoriels et les estimations budgétaires.
* `Visualisation_Programmes_3D.ipynb` : Le code Python (Notebook) pour générer le graphique.

## 🚀 Comment visualiser le graphique ?

GitHub ne permet pas de manipuler la 3D directement sur la page. Pour interagir avec le cube (zoomer, tourner, cliquer sur les points), **ouvrez ce projet dans Google Colab** :

1. Cliquez sur le fichier `Visualisation_Programmes_3D.ipynb` dans la liste ci-dessus.
2. Une fois ouvert, vous verrez un bouton "Open in Colab" en haut du fichier (ou téléchargez-le pour l'ouvrir sur votre Colab).
3. **Important** : Une fois dans Colab, vous devrez importer le fichier CSV `Programmes_avec_budget_et_coordonnees_v2.csv` dans la session pour que le code fonctionne.

## 📊 Méthodologie

* **Axe X (Territoire)** : De Rural (0) à Urbain/National (10).
* **Axe Y (Stratégie)** : De Social (0) à Économique/Innovation (10).
* **Axe Z (Levier)** : De l'Ingénierie/Soft (0) à l'Investissement Capital/Hard (10).
* **Taille des points** : Proportionnelle au budget estimé du programme.
* **Croix (x)** : Indique les programmes dont le budget n'est pas chiffré précisément.
