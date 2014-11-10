# jquery.ui.timeselect.js

## Requirements
1. [jQuery (1.6+)](http://jquery.com/)
2. [jQuery UI (1.10+)](http://jqueryui.com/)
3. [Datejs](http://www.datejs.com/)

##Options
1. *step* _(default: 30)_
2. *format* _(default: 'h:mm tt')_
3. *maxResults* _(default: null)_
4. *autocompleteSettings* _(default: {})_

##Examples

#### Basic Example
```javascript
$('#example-1').timeselect({
    'step': 15,
    autocompleteSettings: {
        autoFocus: true
    }
});
```
    
#### Maximum Results
```javascript
$('#example-1').timeselect({
    'step': 15,
    autocompleteSettings: {
        autoFocus: true
    }
});
```
    
#### Military Time
```javascript
$('#example-1').timeselect({
    'step': 15,
    autocompleteSettings: {
        autoFocus: true
    }
});
```

To see a working example, go to [http://dochoffiday.com/_demo/jquery.ui.timeselect](http://dochoffiday.com/_demo/jquery.ui.timeselect)