# Bootstrap
## What I learned/practiced: 
The purpose of this assignment was to create a website using Bootstrap. I learned many things, mostly the fact that I will try to stay as far away from Bootstrap as I possibly can, but also that it has some helpful techniques once you can understand them.

### Column Setup
Instead of being able to use CSS ```display: grid;```, with Bootstrap you use the syntax provided by the framework. Different columns have set parameters for their size. For example, I wanted a row of three columns so I created a ```div``` and called the ```class col-4```, ```<div class="col-4">```. This allowed for four columns to span the width of the page. The Bootstrap website has many helpful articles when it comes to understanding the specific columns you will want to use.

After figuring that out and getting it set up, I used similar techniques and formatting for the columns as I would in ```display: grid;```. It was the only part of Bootstrap that I used as I prefer to create the CSS myself. I found Bootstrap too restrictive to achieve the design I wanted.

I also noticed that using Bootstrap, floating an image worked better than just having the image set with CSS. This could be because I was working with the bootstrap column structure. 

### Navbar
For this navbar, I used a similar navbar that I used on a different assignment. This navbar uses active properties to add lines when hovering over. The navbar has multiple parts that I followed a Codepen for, and it has an active selector using the ```::before``` and ```::after``` pseudo-class elements to show different actions at different times. 

The ```::before``` element is used to code the state of the navbar before it is interacted with, while the ```::after``` element is used after an interaction like hovering. 

ex. ```div.topBotomBordersOut a:before, div.topBotomBordersOut a:after{```

It also uses the transform property to show how far off of the x-axis the lines are going. 
ex. ```transform: translateY(10px);``` 

I used this element in tandem with the transition property to make sure it would transition the lines seemly.
ex.```transition: all 0.3s;```

After this, changing the opacity, and making sure the header was correctly working, I was done!  In the future, I will experiment more with using the Navigation available in the Bootstrap Framework.

### Background Images
During the assignment, I also tried using a background image for the homepage header. It was a bit of a challenge to find an image that would be the correct size, but I finally got what I was looking for. I also used the CSS property ```background-repeat: no-repeat;``` to make sure the image only showed once. I struggled a bit with linking the photo, but finally discovered that because the  'Images' folder was the root directory, I could use ```background-image: url('../images/animalcrossingbanner2.jpg');``` which works great!

[Visit site here](https://giaviolini.github.io/Learning-Bootstrap/)
