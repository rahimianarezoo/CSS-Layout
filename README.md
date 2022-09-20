# CSS-Layout
I've learned CSS grid from different online resources However, I used Kevin Powell's giude for testimonial example.
- grid is a two-dimensional css layout system.
One of the interesting thing I learned is 'grid-area' property, by setting a name to this property for an item you can set the grid based on your desire in next step. In another word, if you assign a name to the item in future by refrencing this name you can specified you own grid template by using another property named 'grid-template-areas' so you repeat the name of a grid area you already created. You can clone this exmaple and discover this cool feature.

NOTE: When using 'grid-template-areas' make sure for each row you need to have the same number of cells.


NOTE: If you need an empty cell you can use a period "." which signifies an empty grid cell.
In Grid folder:
- I've worked with 'grid-areas' property which is a cool feature. 
- I've worked with 'grid-auto-column' property and help in situation of create any automatic generated column and it give the same size of each of them (I found it a nice feature)
- In albums file, I created an albums grid example and show how use nested grid in practice, I also used autofill and minmax(). The interesting part is that there is no media quesry but it's totally responsive meaning that as big as / as small as  page goes you will not face any issue to work with it.

- Another cool example is my image gallery. In this project I created an images by using DOM.
  For the item that needs be span HORIZONTALLY I consider "h" class and a number meaning how much span e.g. "h2" means horizontally span 2.
  For the item that needs be span VERTICALLY I consider "v" class and a number meaning how much span e.g. "v3" means vertically span 3.
