# Bootstrap
##What I learned/practied: 
The purpose of the this assignment to was to create a website using bootstrap. I learned many things, mostly the fact that I will try to stay as far away from bootstrap as I possibly can, but also that it has some helpful technquies once you can understand them.

### Displays
Instead of being able to use use ```display: grid;``` for bootstrap you use different columns that have set paramaters for their size.  \
For example I wanted a row of three columns so I created a ```div``` and called the ```class col-4```, ```<div class="col-4">```. This allowed for three columns to span the width of the page. The bootstrap website had many helpful articles when it comes to picking out the specific columns you will want to use.  \
After figuring that out and getting it set up, I used similar techquies and formatting for the columns as I would in ```display: grid;```.

I also notice that using bootstrap, floating an image worked better then just having the image set accordingly. This could also be because I was using text and wanted to wrap it around, all while fitting inside the column structure. 

### Navbar
For this navbar I used a similar navbar that I used on a different assignment. This navbar uses active properties to the add lines when hovering over. The navbar has multiple parts that I followed a codepen for, but it has an active selector and uses the ```::before``` and ```::after``` pseudo-code elements to also program different actions at different times. 
The ```::before``` element is used to code the state of the navbar before it is interacted with while the ```::after``` elements is used after interacting.   \
ex. ```div.topBotomBordersOut a:before, div.topBotomBordersOut a:after{```  \
It also uses the transform property to show how far off of the x-axis the lines are going.  \
ex. ```transform: translateY(10px);```  \
I used this element in tandom with the transition property to make sure it would transition the lines seemly.  \
ex.```transition: all 0.3s;```  \
After this, and changing the opacity, and making sure the header was correctly working, I was done!  

### Background Images
During the assignment I also tried using a background image for one of my headers. I was a bit of challenge to find an image that would be the correct size, but I finally got. I also used the property ```background-repeat: no-repeat;``` to make sure it only should the image once. I also struggled a bit with linked my photo, but because the image was in a folder cause 'images' right in side the root, I can to solution that ```background-image: url('../images/animalcrossingbanner2.jpg');``` would work, and it does!

[Visit Site Here](https://giaviolini.github.io/bootstrap/)
