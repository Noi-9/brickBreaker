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

![GameOver](https://user-images.githubusercontent.com/95036158/143690882-f119ee5e-61fe-4628-b99c-c539cc7c4ab8.jpg)

And if you win, you will get this result

![YouWin](https://user-images.githubusercontent.com/95036158/143690993-5016091a-4bca-4045-b2d6-56d3790ff954.jpg)
