Use 2 or more arrays to make a simulation of rain
==================== 
In this assignment, you will make an animation of rain. Since rain is composed of many, many individual rain drops it's best to use arrays to keep track of the drops and their different properties. You may find slides 363 - 401 of the [slide presentation](https://docs.google.com/presentation/d/1fm_Di0qR4HpRWTf8tJtcW3u5by3OrilfXIPZ517K1js/edit?usp=sharing) helpful in completing this assignment.

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
* Add a little bit of randomness so the drops "wiggle" a bit as they fall
* Make other things "rain", like snowflakes, [characters](https://unicode-table.com/) (like [the Matrix](https://www.youtube.com/watch?v=kqUR3KtWbTk) movies) or any other shape. If you use multiple commands to draw whatever is raining down, consider creating a custom function with x and y arguments. 
* Your rain simulation doesn't have to look or work like any other. Look at the samples of student work below for ideas. Have fun and be creative!

Samples of Student Work
-----------------------
[Jennie](https://editor.p5js.org/jilin20/present/X8a1q4YRp)   
[Justin](https://editor.p5js.org/juwu14/present/tc5mrsX36)   
[Christina](https://editor.p5js.org/chchan10/present/YgRjjan8E)   
[Juan](https://editor.p5js.org/jucalvohuerta/present/4tpWriGlj)   
[Sally](https://editor.p5js.org/sahong3/present/WUN2K9US8)   
[Jason](https://editor.p5js.org/jawong32/present/R499Ja2oK)   
[Michelle](https://editor.p5js.org/michelle0/present/4P4Qu-yT9)    
[Cameron](https://editor.p5js.org/canguyen1/present/yZlI52ZpR)   
[Keneth](https://editor.p5js.org/kelee20/present/_xw8d2B-p)   
[Eliot](https://editor.p5js.org/elchen/present/5NuEKVqZ3)   
[Robin](https://editor.p5js.org/rowin/present/Qxar0uiJ5)   
[Emely](https://editor.p5js.org/emsarcenobravo/present/I1xsBDRmw)   
[Tushig](https://editor.p5js.org/Tushig.itgel/present/wDM-1HItD)   
[Frank](https://editor.p5js.org/frshi/present/EULzXU7_h)   
[Abigail](https://editor.p5js.org/abupton/present/BdmAYYdZc)    
[Tobias](https://editor.p5js.org/tozuercher/present/E57V5LADh)   
[Tommy](https://editor.p5js.org/toyu3/present/tn4LS0hrOx)   
[Kami](https://editor.p5js.org/kawang7/present/X6ZUwXJXd)   
[Juan](https://editor.p5js.org/jucalvohuerta/present/4tpWriGlj)   
[Elvin](https://editor.p5js.org/elli1/present/kNo7XO6T2)   
[Irisa](https://editor.p5js.org/irchu1/present/FkLzNribp)   
[Tommy](https://editor.p5js.org/Touyen/present/0q-4MqhLx)   
[Afraz](https://editor.p5js.org/afshaikh/present/LSfoofDky)   
[Ashton](https://editor.p5js.org/ashan-voltaic/present/S-6qNtZ8p)   
[Niko](https://editor.p5js.org/NikoTsu/present/Eqe0svqe4)    
[Michael](https://editor.p5js.org/mimui/present/Gw8MZ2FAx)   
[Melissa](https://editor.p5js.org/metam3/present/ctKyOoo5Z)   
[Pyry](https://editor.p5js.org/pymiettinen/present/B08VigQ3d)   
[Audrey](https://editor.p5js.org/AudreyLau8/present/xsHqkc8BOK)   
[Ben](https://editor.p5js.org/bewong4/present/YfUA_Ey9p)    
[Benjamin](https://editor.p5js.org/benhan/present/H8nMbM33B)   
[Liam](https://editor.p5js.org/lizito/present/zdbsTYGL8)   
[Tiffany](https://editor.p5js.org/titse/present/jwLonv5rU)   
[Tyler](https://editor.p5js.org/tylee2/present/wrO28FOcH)   
[Marissa](https://editor.p5js.org/maholmes/present/3m06nKRKf)   
[Brian](https://editor.p5js.org/brsen/present/YKPpaCvkL)   
[Tommy](https://editor.p5js.org/tohang/present/Mtb1SRVll)   
[Rachel](https://editor.p5js.org/raroyer/present/zc7CyH8Tt)   
[Karla](https://editor.p5js.org/kanguyen/present/A4ceHiL_N)   
[Tuan](https://editor.p5js.org/tuduong1/present/Tn03zZ_MJ)   
[Azalea](https://editor.p5js.org/Azalea/present/Z5sVVRCZi)   
   
      
*This assignment is based on a [Khan Academy computer science project](https://www.khanacademy.org/computing/computer-programming/programming/arrays/pp/project-make-it-rain)*         

