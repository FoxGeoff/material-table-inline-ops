# Project: MaterialTableInlineOps

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.1.

## Project References

1. <https://www.freakyjolly.com/angular-material-table-operations-using-dialog/>

### Task: Add material

1. run  ```ng add @angular/material```

### Task: Update app.module

### Task: Add mat-table

1. ```*matHeaderRowDef``` takes an array of columns we want to show in the table.
2. ```matColumnDef``` property on the column is the same as a key in the JSON data object.
3. ```*matHeaderCellDef``` have the text of columns in the table header.
4. ```#mytable``` is a template variable used to refeash the data by calling the maethos ```rendRows()```

### Task: Add Dialog Component

1. Run ```ng generate component dialog-box --skipTests=true```

### Task: Add flex layout

1. Ref. <https://github.com/angular/flex-layout>
2. Run ```npm i -s @angular/flex-layout @angular/cdk```
3. Example demo <https://tburleson-layouts-demos.firebaseapp.com/#/docs>
