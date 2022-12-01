# Scripts with Flags

This repo is just to show different script options when running Cypress headlessly for single spec

Install
```
yarn
```

## Run

Running without a script command
```
yarn cypress run --browser chrome --spec 'cypress/e2e/test1.cy.js' 
```

Running with a script command
```
yarn {{SCRIPT_NAME_FROM_PACKAGE.JSON}}
```
