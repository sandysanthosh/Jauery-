Welcome to the Jauery- wiki!


### Jquery UI:


* ->Jquery ui tutorial for beginners and professional

_higly interactive_
_open source_

* ->Add below head:

  `<link href="http://code.jquery.com/ui/1.10.4/themes/ui-lightness/jquery-ui.css" rel="stylesheet">  `
  `<script src="http://code.jquery.com/jquery-1.10.2.js"></script>  `
  `<script src="http://code.jquery.com/ui/1.10.4/jquery-ui.js"></script>  `

### ->jquery user interface:

* animated visual
* GIU widgets
* themes

### front-end framework:
-### >MIT license

## Jquery UI categorization:

* interactions
* widgets
* effects
* utilities

### interactions:

* ->plugin which facilitates users to interact with DOM element.

* Draggable
* Dropable
* resizable
* selectable
* sortable

-### >widgets:
 * plugin which you able to create user interface like date-picker,progress bar

* autocomplete
* dialog
* button
* date picker
* menu
* progress bar
* Tabs
* slider
* spinner

### ->Effects:

* hide
* show
* add class
* remove class
* switch class
* toggle class
* color animation
* effect 
* toggle

### utilities:
->position

### Jquery UI Draggable:

### draggable()

* `->$(selector,context).draggable(options)Method`
`* ->$(selector,context).draggable("actions",params)Method`

### Droppable:

->Droppable() method to make any DOM element droppable

-`>$(selector,context).droppable(options)Method`
`->$(selector,context).droppable("actions",params)Method`

`<script>`
`$(function(){`
`$("#draggable-1").draggable();`
`$("#droppable-1").droppable();`
`$( "#accordion" ).accordion();`
`$( "#resizable ").resizable(); `
`$( "#button-1" ).button(); `
`</script>`

### second method:

`$(selector,context).draggable(options)Method`
`$(selector,context).droppable("action",params);`
`$(selector, context).resizable (options) Method  `

### destory:

->method

* UI dROPPable
* UI selectable
* UI resizable

### UI resizable:
### disable:
`$( "#resizable-13" ).resizable('disable');   `
### destroy:
`$( "#resizable-13" ).resizable('destroy');  `

### UI SELECTABLE:

->selectable will select the element using the deplay and distance.
`$(function() {$( "#selectable-2" ).selectable({delay : 1000});  `
              `$( "#selectable-3" ).selectable({distance : 100}); `
 `}); ` 
select the element changes the color:

* DISABLE:
`$( "#selectable-5" ).selectable('disable');`
* DESTROY:
`$( "#selectable-5" ).selectable('disable');`


* SORTABLE:

* sort the element by user needs:
`$(function() {$( "#selectable-2" ).selectable({delay : 1000});  `
`$(function() {$( "#sortable-1" ).sortable();});`

`<ul id ="sortable-1">`
`<li class="default">java</li>`
`<li class="default">php</li>`
`<li class="default">.net</li>`
`</ul>`

### widgets:


### Accordion:

* ->expanded and collasible content holder that is broken into sections

* dropdown value will show the content when the user clicks

$("#accordion" ).accordion(); 

### autocomplete:

* ->autocomplete is frequently used in modern websites

* beginning word in the textbox.

`$(selector, context).autocomplete (options);  `
`$(selector,context).autocomplete(options)Method`

`->auto search like www.google.com`

### JqueryUI button:

-`>jquery buttons,inputs,anchors`

`->disabled`
`->icons`
`->label`
`->text`
`->button`

`$(function() { $( "#button-1" ).button(); });`

### ->buttonset:

`$(function() { $( "#button-5" ).buttonset(); });`
`<div id="button-5">`
`<input type="checkbox" id="check"><label for="check1">`
`<input type="checkbox" id="check"><label for="check2">`
`<input type="checkbox" id="check"><label for="check3">`

### Jquery Datepicker:

`-><input type="text" id="datePicker">`

`$(function(){ $( "#button-5" ).datepicker(); });`


### JQUERY UI DIALOG:

`<button id="datePicker">click this</button>` 

### JQUERY UI MENU:

* MAIN MENU WITH POPUP MENU:

* SOME ITEMS IN THE POPUP

`<script>`
`$(function (){`
`$("MENU").menu();`
`});`

`<ul id="menuu">`
`<li><a href=" ">c</a></li>`
`<li><a href=" ">cpp</a></li>`
`<li><a href=" ">JAVA</a>`
`<ul>`
`<li><a href=" ">core java</li>`
`<li><a href=" ">J2EE</li>`
`<li><a href=" ">Spring</li>`
`</ul>`

`<script>`
`$(fuction(){`
`$("#menuu").menu();`
`}`
`</script>`


### UI PROGRESS BAR:

* ->DETERMINED PROGRESSBAR
* ->INDETERMINED PROGRESSBAR

### determined progress bar:
* ->update the current status
* ->is used to provide user feedback

### progress bar:

`<div id="progressbar"></div>`
`$(function(){`
`$("#progressbar").progressbar({value:30})});`

### ui-select menu:

### ui-slider:

`$( "#slider-1" ).slider();  `
`<div id="slider-1"></div>  `

### ui-spinner:

`$( "#spinner" ).spinner();  `
`<input type="text" id="spinner" value="1">`