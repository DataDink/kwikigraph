# kwikigraph
 visualize quickly

# Quick Start

* Open [kwikigraph.html](kwikigraph.html) in your browser

# Reference

[!NOTE]
* *Parameters are evaluated as javascript.*
* *Use parentheses to capture whitespace.*
* *Does not support strings*

[!WARNING]
* *editing the DOM can break the app*

> * `move x y`
>   * Moves the cursor to the x/y coordinate.
> * `plot x y [ move ]`
>   * Puts a dot at the x/y coordinate and optionally (true/false) moves the cursor.
> * `line x y [ move ]`
>   * Draws a line from the cursor to the x/y coordinate and optionally (true/false) moves the cursor.
> * `grid size`
>   * Sets the grid line spacing
> * `offset x y`
>   * Pans / offsets the drawing
> * `clear`
>   * Clears / resets the drawing
> * `color [stroke [, grid [, background [, origin]]]`
>   * Sets colors (null to keep existing value)
> * `weight [stroke [, grid [, origin]]`
>   * Sets line thickness (null to keep existing value)
> * `set name expression`
>   * Remembers a named value. Expression will be evaluated as a single line of javascript.
> * `get name`
>   * Prints the remembered value


