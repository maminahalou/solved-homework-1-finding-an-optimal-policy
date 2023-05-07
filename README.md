Download Link: https://assignmentchef.com/product/solved-homework-1-finding-an-optimal-policy
<br>
<h2>Problem</h2>

<h3>Description</h3>

The game DieN is played in the following way.

Consider a die with N sides (where N is an integer greater than 1) and a nonempty set B of integers. The rules of the game are:

<ol>

 <li>You start with 0 dollars.</li>

 <li>Roll an N-sided die with a different number from 1 to N printed on each side.

  <ol>

   <li>If you roll a number not in B, you receive that many dollars. (eg. if you roll the number 2 and 2 is not in B, then you receive 2 dollars.)</li>

   <li>If you roll a number in B, then you lose all of your obtained money and the game ends.</li>

  </ol></li>

 <li>After you roll the die (and don’t roll a number in B), you have the option to quit the game. If you quit, you keep all the money you’ve earned to that point. If you continue to roll, go back to step 2.</li>

</ol>

<h3>Procedure</h3>

<ul>

 <li>For this problem, determine an optimal policy for playing the game DieN with N sides. You will be given N and an array B (isBadSide) which indicates which sides are bad. The policy should depend on your current bankroll.</li>

 <li>What is the expected value of this game if you follow an optimal policy? Answer for the problems you are given in the <u>​</u><u>Solve for Code</u><u>​ </u></li>

</ul>

<h2>Examples</h2>

The following examples can be used to verify your calculation is correct.

<ul>

 <li>Input: N = 21, isBadSide = {1,1,1,1,0,0,0,0,1,0,1,0,1,1,0,1,0,0,0,1,0}, Output: 7.3799</li>

 <li>Input: N = 22, isBadSide = {1,1,1,1,1,1,0,1,0,1,1,0,1,0,1,0,0,1,0,0,1,0}, Output: 6.314</li>

</ul>

1







<ul>

 <li>Input: N = 6, isBadSide = {1,1,1,0,0,0}, Output: 2.5833</li>

</ul>

<h2>Resources</h2>

The concepts explored in this homework are covered by:

<ul>

 <li>Lectures

  <ul>

   <li>Lesson 1: Smoov &amp; Curly’s Bogus Journey</li>

  </ul></li>

 <li>Readings

  <ul>

   <li>Littman (1996)(​ ​chapters 1-2)</li>

  </ul></li>

</ul>