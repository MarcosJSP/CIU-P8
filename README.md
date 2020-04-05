# Baby MS Paint using p5.js - by MarcosJSP

The objective of this project is to familiarize myself with p5.js with a simple project such as developing a board where you can paint on:

<p align="center">
  <img align="center" src="readme assets/demo.png" alt="Demo png"></img>
</p>
<p align="center">
   <b>Figure 1 - Baby MS Paint Demo</b>
</p>




## Development

If we look at the right side of the board we can see a color chooser (limited to 4 colors yet), a button with a trash bin icon, which will let us clean the board and at the bottom we have the pencil thickness chooser.

To visually help the user see the pencil thickness there is a semi transparent dot following the cursor.

The way the drawing system works is the following:

- Each time we click to draw, a new figure object is created, storing the position of the mouse while its been dragged. At the moment the figure is created, it also stores the selected color, and pencil thickness.

- To draw the figure on the board, I used lines between the stored positions. These lines also take the color and thickness previously stored.

  

## Tools used & References

- Everything that i learned came from https://processing.org/ && https://http://www2.ulpgc.es/.