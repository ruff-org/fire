# Components
## What?
Components are re-usable user interface elements which are implemented in a web application.

## Why?
Components allow for data to be separated from architecture. 
This is helpful because logic can be re-used to seperate concerns. 

## How?
A simple Fire component can be built as follows:

```html
<fire-test>
    <p>Inner HTML of component...</p>
</fire-test>
<script>
    class FireTest extends HTMLDivElement {
        constructor(){
            super();
        }
    }
    customElements.define('fire-test', FireTest, { extends: 'div' });
</script>
```

The above component is simply a static container around the inner html elements.
The constructor method should be used to define inherit functionality for all like elements.




