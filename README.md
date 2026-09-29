Analyse du profil des entreprises qui génèrent de l'emploi au Congo-Brazzaville
📌 Présentation du projet

Ce projet consiste à analyser le profil des entreprises créées au Congo-Brazzaville afin d'étudier leurs caractéristiques et leur capacité à générer de l'emploi.

L'analyse sera réalisée à partir du fichier entreprise.csv, en utilisant principalement Python, Pandas, SQL et Matplotlib, avec Google Colab pour les travaux d'analyse.

L'objectif est d'explorer les données, de produire des indicateurs pertinents, d'identifier les caractéristiques des entreprises associées à la création d'emplois et de présenter les résultats sous forme de statistiques et de visualisations.

🎯 Objectifs

Explorer et comprendre le jeu de données ;

Nettoyer et préparer les données ;

Réaliser des analyses avec SQL et Pandas ;

Calculer les indicateurs nécessaires ;

Créer des visualisations avec Matplotlib ;

Interpréter les résultats obtenus.
🔄 Workflow GitHub de l'équipe
1. Récupérer le projet

Chaque membre clone le repository sur son ordinateur :

git clone URL_DU_REPOSITORY
cd analyse-entreprises-emploi-congo

2. Vérifier les branches
git branch -a


Chaque membre travaille uniquement sur la branche qui lui a été attribuée.

Exemple :

git checkout feature/analyse-sql


ou :

git switch feature/analyse-sql

3. Travailler sur sa branche

Le membre réalise son travail dans sa branche :

modification du code ;

notebooks Google Colab ;

requêtes SQL ;

analyses Pandas ;

visualisations ;

documentation.

4. Enregistrer son travail
git status
git add .
git commit -m "Description du travail réalisé"


Exemple :

git commit -m "Ajout des requêtes SQL sur les emplois"

5. Envoyer le travail sur GitHub

⚠️ Le membre pousse uniquement sur sa branche, jamais directement sur main.

git push origin NOM_DE_LA_BRANCHE


Exemple :

git push origin feature/analyse-sql

6. Créer une Pull Request

Sur GitHub :

Pull requests → New pull request

Sélectionner :

base: main
compare: feature/analyse-sql


Puis créer la Pull Request.

7. Review

Le responsable du repository vérifie :

le code ;

les résultats ;

les requêtes SQL ;

les analyses ;

les graphiques ;

la qualité des fichiers ;

l'absence de données sensibles.

Si une correction est nécessaire, le membre effectue les modifications sur sa branche et fait un nouveau push.

La Pull Request est automatiquement mise à jour.

8. Validation et merge

Lorsque le travail est validé :

Pull Request
     ↓
Review
     ↓
Approve
     ↓
Squash and merge
     ↓
main


Le membre ne fusionne pas lui-même son travail dans main, sauf si l'organisation de l'équipe en décide autrement.

⚠️ Règles importantes

❌ Ne jamais travailler directement sur main.

❌ Ne jamais faire git push origin main.

✅ Chaque membre travaille sur sa branche.

✅ Faire des commits réguliers et explicites.

✅ Utiliser une Pull Request pour intégrer le travail dans main.

✅ Attendre la review avant le merge.

✅ Ne jamais publier de données confidentielles ou sensibles.

✅ Avant de commencer un nouveau travail, récupérer les dernières modifications de main.
