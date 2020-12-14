[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/thiagodepaulla/)](https://www.linkedin.com/in/thiagodepaulla/)   [![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/thiagodpaulla)](https://github.com/thiagodpaulla)


# Hello and welcome to my repository
## Meet traffic light

![](https://github.com/thiagodpaulla/semaforo.github.io/blob/main/Sem%C3%A1foro%20.gif)

## Feel free to interact with the project at the link:

https://thiagodpaulla.github.io/semaforo.github.io/

### Stretch a little more and, know a little more than I've been doing:



https://thiagodpaulla.github.io/

### Understand a little more about how it was created.

  * [Project](#project)
  * [Technologies](#technologies)
  * [License](#license)



# Project
💻

Trying to make semantic and clean code, thinking about small functions and sole responsibility
There were 4 images and 4 commands

I used VScode
Inside the HTML I created an img div and then in another div I created four buttons and assigned them an id related to the color of the traffic light and an automatic function.
Inside the HTML I called the JS file and also the CSS which is a basic css where there is centralization, and some guidelines for the main, such as height etc. and a gap (space) of 10h between the two dives so they are not stuck the image to the buttons.

Within the JS file, the following steps were taken:

I declared a const object to receive the id img and in the sequence I created a parent element and through the parent element I know and which element the user clicked.
this was done by creating a const that received the file the id Button previously declared and then I used addEventListener to listen to which button the user was clicking through the traffcLigth function and assigns it to an errolfunction

But how do you know which button he clicked on?
When we assign a function to the addEventListener or callback, this callback takes an argument from the addEventListener and this argument is the event it was clicked on, and it stores a series of information including the target from which button was clicked.
with this it is possible to assign this event to a const and thus be able to control what to do with each user's intersection.

after that, a turnOn object was created where the program started to receive the functions of the images.

But what is the method of an object called?
Remembering that the information inserted inside an object receives (,) and not (;) because it is as if everything were just one line.
using the event, the target, and the target id getting [event.target.id]

Using an interval function in java script

using setInterval that executes a function within a time interval that is determined for it, here in this case 1 second was defined.


For that I had to create a changecolor function, and using an array with the colors.
then creating a global variable type let. (because it will change)

Tender function first he adds one more, then he assigns it inside an errol function.

# Technologies

🚀 The project was developed using the following technologies


➜ JavaScript

➜ HTML

➜ CSS


# License
📂 Distributed under the MIT license. See LICENSE for more information.
