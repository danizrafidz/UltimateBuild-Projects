# UltimateBuild-Projects

## 1. 10x10 Pixel Animation Software (with Logic Gates)
<iframe width="560" height="315" src="https://www.youtube.com/embed/R0qAFd2zKA4?si=-WPqur4jTZynkm9H" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

![image](https://github.com/danizrafidz/UltimateBuild-Projects/assets/105960343/a0dfc1a2-21d8-489c-82d1-73ffe25eb450)
![image](https://github.com/danizrafidz/UltimateBuild-Projects/assets/105960343/ca073e37-62cd-4e89-bb73-5841e2683a72)

## 2. Geometry Blox (with Logic Gates)
![image](https://github.com/danizrafidz/UltimateBuild-Projects/assets/105960343/8e796a4d-f6b7-4c04-a3cc-88bab60d5df2)
Some details of the algorithms that I used:
Initialize game variables:
- Blocky
- Score
- Timer
- Obstacle
- TWD (Text When Die)

Loop:
If the player activates play button (Yellow Switch on Left):
    Reset timer to 0
    Start the timer
    Activate the Score system
    Generate random obstacle at a random time interval
    Unlock the jump button

If the player presses jump button (Long Red Button)
    Move the Blocky upwards then downwards (with set animation, 0.2 sec frame, total of 5 frames)

Check for collision between blocky and obstacle:
    If collision occurs:
        End the game loop by deactivating play switch
        Display TWD (Set 4 digit hex to D-E-A-D)
        Reset score to 0
        Lock the jump button

If Blocky successfully jumps over an obstacle:
    Increase the score

If the obstacle goes off the screen:
    Remove the obstacle

Display the game screen with the blocky, obstacles, score, timer, text when die.

## 3. Line Follower Mouse (Pathfinding Robot)
https://github.com/danizrafidz/UltimateBuild-Projects/assets/105960343/816072a9-c9c2-42e6-b69a-02c3f9cdb080

## 4. Functional Tower Crane
Controls Info:
E - Raise Crane Height
Q - Lower Crane Height
A - Rotate Crane Left
D - Rotate Crane Right
R - Raise Hook
F - Lower Hook
W - Forward Hook
S - Backward Hook
X - Stick (Using Glue)
Z - Stabilize
C - Anchor
T - Peak Camera
Y - First Person Camera
![image](https://github.com/danizrafidz/UltimateBuild-Projects/assets/105960343/fabd8b4e-2054-41f5-91dd-23f495dc07bf)

## 5. Connect 4 (with Logic Gates)


