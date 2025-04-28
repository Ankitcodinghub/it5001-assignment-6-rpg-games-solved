# it5001-assignment-6-rpg-games-solved
**TO GET THIS SOLUTION VISIT:** [IT5001 Assignment 6-RPG games Solved](https://www.ankitcodinghub.com/product/it5001-assignment-6-rp-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119246&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IT5001 Assignment 6-RPG games Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
We play a lot of RPG games nowadays like Final Fantasy, World of Warcrafts or DOTA. In this assignment, you are going to implement the characters for a turn-based RPG.

(If you are not familiar with turn-based RPG, please google or reference to this: https://www.gamasutra.com/blogs/FelipePepe/20170922/305783/The_Art_of_TurnBased_RPGs_I_Menubased_bat tles.php)

Overview

The game is a fight between two teams of adventurers formed by different types of characters (the jargon should be “classes” but I do not want to be confused with the “class” in Python). You are given a battle system that can let two teams fight each other until one team won by destroying all the characters in the other team. The good thing is that, the battle system is already implemented for you. You only have to implement some new types of characters. You can choose to run the file battle.py to start the game and try it out.

Game System

• You are given some amount of gold (The default setting is 200 gold in the skeleton file)

• Every type of characters has a cost and you can recruit a team with any combinations of them within your budget. And each team has to use up all the gold to form.

• A random team formed by createRandTeam() will create a team as your enemy. Then you can recruit your own team by choosing available type of characters by the function userChooseTeam(). In the battle, you will be Team A and your enemy will be Team B.

Battle System

• Once the battle starts, each team will take turns to act. However, one character can perform an action for one turn. A character will be chosen at random within those are still alive in the team and he will perform an action targeted at a random enemy that is alive. (randAlive()). However, the last class Necromancer has an ability to “target” your own team also!

• So, when a character acts, he will hurt a targeted enemy (and the enemy got hurt by gotHurt() ). When the targeted enemy’s hp (hitpoint) drops to zero, he will be dead and no longer acts…. unless, a necromancer revives him afterwards.

A typical start of the battle is shown in the next page. And the file “sample gameply.txt” stores the log of a full battle for you to reference to.

THE BATTLE STARTS!!!!!

Round 1

Team A:

Members: | Fighter| Mage|Necromancer| Fighter

Hitpoints: | 1200| 800| 800| 1200

Strength: | 100| | | 100

Max. Mana: | | 50| 50| Currnet M: | | 50| 50|

Team B:

Members: | ArchMage| Berserker

Hitpoints: | 800| 1200

Strength: | | 100

Max. Mana: | 50|

Currnet M: | 50|

Team A member 0 Fighter acts

Hurt enemy 1 by damage 100.

Berserker hurt with remaining hp 1100.

Team A:

Members: | Fighter| Mage|Necromancer| Fighter

Hitpoints: | 1200| 800| 800| 1200

Strength: | 100| | | 100

Max. Mana: | | 50| 50| Currnet M: | | 50| 50|

Team B:

Members: | ArchMage| Berserker

Hitpoints: | 800| 1100

Strength: | | 100

Max. Mana: | 50|

Currnet M: | 50|

Team B member 0 ArchMage acts

Strike enemy 3 with spell

Fighter hurt with remaining hp 800.

Round 2

Team A:

Members: | Fighter| Mage|Necromancer| Fighter Hitpoints: | 1200| 800| 800| 800

Strength: | 100| | | 100

Max. Mana: | | 50| 50| Currnet M: | | 50| 50|

Team B:

Members: | ArchMage| Berserker

Hitpoints: | 800| 1100

Strength: | | 100

Max. Mana: | 50|

Currnet M: | 30|

Team A member 0 Fighter acts

Hurt enemy 0 by damage 100.

ArchMage hurt with remaining hp 700.

(and the battle goes on….)

Character Classes

We will have five different character classes, namely, Fighter, Mage, Berserker, ArchMage and Necromancer.

Fighter (Given)

A Fighter has a maximum hp of 1200 and strength 100. He has a cost of 100 gold. During each turn in the battle, he will select a random enemy and inflict a damage equal to his strength, i.e. 100 hp.

Mage (Given)

Here is the statistics for a mage:

Max HP Max Mana Intelligence Cost

800 50 400 200

He will cast a spell in his turn and make a damage that is equal to his intelligence. However, casting a spell needs 20 mana. If his remaining mana is less than that, he will take the turns to meditate to gain a recovery of 30 mana points instead. Namely, he will not cast a spell to hurt an enemy on that turn.

The above two classes are already implemented for you. Your task is to implement the next three classes.

Berserker

A Berserker is a Fighter but he costs 200 gold. However, if his hit point is lower than or equal to half of his maximum hp, he will enter the “berserk mode” and his strength will be doubled to 200.

Sample output:

ArchMage

An ArchMage is a Mage but he costs 600. However, if he is the only one alive in his own team, he will cast the special spell KABOOM and it inflicts EVERY enemy alive with a damage of double of his intelligence, i.e. 800 hp!!! However, this KABOOM spell also needs 20 mana to cast. Meaning, he has to waste a turn to meditate if his mana is lower than

20.

Sample output:

Necromancer

A Necromancer is a Mage but he costs 400. However, if there are some dead members in his own team, he can cast a spell “raise dead” with 20 mana to revive a random dead team member and recover him half of his maximum hit point, instead of hurting his enemy in his turn.

Sample output:

Your Tasks

Your job is to implement the three remaining classes with inheritance. You are given three files:

characters.py

This is the major file you have to add your code. The two base classes of Fighter and Mage are implemented for you. If you read the code, you noticed that they are two sub-classes of the class Character.

You will notice there is a function dprint() and every output line is using that instead of print(), in which, it’s controlled by the variable printActionDescription. If it’s True, their actions will be printed or silence otherwise. You should add your classes as an inheritance of the classes Fighter and Mage WITHOUT changing the two base classes. Namely, you should only ADD code to this file instead of changing anything (other than the variable printActionDescription for your own testing.) battle.py

This is where the “game engine” is. Basically, the whole system is implemented for you and you do not have to do any big changes. The changes you need to do should be:

• Increase the value of nCharType if you have implemented more character type(s) (probably one by one)

• The two parts with the comments “You should uncomment the following….” in the two functions createChar() and userChooseTeam(). However, you should just uncomment those lines instead of changing them.

• Your game should work also if you can use more than 600 gold. My testing code will use 1500 gold.

• The second argument of the function gameStart(). If it’s True, the game will pause for every turn. Otherwise, it will run until the battle ends.

team.py

You should not change this file. But you should read the implementation because the helper functions will be useful to you.

Submission

You should only copy and paste the classes for the three new characters into coursemology from the file characters.py. And there will be no testing feedback for you because the game is random.

Tips

• Design before you implement. Plan out your class inheritance diagram before you code, especially what are commons or not in each of the class relationship

• Implement one class at a time

• Make good use of the pause and dprint().

• Make backup from time to time. Especially a copy of your code for each new character type you implemented

• You cannot do any hard-coding. And you have to follow the way of OOP instead using other ways to get around, e.g. checking the Character’s name to choose what to do

Extra Tasks

I guess the assignment is hard enough but please try the following. (However, it’s only for fun.)

Finding the Best Team

If you are really the designer for a game, you want to know what is the best formation of your team. Is it better to use a team of Fighters or Mage, or some combinations of both? Design some experiment/code/testing to find out the best few teams (e.g. the first 5 best teams) for a certain gold allowance. For example, if you have 600 gold, what is the best team? You should be able to find out the best team for more gold, e.g. 1200 gold

Adding New Classes

Add two of the following classes:

• Ranger: Can randomly perform what a Fighter and a Mage do.

• Assassin: He can poison one targeted enemy. So whenever that enemy acts, he will lose %20 of his maximum hit point. But it only last for three times (three times the enemy acts, if the enemy is not selected at the turn of the enemy team, that enemy will not get hurt from poison.) And the poison effect will disappear if the enemy died even there are more remaining rounds to go

• Bard: He will not do any damage. But he will sing a song in his turn but the next person in his team acts in the next turn, the effect will be doubled except a bard, e.g. double damage, raise two dead members.

Or some other classes of your own design! But they must be complicated enough. Requirements are, one class must use multiple inheritance and the other needs some non-trivial modification of a certain base class. Or polymorphism. You can consult me before you do it.

Battle Formation

So far, it does not matter for a character in any “position” in the team. The more interesting way to do it is to divide the team into the front row and the back row as a formation (or more rows?!). Impose some rules based on the roll, e.g. a fighter can attack only if he is at the front row and he can attack an enemy on the front row only, unless the whole front roll of his enemy team died, but a Mage type of character can attack any row of his enemy. (Or you can design a class called Archer as a Fighter who can attack from the back roll.)
