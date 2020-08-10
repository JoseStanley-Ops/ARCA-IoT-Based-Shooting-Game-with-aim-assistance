# Arca - IoT based Shooting game with aim assistance
This project is coined with an idea of engaging kids in a physical acticity in the middle of this online gaming era. What's the catch? Imagine you could play a physical game such as dart, bow and arrow at your home but against someone from the other side of the globe. Alright, let me explain it with the help of reality. In this project I am bringing a trajectory shooting gun with an aim assistance setup and a method to access game scores online. 

Three units of the project 
1. Gun Unit
2. Target Unit
3. IoT unit

Gun Unit:
‘Parabolic shooting gun’ is a setup which works based on the principle of trajectory motion. The
gun is developed in a way such that, it can shoot a ball to the target in a parabolic way with
automatic distance calculation assistance. The angle of projection is calculated by using a tilt
sensor. In this gun, the velocity of the ball will be constant.The integral part of the gun is the
microcontroller which automatically determines the horizontal distance the ball can cover, when
it is shot in a specific angle, by using the data from accelerometer. There will be a display module
attached to the gun to display the angle of projection and distance. So the player can change the
angle of projection to meet the distance to the target.

Target Unit:
Target unit comprises a dart-board with a target circle, a sensor connected to the circle to detect target hits, a microcontroller to access target hits data. These data is being uploaded to internet using inbuilt wifi module in the microcontroller

IoT Unit
Now internet is taking over the data flow. We use an API to receive the data from the target unit. These data can be represented graphically using MATLAB tools within the API. And it is publicly accessible for other users. Now, when other people around the world with the same game setup plays, the data is automatically uploaded to the internet. 

This project can be further developed for a scoreboard to portray top-scorers, users current position in the scoreboard and so on 
