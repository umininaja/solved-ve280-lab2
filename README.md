Download Link: https://assignmentchef.com/product/solved-ve280-lab2
<br>
<h1>Ex1. Eratosthenes Sieve</h1>

<strong>Problem</strong>: At last, Kyon discovered that 775249 is the product of 179, 61 and 71, which are exactly Koizumi’s height, weight and waistline. Now Kyon is wondering whether these three numbers are prime numbers. To make things general, given a sequence of integers within a certain range, he wants to find out all the prime numbers without changing their order. Please help him implement a program to complete this task.

<strong>Requirement</strong>: To check if an integer is a prime, intuitively we can achieve that by dividing integers smaller than itself. However, there is a more efficient algorithm called Eratosthenes Sieve , and you are required to implement it for this exercise. The algorithm works as follows:

<ol>

 <li>For all integers within given range, mark them as prime</li>

 <li>For 0 and 1, mark them as not prime</li>

 <li>Find the next smallest integer i that is marked as prime</li>

 <li>For all integers that can be divided by i , mark them as not prime</li>

 <li>Repeat Steps 3-4 until no more i can be found in Step 3</li>

</ol>

After running the above algorithm, you have generated a lookup table. To check if a given integer is a prime, simply check that lookup table and see if it is marked as prime or not.




<strong><u>Ex2. Which Building Will Be Destroyed?                                             </u></strong>

<strong>Problem</strong>: Unfortunately, Kyon’s action of Hiding Photos was discovered by Haruhi. Haruhi got so angry that she unconsciously dragged Kyon into a closed space where a celestial was destroying the buildings. The celestial’s action could be predicted as follow:

<ol>

 <li>Equally divide the square into 4 smaller squares, and the left-upper part will all be destroyed.</li>

 <li>For each of the remaining 3 smaller squares, also divide them into 4 smaller squares, and the left-upper part will be destroyed</li>

 <li>Repeat until the square can no longer be divided</li>

</ol>

Suppose you are Kyon, you need to write a program to calculate which buildings will be destroyed in order to save your own life.




<h1>Ex3. Strength Ranking</h1>

<strong>Problem</strong>: Finally, Kyon successfully escaped from the closed space by kissing Haruhi. The huge celestial really reminded Kyon of the big giants in <em>Attack on Titan</em>, so he invited Haruhi to watch this anime together. However, they had a intense debate about whether Mikasa or Levi was stronger. They finally decided to rank the soldiers in the Survey Group by the sum of their combat, initiative and wits ability grades. If two soldiers have the same sum grades, just keep the order the same as in the input. Please write a program for them to help them with the rank.

<strong>Output Format</strong>: Soldiers sorted in descending total score.




<h1>Files</h1>

<ol start="2">

 <li><em>pdf</em>: description in pdf</li>

 <li><em>zip</em>: starter files</li>

</ol>