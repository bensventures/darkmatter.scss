# darkmatter.scss
A micro reset library for material-ish look and feel.

## Classes
The idea was to only use tag names to make it a trully drop-in reset. However some classes are used for now until a better solucion is devised:

* `.icon-label` : Used in place of a text label to identify a form field. A following input will be resized to fit the icon and input on the same line (uses `display:flex`)
* `.icon-btn`: A button that has a `.icon` in it.
* `.icon`: An icon. Only necessary when used inside a button. Meant for svgs for now.
* `.grouped-inputs`: Make inputs stick together. Works for textual inputs (text, number, password) and `<button>`.
* `.error`: For error messages. 
