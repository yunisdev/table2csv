## Installation
Add following HTML before body end:
```html
<script src="https://yunisdev.github.io/table2csv/table2csv.min.js"></script>
<!-- or -->
<script src="https://unpkg.com/yunisdev-table2csv"></script>
```
or you can install using npm:
```bash
npm i yunisdev-table2csv
```

## Usage
You can use this library using following syntax:
```html
<button class="table-btn" onclick="table2csv(this,1)" data-table="usersTable">Download</button>
```
- ```data-table``` is id of table to convert.
- ```table2csv``` is function that converts table in id of ```data-table``` to csv file and downloads. Accepts 2 parameters:
    - ```el```. Required. Accepts object of button.
    - ```endcut```. Optional. Accept an integer to cut from end of table.