# Comment faire? 

1. Une fois vous aurez le lien github classroom, vous acceptez l'invitation
2. Après cela, actualiser la page, normalement un lien devra apparaitre
3. Copier l'URL que vous voyez sur la page
4. Aller sur votre vsCode puis taper cette commande git ```git clone <URL>```  <br>
5. Taper ```npm init``` <br>
6. Taper ```npm install``` <br>
7. Taper ```npx cypress open``` <br>
Puis commencez à code votre "wimtimLogin.cy.js" à l'intérieur du dossier ```/cypress/e2e```

# De quoi il s’agit? 
=> Il s’agit de visiter ce site https://app.wimtim.com/ pour effectuer certains cas de test en Cypress

Quels sont les objectifs? 
- Se familiariser certaines commandes avec Cypress
- Se familiariser avec le cas réel du test e2e
- Se familiariser avec l’outil de versioning Github

# Ennoncés de l’exercice: 
1. Visiter le site https://app.wimtim.com/
2. Vérifier si l’URL affiché dans la barre d’adresse est bien https://app.wimtim.com/
3. Vérifier si le texte “Log In” est bien visible sur la page
4. Entrer ce login en utilisant la commande cypress: 
    - Email : ```cypress_sp@gmail.com```
    - mot de passe : ```oriZon#22dqshdjk``` <br>
**=> Vérifier la visibilité de ce texte en utilisant une commande cypress ```4 login attempts left, and you will have to wait for 30 minutes```** 
5. Cliquer sur le texte **Forgot password?** ensuite vérifier si l'URL affichée dans la barre d'adresse est bien ```https://app.wimtim.com/forgot-password```

# Rendu de l’exercice attendu
- Fichier cypress nommé “wimtim.cy.js” dans ```/cypress/e2e```
- Quand taper ```npx cypress open``` le fichier ```wimtim.cy.js``` s'exécute en ouvrant un navigateur
