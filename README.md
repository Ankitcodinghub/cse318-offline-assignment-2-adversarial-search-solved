# cse318-offline-assignment-2-adversarial-search-solved
**TO GET THIS SOLUTION VISIT:** [CSE318 Offline Assignment 2-Adversarial Search Solved](https://www.ankitcodinghub.com/product/cse318-offline-assignment-2-adversarial-search-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96937&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE318 Offline Assignment 2-Adversarial Search Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Adversarial Search

The task of this assignment is to implement a game player which uses adversarial search algorithms to play a two player game. The game we shall consider here is Mancala.

Your implementation would include a minimax algorithm with alpha-beta pruning. You also need to

<ul>
<li>● &nbsp;Experiment with different search strategies (e.g., iterative deepening search).</li>
<li>● &nbsp;Experiment by varying depth-limits and changing move-ordering.
Moreover, you need to implement various heuristics and find out which one is better by running experiments. Determine the win-loss ratio by running 100 games with computer vs computer autoplay. Keep the experiment results and show during the evaluation process.

A heuristic function estimates how good a particular state is for a player. A number of factors determine whether a given state of the game is good for a player.

How to Play:

In Mancala, the board consists of six (6) bins on each side, and a home position (called storage) on the right of the bins. The board is laid out typically starting with four stones in each bin and both storage bins empty.

The following link contains a description of the rules of Mancala.

https://www.thesprucecrafts.com/how-to-play-mancala-409424

You can play Mancala online from one of the following links to get acquainted with it.

https://www.mathsisfun.com/games/mancala.html https://www.mathplayground.com/mancala.html

Mancala Heuristics:

For Mancala, the following strategic factors can be used to design a good heuristic to determine how

favorable a particular position is for a player:
</li>
</ul>
<ol>
<li>First valid move [furthest valid bin ( a bin on my side which is not empty) from my storage]</li>
<li>How far ahead of my opponent I am now [the difference in stone count between my storage and opponent’s storage]</li>
<li>How close I am to winning (If my storage is already close to containing half of total number of stones)</li>
<li>How close opponent is to winning</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
<ol start="5">
<li>The total number of stones residing in the six bins of my side</li>
<li>The total number of stones residing in the six bins of opponent’s side</li>
<li>Number of stones close to my storage ( a stone, although residing in a bin on my side,
is not close to my storage, if it is going to be overflowed to my opponent’s side )
</li>
<li>Number of stones close to my opponent’s storage</li>
<li>Have I earned an extra move</li>
<li>Have I captured any stone</li>
</ol>
You have to experiment with six heuristics including the following three (i.e., define three of your own heuristics):

Heuristic-1: The evaluation function is (stones_in_my_storage – stones_in_opponents_storage)

Heuristic-2: The evaluation function is

W1 * (stones_in_my_storage – stones_in_opponents_storage) + W2 * (stones_on_my_side –

stones_on_opponents_side)

Heuristic-3: The evaluation function is

W1 * (stones_in_my_storage – stones_in_opponents_storage) + W2 * (stones_on_my_side –

stones_on_opponents_side) + W3 * (additional_move_earned)

How to represent:

At the end, your code will give the user to play with the computer. After each move (either by human or by the computer), you need to show the updated state of the board. You can do it in the normal output console. But it would be better if you can make a small implementation in GUI.

Additional Resources for Adversarial Search:

You can learn more about Adversarial Search in Chapter 5 (5.1 to 5.4) of the book “Artificial Intelligence A modern Approach (Third Edition)” by Stuart Russell and Peter Norvig

&nbsp;

</div>
</div>
</div>
</div>
