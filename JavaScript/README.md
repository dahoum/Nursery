# JavaScript

## Event Listeners

Introduction to Keyboard Events in JavaScript

https://www.section.io/engineering-education/keyboard-events-in-javascript/

https://www.w3schools.com/jsref/met_element_addeventlistener.asp 

```
// Add event listener on keydown
document.addEventListener('keydown', (event) => {
            
    var name = event.key;
    var code = event.code;
            
    // Alert the key name and key code on keydown
    alert(`Key pressed ${name} \r\n Key code value: ${code}`);

}, false);
```
