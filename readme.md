# demo 02-CICD

## Pour lancer le projet démo

```yml
# Installation des Node
npm i
# Tester le code
npm run test

# Build le projet TS → JS
npm run build

# Lancer le projet buildé
npm run start
```


## Mise en place d'un action CI/CD
- Créer le repertoire `.github/worflows`
- Dans celui-ci, créer une fichierr `<action-name>.yaml`
- Dans le fichier "workflow" définir :
  - le nom du workflows
  - les déclancheurs
  - Les jobs 