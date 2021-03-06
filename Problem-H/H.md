# Problem H: Straights
In poker, a straight is a continuous sequence of cards, in this case of any length. Your friend John makes up a game called straights which is played with <img src="https://render.githubusercontent.com/render/math?math=N"> cards with numbers that may repeat, between <img src="https://render.githubusercontent.com/render/math?math=1"> and <img src="https://render.githubusercontent.com/render/math?math=10^4">. In order to win, you must get rid of all of your cards in as little turns as possible. The only way to put down more than 1 card at a time is if the cards are strictly in descending or ascending order.

For example, given eight cards with the numbers: `1 8 3 6 5 7 2 1`, the minimum number of turns to get rid of all of your cards would be: `3` because you would have 2 straights: `1 2 3` and `5 6 7 8` and a single card: `1` left over.

Can you find the minimum number of turns required for you to win?

## Input
Input consists of two lines. The first contains the number of cards that you are given <img src="https://render.githubusercontent.com/render/math?math=N (1≤N≤10^4)">. The second line consists of <img src="https://render.githubusercontent.com/render/math?math=N"> space separated integers each with a different value between <img src="https://render.githubusercontent.com/render/math?math=1"> and <img src="https://render.githubusercontent.com/render/math?math=10^4">.

## Output
Output the minimum number of turns to win.

<table>
<thead>
  <tr>
    <th>Sample Input</th>
    <th>Sample Output</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>
<pre>
8
1 8 3 6 5 7 2 1 
</pre>
    </td>
    <td>
<pre>
3
</pre>
    </td>
  </tr>
</tbody>
</table>
