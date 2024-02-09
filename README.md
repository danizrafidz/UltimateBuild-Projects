# UltimateBuild-Projects
Reached highest rank engineer in "Ultimate Build" server (the ranks: Engineer -> Good Engineer -> Ultimate Engineer)

![image](https://github.com/danizrafidz/UltimateBuild-Projects/assets/105960343/c1fcf639-922d-4320-8ea8-78d9e2e78531)


## 1. 10x10 Pixel Animation Software (with Logic Gates)

https://github.com/danizrafidz/UltimateBuild-Projects/assets/105960343/eb3211ed-207f-4fc5-9a54-dd2aaa8174d5

Full Showcase ( https://www.youtube.com/watch?v=R0qAFd2zKA4 )

Units I used:
- Logic Gates & Wire: Node, Buffer, AND gate, OR gate, XOR gate, NAND gate, NOR gate, NOT gate, XNOR gate
- Button & Switch
- Transmitter & Receiver
- Repeater & Timer
- Sequence
- Random
- Painter Block
- LED
- Physics Block
- Constraint Tool

![image](https://github.com/danizrafidz/UltimateBuild-Projects/assets/105960343/a0dfc1a2-21d8-489c-82d1-73ffe25eb450)
![image](https://github.com/danizrafidz/UltimateBuild-Projects/assets/105960343/ca073e37-62cd-4e89-bb73-5841e2683a72)

## 2. Geometry Blox (with Logic Gates)
https://github.com/danizrafidz/UltimateBuild-Projects/assets/105960343/612746a5-ed96-4e84-b3dc-5d43b3e25335

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


