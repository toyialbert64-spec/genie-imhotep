# Données Génie Imhotep

Ce dossier est préparé à partir du fascicule fourni par l’utilisateur.

## Utilisation
- `REGLES.md` : section des règles des rubriques.
- `rubrics.json` : paramètres structurés pour le moteur de jeu.
- `manifest.json` : point d’entrée pour un agent/codeur.
- `CLAUDE_PROMPT.txt` : prompt court à donner à Claude.
- `*.json` : questions/réponses structurées quand l’extraction a identifié le marqueur `R :`.
- `*.md` : texte du questionnaire correspondant, conservé pour contrôle.

## Hébergement pour un agent
Placez le dossier dans un dépôt accessible par URL puis utilisez l’URL brute de `manifest.json` comme `[URL_BASE]/manifest.json`.

## Important
Le fascicule indique que le questionnaire et son contenu sont protégés. Vérifiez les droits nécessaires avant de publier publiquement la totalité des questions. Pour un dépôt public destiné uniquement au code, préférez publier les règles nécessaires au développement et conserver le corpus complet dans un emplacement autorisé.
