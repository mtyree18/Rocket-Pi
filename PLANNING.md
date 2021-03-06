# Planning

## Brainstorming

Helicopter, catapult, bottle rocket, balloon, plane, attach it to a bird, throw it

## Project Plan Overview

We decided to make a bottle rocket. To power the bottle rocket we will use HHO otherwise known as "brown gas". This gas is produced from 
doing electrolysis to water. When ignited this gas combusts and rushes out of whichever spot provides the least resistance. Our idea is to have
this gas propel our rocket into the sky. 
#
#
#
# Project Shift
#
#
#
## New Planning
We have decided to do a stomp rocket because the mechanics are simple and it can be designed more efficiently. Due to time constraints our previous idea is not realistic.

## Code Progress
### Overview

Our code was relatively simple to code. We used an altimeter to measure the rough altitude of our pi. Using the altimeter we were able to write code that essentially continuously takes the altitude, and when it notices that the altitude has decreased by 1 meter (because it is a inconsistent reading it can be off by half a meter, which is why we needed to account for that inconsistency by making it a one meter difference), our buzzer lets out a distinct beep letting us know we hit the peak of our launch.

### Early Days

In the beginning stages of our project we were having trouble figuring out how to code with the altimeter, and the libraries that went with it. However like any good engineering project we eventually figured it out using tutorials and basing our code off of others who had done similar things. Another big problem we ran into early on was our parachute approach. The servo wouldn't fit with our rocket's design, and the way we had planned for the parachute to come out of the rocket wasn't going to work. I had coded a servo to do the same thing as the buzzer except instead of beeping it releases the parachute. This plan did not come to fruition and we landed on doing the buzzer instead for simplicity and time's sake.

### Final Stage

In our finishing up of our project we noticed some other problems. Our power button was extremely inconsistent. You would hold it for a good 10 seconds and it wouldn't shut down, just restart. Sometimes you would only hold it for 4, and it would shut down. Nothing about it made sense. However we were running out of time and with the deadline to launch quickly approaching we decided to retrieve the pi from the rocket and shut it down safely by plugging it in and telling it to shut down. Even Mr. Miller with his brilliant engineering expertise couldn't figure out how to fix this problem.

### Linked Code

link : https://github.com/mtyree18/Engineering_4_Notebook/blob/86269f6525d0875e81fcc4ccfdc47e88c4480bd2/Python/altitude.py

## CAD Progress
### Overview
For the stomp rocket we are going to use a 2 liter bottle for propulsion. Then we will use two half inch PVC pipes with an elbow socket to turn the pipe in an upward direction. We found a model of a 2 liter bottle to PVC connector on thingiverse.com (link below) and 3D printed it (1). To balance the stomp rocket model we added another PVC pipe underneath going in a perpendicular orientation. The final piece we had to design, the piece connected the two PVC pipes together (2). 
https://www.thingiverse.com/thing:733138
<img src="https://user-images.githubusercontent.com/61475474/170089028-022e442f-cfac-4aa3-8735-daca17539c44.png" width = "210.5">

### Early Days
In the beginning of the project we wanted to make our rocket into two pieces so we could slide the Pi inside and put a top on. On the top we would use a servo to open a hole for a parachute. After re-evaluating our project we determined that we wouldn't need a parachute due to the projected height of the projectile.
![onshapeEarlyDesign](https://user-images.githubusercontent.com/61475474/171678041-d73a41bd-8451-49fa-b627-f60ef16f6787.png)

### Final Stage

empty

### Linked Model

Link : https://cvilleschools.onshape.com/documents/9361add885ff5dd5aff085b3/w/0670184bbbeabc8a29667710/e/3fa74f3cb619229d4a364e5b?renderMode=0&uiState=6297767f35c2b53b17c29742

## Wiring Progress

### Wiring Overview
The wiring was maybe the most challenging part of this project, and not because it was the most difficult skill wise, or even difficult to understand. It was so challenging because we had to get this rocket in the air and due to setbacks at the beginning of the project, as well as one of our team members (me I'm Max I got covid) getting covid, we were far behind from where our project plan put us. Neither of us has much soldering experience either, which slowed us down considerably. The final jumble of wires did work though. It may not have looked clean, and was not easy to understand, but it served its function and got electricity from point A to point B.

### Wiring Pictures

<img src="https://user-images.githubusercontent.com/60942957/171425415-c96e60c0-f401-4c89-abcc-c243fdc72777.png" width = "210.5">

<img src="https://user-images.githubusercontent.com/60942957/171414435-9118b1e9-0dd9-4ad9-9428-245846d9410e.JPG" width = "210.5">

<img src="https://user-images.githubusercontent.com/60942957/171424201-8720a149-bb4a-44cd-b836-10c66b874288.png" width = "210.5">

<img src="https://user-images.githubusercontent.com/60942957/171425188-8f67cbe3-9a19-45fc-85ce-9e48772442b6.png" width = "210.5">

## Materials Used

empty

## Timeline

empty

### Miscellaneous Pictures

<img src="https://user-images.githubusercontent.com/60942957/171424810-0ec4beb4-9fea-444e-87b4-e4fb8e316ea5.jpg" width = "210.5">
