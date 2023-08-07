<h1>Turn Based RPG (2023)</h1>

<p align="center">
<img src="https://imgur.com/ogAvXHx.png" height="50%" width="50%" alt="Game Opening Screen"/>

<h2>Description</h2>

This project was developed solo for my games development module, during the second semester of my third and final year of my computing sciences degree. We had been set the somewhat ambiguous task of creating a game. I deicded to make a turn based RPG inspired by the likes of the Fire Emblem series and the Mario and Luigi RPG series. The game consists of a single level (orgianlly planned to be three, however the timeframe did not allow for this) with a grid where units and enemies are placed. Breadth first search is used to pathfind on the grid. The player uses their cursor to select a unit, either to display their info, order them to move and/or attack, or leave them in place for the next turn. The mechanics are very similar to the Fire Emblem series, as is the fantasy medieval setting. The game functions on a tile system; a unit or enemy can only exist and move on tiles. These tiles represent their environment. For example, a swamp tile is more costly to move across and a forest tile impacts your accuracy. Should the player loose all of their units, then they loose the game. On the contrary, should they rout the enemy, then they win. The enemies use a rudimentary AI system; during their turn they will pick units to attack based on remaining health, easiest kill and shortest distance to travel. The enemy will navigate and move itself to the unit it chooses to attack, if any.

I was very limited on time to create this game. Moreover, I also had to work on my year long dissertation and other modules. As well as this, I have very little to no experience in areas like art and modeling and was without any team memebers who could support this weakness. Thus, I had to find royalty free assets online and use these for my project. Despite all of my hindrances, I am very happy with what I created; I structured my time management to allow me to research the relevant areas to create this project and more importantly slot it in between the rest of my university work. During this project I was able to familiarise myself with concepts like tweening and asyncronous code, which I have since found useful elsewhere. Feedback from my lecturers can be found below the screenshots.
<br />

<h2>Screenshots:</h2>

<p align="center">
<img src="https://imgur.com/UZ5KrCY.png" height="45%" width="45%" alt="Gameplay"/>
<img src="https://imgur.com/Ha0OF4t.png" height="45%" width="45%" alt="Unit Overview"/>
<img src="https://imgur.com/vVvhOey.png" height="45%" width="45%" alt="Battle Forecast"/>
<img src="https://imgur.com/5IEEhFH.png" height="45%" width="45%" alt="Environment"/>
<img src="https://imgur.com/HBQ7I50.png" height="45%" width="45%" alt="Context Menu"/>
<img src="https://imgur.com/6EWsjRx.png" height="45%" width="45%" alt="Battle Scene"/>
<img src="https://imgur.com/FvsUBCq.png" height="45%" width="45%" alt="Damage"/>
<img src="https://imgur.com/4uulXQj.png" height="45%" width="45%" alt="Enemy Turn"/>

<h2 id="Feedback">Feedback</h2>

My code review was marked by a lecturer who is very familiar with C# and Unity at a score of 18/20. Below is some comments:

* "Good amount of self written code and good use of C# and unity specific
knowledge. Most is self-written."
* "Good use of Unity and C# knowledge (namespaces, interfaces, SerializeField,
etc). Some of your code inherits MonoBehaviour when it does not need to.
Overall very good."
* "Overall development wise is very good, good use of version control, folder
structure, and code. Well done!"

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
