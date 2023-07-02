# Drawing Assignment 2 - (Creative Coding)
-------------------------------------------
Instructions:

Click - Create Paint Cluster

Shift - Hold Shift to change color by dragging the mouse left and right
across screen.

Up and Down Arrow - Change size of the individual circles in clusters.

-------------------------------------------
Description:

In my previous project I made a cluster of stars by hard-coding where
it spawns, but this time I wanted the user to be able to place the clusters.

First, I took the spawn cluster function from my previous assignment and
then changed it to spawn upon the click with the center being the spot it was clicked.

Next, I wanted to add a function that changed the color of the cluster, so
I added a function for when Shift is held it would change the RGB and also display
it at the bottom of the window. (Also as a side note if you hold down the shift and
spam click going back and forth it creates a pretty cool rainbow pattern)

Finally, I added a size function by adding a function for increasing or
decreasing the size by pressing the up and down arrows with a min of 1 and max of 10. It is
displayed at the bottom of the screen. 
When testing the larger sizes, the stroke made it
look a little weird so I changed it to noStroke() and it made it seem like paint splatters
rather than stars, which I thought looked pretty cool.

-------------------------------------------
Link to project: https://editor.p5js.org/Kevin-Lewis-13/sketches/GNFbIGJYJ

Portfolio Link: https://kevinlewis.net/other-projects/drawing2-creative-coding
