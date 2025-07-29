# Formulaire de candidature Axle IA

Formulaire de candidature standalone pour intégration dans Webflow.

## Configuration

Avant d'utiliser le formulaire, vous devez configurer l'intégration ClickUp :

1. **Obtenir un token ClickUp** :
   - Allez dans vos paramètres ClickUp
   - Générez un token API personnel
   - Remplacez `VOTRE_TOKEN_CLICKUP` dans le code

2. **Obtenir l'ID de la liste ClickUp** :
   - Créez une liste "Recrutement" dans ClickUp
   - Récupérez l'ID de la liste
   - Remplacez `VOTRE_LIST_ID` dans le code

## Intégration Webflow

### Option 1 : Embed Code
1. Copiez le contenu du fichier `index.html`
2. Dans Webflow, ajoutez un "Embed" element
3. Collez le code HTML complet

### Option 2 : Custom Code
1. Copiez les styles CSS dans les paramètres du projet Webflow (Head Code)
2. Créez la structure HTML avec les éléments Webflow
3. Ajoutez le JavaScript dans les paramètres du projet (Before </body> tag)

## Fonctionnalités

- ✅ Formulaire responsive
- ✅ Upload de CV (PDF, DOC, DOCX)
- ✅ Intégration ClickUp automatique
- ✅ Fallback email si erreur
- ✅ Validation des champs
- ✅ Messages de succès/erreur

## Personnalisation

Vous pouvez personnaliser :
- Les couleurs dans les variables CSS
- Les postes disponibles dans le select
- Les champs du formulaire
- Les messages de confirmation

## Support

Pour toute question : contact@axle-ia.com