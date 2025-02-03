# CARP
## OBJECTIVE
The main objective of this project is to create a web application in which the user can draw shapes and use them to control the audio buffer and the gain.

## GUI
- The main part of the graphical user interface is the canva, in which the user can draw. The canva has a line in the middle, this line rappresent the 0 value of the shape and the upper limit and the lower limit rapresents the higher and lower value we can pass to the data buffer or the gain.
in the corner of the canva we can find a button that enable the user to chage the shape they are controlling (wheter they are changing the wave or the envelope).
- In the lower part of the web page we find the keyboard, the octave up and down buttons and the envelope duration slider. The keyboard can be accessed booth by clicking with the mouse or using the computer keyboard (a, w, s, e, d, f, t, g, y, h, u, j, k), the same goes for octave up and octave down (z, x). The envelope duration slider controls how fast the shape drawn on the canva will be "read". 
- In the upper right part of the web page we find the buttons to interact with the database. we have a input text-box in which the user can write. Then they can save the shape visualized in the canva in the database with the name specified in the text-box name, load on the canva a shape with the name specified in the text-box name from the database, remove from a shape with the name specified in the text-box name from the database.
The names of shapes saved in the database will be shown in the grey part titled "Stored Waves".
- In the lower right part of the web page we find controls associated with the shapes. This buttons fills our wave or envelope (based on what the canva is set on) with a precise shape (sine, square, triange, adsr).
