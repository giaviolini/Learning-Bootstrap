# Bootstrap
## What I learned/practiced: 
The purpose of this assignment was to create a website using Bootstrap. I learned many things, mostly the fact that I will try to stay as far away from Bootstrap as I possibly can, but also that it has some helpful techniques once you can understand them.

### Displays
Instead of being able to use ```display: grid;``` for Bootstrap you use different columns that have set parameters for their size.  \
For example, I wanted a row of three columns so I created a ```div``` and called the ```class col-4```, ```<div class="col-4">```. This allowed for three columns to span the width of the page. The Bootstrap website has many helpful articles when it comes to picking out the specific columns you will want to use.  \
After figuring that out and getting it set up, I used similar techniques and formatting for the columns as I would in ```display: grid;```.

I also noticed that using Bootstrap, floating an image worked better than just having the image set accordingly. This could also be because I was using text and wanted to wrap it around, all while fitting inside the column structure. 

### Navbar
For this navbar, I used a similar navbar that I used on a different assignment. This navbar uses active properties to add lines when hovering over. The navbar has multiple parts that I followed a codepen for, but it has an active selector and uses the ```::before``` and ```::after``` pseudo-class elements to also program different actions at different times. 
The ```::before``` element is used to code the state of the navbar before it is interacted with while the ```::after```element is used after interacting.   \
ex. ```div.topBotomBordersOut a:before, div.topBotomBordersOut a:after{```  \
It also uses the transform property to show how far off of the x-axis the lines are going.  \
ex. ```transform: translateY(10px);```  \
I used this element in tandem with the transition property to make sure it would transition the lines seemly.  \
ex.```transition: all 0.3s;```  \
After this, changing the opacity, and making sure the header was correctly working, I was done!  

### Background Images
During the assignment I also tried using a background image for one of my headers. I was a bit of challenge to find an image that would be the correct size, but I finally got. I also used the property ```background-repeat: no-repeat;``` to make sure it only should the image once. I also struggled a bit with linked my photo, but because the image was in a folder cause 'images' right in side the root, I can to solution that ```background-image: url('../images/animalcrossingbanner2.jpg');``` would work, and it does!

[Visit Site Here]([https://giaviolini.github.io/Learning-Bootstrap/)
