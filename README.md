kb.css
======

A small (< 2 kb) stylesheet for rendering text as keyboard keys. It scales with text size and is compatible with modern browsers. Use the `.kbd` class on a `span` or the `<kbd>` tag:

```html
<p>
After you have gained access to the missile control system, press 
<kbd>Ctrl</kbd> + <span class="kbd">Backspace</span> to override the safety controls.
</p>
```

results in:

!["Example"](https://raw.githubusercontent.com/JSlote/kbd.css/master/example.png "Example")

You need to specify a `z-index` for the parent element. Play with the example on JSbin: http://jsbin.com/zimacahe/3/edit
