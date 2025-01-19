# Online-Meet-Logs


## Workshop 1: 14/1/25
Began watching the video and I rewatched the beginning because I was very interested in the move function Leo used. This helped me because I was trying to figure out how to make a block come back after reaching the edge of the canvas. I’m glad I now know how to use this tool.

<img width="1046" alt="Screenshot 2025-01-14 at 5 01 56 PM" src="https://github.com/user-attachments/assets/9c4d0273-fd57-480f-81e4-3089987de38c" />
This is my block that bounced from wall to wall. I also made it so it stopped and looked like it was bouncing on the right wall by making it stop it’s own width before the canvas width so it appeared like it was bouncing off of it. This is super fun and I’m going to experiment to see if I can do the same thing vertically. And Ideally, I would be able to make a pong game out of rectangles (or even triangles if I felt so compelled to do so).

## Workshop 1: Loops
Also learning how to use the loops ‘while’ and ‘for’, as well as writing x=x+50 as x+=50 because that’s a shortcut.
The ‘while’ enables a restriction within making something happen. In his example, Leo made it possible for duplicated rectangles to be made within the canvas. This means that you don’t have to individually generate shapes onto the canvas which keeps your code tidy and short.  This is how the ‘while’ function is written out:

 while (x < width){
rect(x, 200, 25, 80);
x += 50;
}

The ‘for’ function also helps keep code tidy and allows for you to use three key elements when generating shapes, the variable (x=0), the exit condition (x<width), and the incrementation (x+=50).
Leo says that this will be the loop that we will use the most often because it is the most compact/shortest to type, as well as being super useful for generating shapes and objects to fill in/be contain within a certain space on the canvas. 
It is written like this:
for (x = 0; x < width; x += 50){
rect(x, 200, 25, 80)
}

### Functions: codes you name that have specific qualities/purposes
Defining and calling functions, function draw() and function setup() are two functions that exist in p5.js. Inside the brackets you can adjust parameters and arguments into the function.
The curly brackets {} exist to house the code the function will execute when it gets called.  
x ++ is a shorthand meaning x=x+1

### What does it mean to define and call your functions?
- Modularity and reusability
- To keep lines of code tidy/easy to navigate
- Ability to call a function again rather than try to make it again
- Variables(use anywhere) vs Function Variables (usable within a function)
- Making multiples parameters means more things that can be adjusted on the thing you have created e.g. height, width, length, colour

### Leo’s example of creating a function on the right:
function draw() {
background (220);

makeHouse (50, 200,
30, color (255, 0, 0));
makeHouse (150, 200, 150, color (255,
255, 0));
makeHouse (250,
200,
makeHouse (350,
200,
50, color(40, 100, 200));
20, color (200, 100,
makeHouse (450,
200, 100, color(30, 200,
90));
80))

}

function makeHouse(xPos, yPos, stories, colour) {
fill(colour);
noStroke();
rect(xPos, yPos, 50, stories);
triangle(xPos, yPos, xPos + 25, yPos - 20, xPos + 50, yPos);

};

Which made a bunch of houses and enables their parameters to be changed. Thus Leo has created his houses and now they are an object rather than being a rectangle and a triangle. This means that far more detailed things can be made.

## Online Meet 2 (15/1/25)
Leo Demos Github, I’ve made an account but haven’t used it yet. Looking into 6 of 21 artists, one of which I will need to study and use as inspiration. Leo is talking about using Github but I don’t know how to use it. So far I have just put photos of my work on these slides so I will email him after this call on how to use Github and move my p5.js files onto it as well as make whatever is expected of us on there. It seems like Github will now be the major way of me taking notes which is making me very worried because I don’t really know what I’m doing. Forking to share files on Github.
- Organise all these notes in Github and make it into a README file because that is what I need to hand in

## Online Meet 2 Cont.
What is computational arts? Art and Computation by Miguel Carvalhais (book)/Art in which computation is pivotal and meaningful/Not limited to digital computers/Creating systems and environments rather than artifacts/Philip Galanter/Generative art is “as old as art itself”/Creating systems and algorithms (rather than artifacts which are secondary)/Ada Lovelace/Grant D. Taylor - when the machine made art: the troubled history of computer art/“Why was computer art so heavily maligned?”/Interdisciplinary and the ‘artist-programmer’ - different way of working - too scientific or too artsy to fit in/Frieder Nake/using pseudorandomness to let the computer to decide/the plotter/Vera Molner (the balance of chaos and harmony that humans are all in search of)/John F .Simon Jr/notion of unknowable/beyond humanness

<img width="590" alt="Screenshot 2025-01-16 at 11 30 57 AM" src="https://github.com/user-attachments/assets/9b519955-7398-4dda-adf4-48bfe67ecfb8" />
