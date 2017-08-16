# ng2-mask-with-renderer

This module is a copy from https://github.com/NepipenkoIgor/ngx-mask, but change renderer2 to renderer

## Getting Started

npm install --save ng2-mask-renderer

In app.module.ts

1. import { Ng2MaskModule } from 'ng2-mask-renderer'
2. imports: [ ..., Ng2MaskModule,....]


##Using

Add mask in your input as in the example below

```
<input (blur)="validateDate(form.birthday)" value="{{form.birthday}}" mask='99/99/9999' required name="birthday" [(ngModel)]="form.birthday" type="text"/>
```
