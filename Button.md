## Exemple visuel

<img width="89" height="43" alt="example button" src="https://github.com/user-attachments/assets/2d610d3f-e783-4dd7-8f0a-d126739cb02c" />

<br>

## Créer un dossier components et placer vous a l'interieur. 



```bash
src/
├── app/
│   ├── components/
```
<br>

## Créer un button

```bash
ng generate component nomducomposant
```

<br>

## html

```bash
<button matButton="filled">
	montextesurlebouton
</button>
```

<br>

## ts 

```bash
import { MatButtonModule } from '@angular/material/button';

imports: [MatButtonModule],
```
<br>

## Dans app.html 

```bash
<nomdu-selector></nomdu-selector>
```
<br>

## Dans app.ts

```bash
import {NomdelaClass} from 'lechemin';

imports: [NomdelaClass],

```

<br>

## Doc officiel

https://material.angular.dev/components/button/overview


