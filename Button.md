## Exemple visuel 



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

