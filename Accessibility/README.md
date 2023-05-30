**What is aria-pressed?**
<br>
The aria-pressed attribute indicates the current "pressed" state of a toggle button. Example: <br>
<br>
HTML
```html
<button aria-pressed="false" class="toggle">Toggle Me</button>
```
JS
```js
const IS_PRESSED = document.querySelector("button").matches("[aria-pressed=true]");
BUTTON.setAttribute("aria-pressed", IS_PRESSED ? false : true);
```
