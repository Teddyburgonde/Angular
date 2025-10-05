## Example visuel 

<img width="152" height="45" alt="Capture d’écran 2025-10-05 à 21 40 37" src="https://github.com/user-attachments/assets/3208af46-4d15-46ef-a128-d2a1bb897a13" />

<br>

## Définition:

```bash
L’interpolation en Angular, c’est quand tu affiches la valeur d'une variable dans le HTML en l’entourant avec {{ }}.
```

<br>

## Exercice: 

- Crée une string en ts dans le fichier app.ts.
Donne a cette string la valeur de ton prénom.

- Va dans app.html
et rajoute la valeur de ta variable déclaration dans le app.ts 
dans le '<p>'Hello'</p>'.
Bien sur tu dois utiliser l'interpolation. 








## Réponses

app.ts 

```ts
export class App {
  name:string = "John"
}
```


app.html

<br> 

```html
<h1>Hello {{name}}</h1>
```
