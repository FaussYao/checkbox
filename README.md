# checkbox
Custom checkbox to angular 2

# Example
```typescript
import { Component } from "@angular/core";

@Component({
selector: 'app-root',
templateUrl: './app.component.html',
styleUrls: ['./app.component.css']
})
export class AppComponent {

selected: boolean;
title: string = 'Check';
disable: boolean = false;

}
```
```html
 <checkbox [disableValue]="disable" 
           [(ngModel)]="selected"
           [label]="title">
 </checkbox>
```
