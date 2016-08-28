# hello-world
Initial Repository

// Hi, I'm a programming nube. I'll be using GitHub to store my coding projects and helpful code for the ride!
// feel free to jump in and tweak what you see here.   
//-bf


var degreesOutside = 70;
var numberOfClouds = 50;
if (degreesOutside > 70 && numberOfClouds < 5) {
  text("Wear sun screen!", 200, 200);
}

rect(100, 50, 100, 100); 

mousePressed = function() {
    if (mouseX > 100 && mouseX < 200 && mouseY > 50 && mouseY < 150) {
      text("You pressed it!", 80, 75);
    }
};
