## Comprendre un formulaire en Angular

### Exemple visuel d'un formulaire 


![formulaire](https://github.com/user-attachments/assets/3bd0d080-3be3-4ff6-97c9-0cc62835b962)



Un formulaire est toujours composé de deux éléments principaux :  

- **Un `<form>`** → c’est la partie visible à l’écran (les champs, les boutons).  
- **Un `FormGroup`** → c’est l’objet Angular qui gère ce formulaire (les valeurs, les erreurs, les validations, etc.).  

👉 Un `FormGroup` contient **un ou plusieurs `FormControl`** (chacun représentant un champ du formulaire).  

---

### Exemple : Formulaire de connexion

Structure logique :  

- FormGroup **"connection"**  
  - FormControl **"username"**  
  - FormControl **"password"**  

---

### En code :

```ts
// Ici, je crée l'objet parent (FormGroup),
je précise à TypeScript la forme qu'il doit avoir 
et je lui donne une valeur.

connection = new FormGroup({
  username: new FormControl<string | null>(null),
  password: new FormControl<string | null>(null),
});
```

