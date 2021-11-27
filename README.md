# brickBreaker


*-Project idea*

*A project for IT214 describing the game Breaker and Bricks
So that every time the breaker passes through the bricks it crashes .*

How we Control this game?
* You can control the protection of the ball from falling to the ground
To move it you can use -> to right and <- to left
* You can change the result increment each time via [THIS CODE](https://github.com/Noi-9/brickBreaker/blob/main/Gameplay.java)
```java
if(ballRect.intersects(brickRect)) {
                            map.setBrickval(0,i,j);
                            totalBricks--;
                            score +=5;
```
*Refrences*
-
-
*Outbut*
-If you lose, you will get this result


![gOver](https://user-images.githubusercontent.com/95036158/143718794-c231c204-12ea-41bb-9192-829f3b82b705.jpg)

And if you win, you will get this result
![Won2](https://user-images.githubusercontent.com/95036158/143718807-cfee95d0-8d37-4bf9-93ff-d539b40c2102.jpg)


-Vedio from this game:


https://user-images.githubusercontent.com/95036158/143707161-6420e584-8e13-42da-bce6-ce885a6890e9.mp4

