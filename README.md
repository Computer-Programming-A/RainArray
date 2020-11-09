Use 2 or more arrays to make a simulation of rain
====================

In this assignment, you will make an animation of rain. Since rain is composed of many, many individual rain drops it's best to use arrays to keep track of the drops and their different properties. You may find slides 363 - 379 of the [slide presentation](https://docs.google.com/presentation/d/1fm_Di0qR4HpRWTf8tJtcW3u5by3OrilfXIPZ517K1js/edit?usp=sharing) helpful in completing this assginment.

Suggested steps for starting this assignment:
-----------------------------------------------
1. Start a new [P5 program](https://editor.p5js.org/)
2. At the very top of your program, create two arrays that will hold the x and y coordinates of each of the rain drops. For now, each array will only have one value, we'll add more later. Here's an example. (Note that I've used `let` to declare each variable. I could also have used `var`)
```javascript
let xPositions = [200];
let yPositions = [0];
```
3. Add code in the `draw()` function to move and show your raindrop.
4. Add more drops to the arrays. You could do that by using `append` with for a `loop` and `random()` function at the beginning of the program, or using an array modification method during animation. You could even add more drops in response to user interaction.
5. Make the rain continuous by moving the position of each drop back to the top when it reaches the bottom of the canvas using an `if` statement.

Optional Extensions
---------------------
* Make an array of colors, so that every drop is a different color, or an array of speeds.
* Make other things rain, like snowflakes (using more shape commands) or avatars (using the image commands). If you use multiple commands to draw whatever is raining down, consider creating a custom function with parameters instead. Have fun and be creative!

Samples of Student Work
-----------------------
None yet!    
   
      
*This assignment is based on a Khan Academy computer science project*         

