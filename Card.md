Exemple visuel 

<img width="396" height="156" alt="example_card" src="https://github.com/user-attachments/assets/1280e194-f2d2-4c5f-98e1-18bcb7c66c9a" />


## Placer vous dans components

```bash
ng generate component card
```

<br>

## html

```html
<mat-card class="example-card" appearance="outlined">
  <mat-card-header>
    <div mat-card-avatar class="example-header-image"></div>
    <mat-card-title>Titre</mat-card-title>
  </mat-card-header>
  <mat-card-content>
      <!-- Ici on place le contenu qui 
       s'aggrandira automatiquement en fonction de la taille du contenu -->
    <p>
     Je suis un contenu
    </p>
  </mat-card-content>
  <mat-card-actions>
    <!-- Ici on place les boutons -->
    <button matButton>Je suis un bouton</button>
  </mat-card-actions>
</mat-card>
```

<br>

## css


```css
.example-card {
  max-width: 400px;
}
```

<br>

## ts

```ts
import {MatCardModule} from '@angular/material/card';

imports: [MatCardModule],

```

## app.html

```html
<app-nomdelaClass></app-nomdelaClass>
```

<br>

## app.ts

```ts

import { nomdelaClasse } from 'Le chemin';
imports: [Card],

```
