
# projet2

# Scraping Books to Scrape - Pipeline ETL Python

Ce dépôt contient une application Python développée dans le cadre du projet "Utilisez les bases de Python pour l'analyse de marché" (OpenClassrooms).  
L'objectif est d'automatiser l'extraction des données livres depuis le site fictif [Books to Scrape](https://books.toscrape.com/), site de démonstration dédié au web scraping.

**Fonctionnalités principales :**  
- Extraction des informations produit (titre, prix, catégorie, disponibilité, note, description, UPC, etc.)  
- Scraping progressif : produit unique → catégorie → catalogue complet (toutes catégories)  
- Téléchargement et stockage local des images de couverture  
- Export structuré des données au format CSV (une catégorie = un fichier)

Le projet implémente une logique **ETL** basique (Extract → Transform → Load) et utilise **requests**, **BeautifulSoup** et **Git** pour le versionnement.

**Pour exécuter :** voir la section *Installation et utilisation* ci-dessous.  
Un fichier ZIP séparé contenant les données et images générées est fourni à Sam (non inclus dans ce dépôt).

# Comment executer le code de scraping (prérequis avoir installé python et telecharger le repository projet2-main.zip)
# Etape 1

Création d'un environnement virtuel (depuis windows)
    - Extraire l'archive projet2-main.zip afin d'avoir accés au repertoire portant le nom projet2-main
    - Une fois dans ce repertoire faites un clique droit et ouvrir terminal.
    - Ecrire la commande `python -m venv projet_2`
    - Puis `projet_2\Scripts\activate` afin d'activer l'environnement virtuel.
# Etape 2
Installation des pacquets dans l'environnement virtuel permettant le fonctionnement du scripts
    - Ecrire la commande `pip install -r requirements.txt`

# Etape 3
Lancer le scripts
    - Ecrire la commande `python main.py` pour lancer l'execution du scripts 
    - Veuillez patientez jusqu'a la fin du programme.

# Etape 4
Attendre le message "Fin du scripts.Merci de consulter les fichiers CSV et le repertoire image"
    -Vous pouvez quitter la fenetre
    -Vous pouvez consulter les fichiers CSV par nom de catégories et le repertoire image contenant toutes les images.
