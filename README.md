Use 2 or more arrays to make a simulation of rain
==================== 
In this assignment, you will make an animation of rain. Since rain is composed of many, many individual rain drops it's best to use arrays to keep track of the drops and their different properties. You may find slides 395 - 440 of the [slide presentation](https://docs.google.com/presentation/d/1fm_Di0qR4HpRWTf8tJtcW3u5by3OrilfXIPZ517K1js/edit?usp=sharing) helpful in completing this assignment.

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
* Make other things "rain", like snowflakes, [characters](https://unicode-table.com/) (like [the Matrix](https://www.youtube.com/watch?v=kqUR3KtWbTk) movies), balloons, bubbles or any other shape. If you use multiple commands to draw whatever is raining down, consider creating a custom function with x and y arguments. 
* You could make your simulation into a raindrop catching game, and remove the raindrops with the [splice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice) function when they are caught.
* Your rain simulation doesn't have to look or work like any other. Look at the samples of student work below for ideas. Have fun and be creative!

Samples of Student Work
-----------------------
[Justin](https://editor.p5js.org/justinlin8/full/_NoWAjJ5L)   
[Sandy](https://editor.p5js.org/satam2/full/amTlccJjC)   
[Alyssa](https://editor.p5js.org/almagtoto-diaz/full/uEG-ebpik)   
[Susanna](https://editor.p5js.org/susannango/full/U13a8kYxG)   
[Noah](https://editor.p5js.org/nospirn/full/AMQILtUo-)   
[Alex](https://editor.p5js.org/alohlenschlager/full/gnXt9QcQa)   
[Noah](https://editor.p5js.org/BiZaark/full/_4OQGMbxV)   
[Andrei](https://editor.p5js.org/anliterato/full/kI2Mna8tK)   
[Justin](https://editor.p5js.org/Daqk1/full/25wqYgJTv)   
[Kathleen](https://editor.p5js.org/kaban/full/v01i-375d)   
[Kaitlyn](https://editor.p5js.org/kaluu/full/kf_JioX0x)   
[Ally](https://editor.p5js.org/alzhao/full/4sLTbneXrG)   
[Brendan](https://editor.p5js.org/brkanaley/full/LTt6vKnOe)   
[Pansy](https://editor.p5js.org/pakuang/full/7PGqSWm8j)   
[Jasmine](https://editor.p5js.org/jaguan4/full/Odhznn2Nc)   
[McKayla](https://editor.p5js.org/mcma/full/Bfwgk_0rL)   
[Jocelyn](https://editor.p5js.org/jocelynpang/full/fPGp7uOnl)   
[Yeshi](https://editor.p5js.org/yesherpa/full/G1XnHmr1W)   
[Linen](https://editor.p5js.org/lifeng/full/eFE4Lsjtu)   
[Isaac](https://editor.p5js.org/ischu/full/B_uKO5F03)   
[Hao](https://editor.p5js.org/hatang/full/BiXp_T9NF)   
[Jeffrey](https://editor.p5js.org/JeffreyLin/full/8DcNzKfB9)   
[Patrick](https://editor.p5js.org/payao/full/v40zm5WSt)   
[Kahlo](https://editor.p5js.org/kafriel-asay/full/w65pvGuJE)   
[Theo](https://editor.p5js.org/thruefli/full/iFa9P6bbB)   
[Tennyson](https://editor.p5js.org/Tennyson/full/BGtM_M-gr)   
[John](https://editor.p5js.org/joieng/full/vi-87ghDW)   
[Alejandro](https://preview.p5js.org/alaguilar5/present/MxO_GMkef)   
[Celine](https://editor.p5js.org/ceyuen/present/WuiiCV97b)   
[Emerson](https://preview.p5js.org/Hello_its_Emerz/present/m1g_aOLk7)   
[Cali](https://preview.p5js.org/cacasanas/present/3OC8OUcTH)   
[Joanne](https://editor.p5js.org/joguan/present/38dB5dKKS)   
[Margaux](https://preview.p5js.org/Mabarahonaventura/present/UYcX6uLJY)   
[Naomi](https://editor.p5js.org/nakung/present/AlAFUQBlo)   
[Jennie](https://editor.p5js.org/jilin20/present/X8a1q4YRp)   
[Supath](https://editor.p5js.org/sugurung/present/BMoS2r4jh)   
[Emely](https://editor.p5js.org/emsarcenobravo/present/I1xsBDRmw)   
[Tiffany](https://preview.p5js.org/ticaballero/present/dPJFhD4P0)   
[Alice](https://preview.p5js.org/alliang/present/IDSuolMu1)   
[Erick](https://preview.p5js.org/erchan8/present/iqt8_V7zA)   
[Oliver](https://preview.p5js.org/Oliver312/present/MlQmGLaLf)   
[Eden](https://preview.p5js.org/edhuang7/present/voX9Wmv-k)   
[Jaden](https://preview.p5js.org/jalee13/present/hZzjGCIjN)   
[Justin](https://editor.p5js.org/juwu14/present/tc5mrsX36)   
[Vivian](https://preview.p5js.org/viliu2/present/-iA5qUQqO)   
[Douglas](https://preview.p5js.org/dolwin/present/X_9uQxe-4)    
[Kimi](https://preview.p5js.org/kinorway/present/llGxir7yr7)   
[Christina](https://editor.p5js.org/chchan10/present/YgRjjan8E)   
[Juan](https://editor.p5js.org/jucalvohuerta/present/4tpWriGlj)   
[Sean](https://editor.p5js.org/sewong3/present/1q7G9UBzc)   
[Sally](https://editor.p5js.org/sahong3/present/WUN2K9US8)   
[Jason](https://editor.p5js.org/jawong32/present/R499Ja2oK)   
[Tiffany](https://editor.p5js.org/titse/present/jwLonv5rU)   
[Michelle](https://editor.p5js.org/michelle0/present/4P4Qu-yT9)    
[Robin](https://editor.p5js.org/rowin/present/mB2bwQ5hf)   
[Lillian](https://editor.p5js.org/litang/present/W_GoRGooS)   
[Cameron](https://editor.p5js.org/canguyen1/present/yZlI52ZpR)   
[Keneth](https://editor.p5js.org/kelee20/present/_xw8d2B-p)   
[Eliot](https://editor.p5js.org/elchen/present/5NuEKVqZ3)   
[Adam](https://editor.p5js.org/adamgooch/present/3pGjjTdcf)   
[Emely](https://editor.p5js.org/emsarcenobravo/present/I1xsBDRmw)   
[Tushig](https://editor.p5js.org/Tushig.itgel/present/wDM-1HItD)   
[Paolo](https://editor.p5js.org/paolo415/present/80sh9S8zD)   
[Frank](https://editor.p5js.org/frshi/present/EULzXU7_h)   
[Ken](https://editor.p5js.org/Keshfer/present/ByaosJqGO)   
[Leah](https://editor.p5js.org/leahcochrum/present/Adg2P-k4b)   
[Abigail](https://editor.p5js.org/abupton/present/BdmAYYdZc)    
[Ailsa](https://editor.p5js.org/aiyale/present/Sm6zmfMKI)   
[Tobias](https://editor.p5js.org/tozuercher/present/E57V5LADh)   
[Tommy](https://editor.p5js.org/toyu3/present/tn4LS0hrOx)   
[Damian](https://editor.p5js.org/dabogdon/present/AGMjeSXNu)   
[Kami](https://editor.p5js.org/kawang7/present/X6ZUwXJXd)   
[Josh](https://editor.p5js.org/joshuapaza/present/mSRUlkVIg)   
[Diego](https://editor.p5js.org/disurasalvador/present/fStMOcnjjM)   
[Juan](https://editor.p5js.org/jucalvohuerta/present/4tpWriGlj)   
[Elvin](https://editor.p5js.org/elli1/present/kNo7XO6T2)   
[Irisa](https://editor.p5js.org/irchu1/present/FkLzNribp)   
[Tommy](https://editor.p5js.org/Touyen/present/0q-4MqhLx)   
[Eva](https://editor.p5js.org/evmartinez/present/R98PHCvfG)   
[Afraz](https://editor.p5js.org/afshaikh/present/LSfoofDky)   
[Ashton](https://editor.p5js.org/ashan-voltaic/present/S-6qNtZ8p)   
[Niko](https://editor.p5js.org/NikoTsu/present/Eqe0svqe4)    
[Michael](https://editor.p5js.org/mimui/present/Gw8MZ2FAx)   
[Melissa](https://editor.p5js.org/metam3/present/ctKyOoo5Z)   
[Pyry](https://editor.p5js.org/pymiettinen/present/B08VigQ3d)   
[Audrey](https://editor.p5js.org/AudreyLau8/present/xsHqkc8BOK)   
[Ben](https://editor.p5js.org/bewong4/present/YfUA_Ey9p)    
[Benjamin](https://editor.p5js.org/benhan/present/H8nMbM33B)   
[Olivia](https://editor.p5js.org/olgutierrez1/present/ozILTyd8n)   
[Liam](https://editor.p5js.org/lizito/present/zdbsTYGL8)   
[Tyler](https://editor.p5js.org/tylee2/present/wrO28FOcH)   
[Marissa](https://editor.p5js.org/maholmes/present/3m06nKRKf)   
[Brian](https://editor.p5js.org/brsen/present/YKPpaCvkL)   
[Tommy](https://editor.p5js.org/tohang/present/Mtb1SRVll)   
[Rachel](https://editor.p5js.org/raroyer/present/zc7CyH8Tt)   
[Karla](https://editor.p5js.org/kanguyen/present/A4ceHiL_N)   
[Tuan](https://editor.p5js.org/tuduong1/present/Tn03zZ_MJ)   
[Azalea](https://editor.p5js.org/Azalea/present/Z5sVVRCZi)   
   
      
*This assignment is based on a [Khan Academy computer science project](https://www.khanacademy.org/computing/computer-programming/programming/arrays/pp/project-make-it-rain)*         

