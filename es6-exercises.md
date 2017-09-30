# formation-react
Un ensemble d'exercice pour une formation React

##Classes

# Créer une classe User

- Créer la classe avec son constructeur.

```
class User {
  constructor(firstname, lastname) {
    this.firstname = firstname;
    this.lastname = lastname;
  }
}
```

- Créer la méthode `welcome` pour dire bonjour à votre utilisateur !

```
class User {
  constructor(firstname, lastname) {
    this.firstname = firstname;
    this.lastname = lastname;
  }
  
  welcome() {
    console.log('Welcome ' + this.firstname + ' ' + this.lastname; 
  }
}
```
