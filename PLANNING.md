# Planning

## Brainstorming

### Helicopter, catapult, bottle rocket, balloon, plane, attach it to a bird, throw it

## Project Plan Overview

### We decided to make a bottle rocket. To power the bottle rocket we will use HHO otherwise known as "brown gas". This gas is produced from 
doing electrolysis to water. When ignited this gas combusts and rushes out of whichever spot provides the least resistance. Our idea is to have
this gas propel our rocket into the sky. 

Planning Documents: https://drive.google.com/drive/folders/1tZ5dSv5s1o1vbS3MPye-oxdw0tjJOcvf?usp=sharing

# Just Kidding, now we're donig a stomp rocket because it would take too much time to do previous idea.
## New Planning
We have decided to do a stomp rocket because the mechanics are simple and it can be designed efficiently. We are going to use a 2 liter bottle to boost the stomp rocket. Then we will use two half inch PVC pipes with an elbow socket to turn the pipe in an upward direction. We found a model of a 2 liter bottle to PVC connector on thingiverse.com (link below) and 3D printed it (1). To balance the stomp rocket model we added another PVC pipe underneath going in a perpendicular orientation. The final piece we had to design, the piece connected the two PVC pipes together (2).
https://www.thingiverse.com/thing:733138

## Code Progress
### Overview

Our code was relatively simple to code. We used an altimeter to measure the rough altitude of our pi. Using the altimeter we were able to write code that essentially continuously takes the altitude, and when it notices that the altitude has decreased by 1 meter (because it is a inconsistent reading it can be off by half a meter, which is why we needed to account for that inconsistency by making it a one meter difference), our buzzer lets out a distinct beep letting us know we hit the peak of our launch.

### Early Days

In the beginning stages of our project we were having trouble figuring out how to code with the altimeter, and the libraries that went with it. However like any good engineering project we eventually figured it out using tutorials and basing our code off of others who had done similar things. Another big problem we ran into early on was our parachute approach. The servo wouldn't fit with our rocket's design, and the way we had planned for the parachute to come out of the rocket wasn't going to work. I had coded a servo to do the same thing as the buzzer except instead of beeping it releases the parachute. This plan did not come to fruition and we landed on doing the buzzer instead for simplicity and time's sake.

### Final Stage

In our finishing up of our project we noticed some other problems. Our power button was extremely inconsistent. You would hold it for a good 10 seconds and it wouldn't shut down, just restart. Sometimes you would only hold it for 4, and it would shut down. Nothing about it made sense. However we were running out of time and with the deadline to launch quickly approaching we decided to retrieve the pi from the rocket and shut it down safely by plugging it in and telling it to shut down. Even Mr. Miller with his brilliant engineering expertise couldn't figure out how to fix this problem.

## CAD Progress
### Overview

### Early Days

### Final Stage

## Wiring

### Onshape Model
![onshapeModel1](https://user-images.githubusercontent.com/61475474/170089028-022e442f-cfac-4aa3-8735-daca17539c44.png)

### Process Pictures
![IMG_4223](https://user-images.githubusercontent.com/60942957/171414435-9118b1e9-0dd9-4ad9-9428-245846d9410e.JPG)
