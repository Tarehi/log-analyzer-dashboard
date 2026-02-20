# log-analyzer-dashboard

Un outil léger et rapide développé en Vanilla JavaScript (sans framework) pour l'analyse, le filtrage et la supervision de fichiers de logs bruts.

##  Contexte
Développé dans le cadre de mes projets personnels pour faciliter la lecture des logs systèmes et applicatifs. Cet outil répond à un besoin d'analyse rapide sans avoir à déployer des solutions lourdes (comme la suite ELK ou Splunk).

##  Fonctionnalités
* **Parsing en temps réel** : Analyse les chaînes de caractères brutes.
* **Classification automatique** : Détection des niveaux de criticité (`CRITICAL`, `ERROR`, `WARN`, `INFO`).
* **Dashboard de supervision** : Compteurs mis à jour dynamiquement pour avoir une vue d'ensemble de la santé du système.
* **Coloration syntaxique** : Interface "Dark Mode" optimisée pour la lecture de données techniques.

## Stack Technique
* **HTML5 / CSS3** (Interface et structure)
* **Vanilla JavaScript** (Manipulation du DOM et expressions régulières)

## Utilisation
1. Ouvrez simplement le fichier `index.html` dans un navigateur web.
2. Collez vos logs bruts dans la zone de texte.
3. Cliquez sur "Analyser les Logs".
4. (Optionnel) Utilisez le bouton "Charger Exemple" pour tester le comportement de l'outil.
