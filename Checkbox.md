## Exemple visuel 

## Checkbox simple 

html

```html
<mat-checkbox>Check box simple</mat-checkbox>
```
<br>

ts

```ts
import {MatCheckboxModule} from '@angular/material/checkbox';
imports: [MatCheckboxModule],
```

## Checkbox avec formulaire réactif

ts 

```ts

import { Component, inject } from '@angular/core';
import { FormBuilder, FormGroup, ReactiveFormsModule } from '@angular/forms';

imports: [ReactiveFormsModule, MatCheckboxModule],

private fb = inject(FormBuilder)
form: FormGroup = this.fb.group ({
	accepTerns: [false]
});
```

html

```html
<form [formGroup]="form">
  <mat-checkbox formControlName="acceptTerms">J'accepte</mat-checkbox>
</form>

```