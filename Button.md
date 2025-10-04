## Exemple visuel

<img width="89" height="43" alt="example button" src="https://github.com/user-attachments/assets/2d610d3f-e783-4dd7-8f0a-d126739cb02c" />


## Créer un dossier components et placer vous a l'interieur. 



```bash
src/
├── app/
│   ├── components/
```

## Creer un button

```bash
ng generate component nomducomposant
```

## html

```bash
<button matButton="filled">
	montextesurlebouton
</button>
```

## ts 

```bash
import { MatButtonModule } from '@angular/material/button';

imports: [MatButtonModule],
```

## Dans app.html 

```bash
<nomdu-selector>></nomdu-selector>
```

## Dans app.ts

```bash
import {NomdelaClass} from 'lechemin';

imports: [NomdelaClass],

```

## Doc officiel

```bash
https://material.angular.dev/components/button/overview
```

