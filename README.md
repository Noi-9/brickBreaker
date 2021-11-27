# brickBreaker
*Project idea*

*A project for IT214 describing the game Breaker and Bricks
So that every time the breaker passes through the bricks it crashes .*
 -control 
* You can control the protection of the ball from falling to the ground
To move it you can use -> left and <- right
* You can change the result increment each time via [this code ](https://github.com/Noi-9/brickBreaker/blob/main/Gameplay.java)
```java
if(ballRect.intersects(brickRect)) {
                            map.setBrickval(0,i,j);
                            totalBricks--;
                            score +=5;
```
