# demo 02-CICD

## Pour lancer le projet démo

```yml
# Installation des Node
npm i
npm run test
npm start


## Mise en place d'un action CI/CD
- Créer le repertoire `.github/worflows`
- Dans celui-ci, créer une fichierr `<action-name>.yaml`
- Dans le fichier "workflow" définir :
  - le nom du workflows
  - les déclancheurs
  - Les jobs 