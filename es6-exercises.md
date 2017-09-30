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
    return 'Welcome ' + this.firstname + ' ' + this.lastname; 
  }
}
```

## Les constantes

- Créer une instance de votre classe avec const

`const user = new User('Julien', 'Liétart');`

- Dites bonjour à votre utilisateur !

`document.getElementById('root').innerHTML = user.welcome();`

## Les variables avec portée

- Créer un meilleur ami à votre utilisateur avec let

`let bestFriend = new User('Dark', 'Vador');`

- Changer de meilleur ami en redefinissant bestFriend

`bestFriend = new User('Obi wan', 'Kenobi');`
