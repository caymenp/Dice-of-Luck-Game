# Dice Of Luck - JavaScript Game

You can view a <a href='https://diceofluck.netlify.app/'>live demo of the game here</a>, I have it hosted with Netlify.

<h4>This game is built using HTML, CSS and JS. </h4>
<p>It implements browser DOM manipulation to determine the current player, hold "current" scores and "overall" scores for the players in the game. </p>

<h3>Code Logic Diagram</h3>
<img src="https://github.com/caymenp/diceOfLuck-JS_Game/blob/main/logicDiagram.png">

<h2>Game Rules</h2>
<ul>
  <li>First to 100 -> Wins!</li>
  <li>Players take turns rolling the dice</li>
  <li>You accumulate points during your turn --until--</li>
  <ul>
    <li>You roll a 1 - all accumulated points during that wrong are gone, and your turn is over</li>
    <li>You play it safe and select the "hold" option.</li>
    <li>The hold option allows you to stop your turn, and keep the accumulated points during your turn</li>
  </ul>
  <li>First person to 100 "overall" points, wins!</li>
  </ul>

<h3>Initial Game Start Screen</h3>
<img src="https://github.com/caymenp/diceOfLuck-JS_Game/blob/main/initialGamePage.png">
<h3>During Game Play</h3>
<img src="https://github.com/caymenp/diceOfLuck-JS_Game/blob/main/duringGamePlay.png">
<h3>Winning Player</h3>
<img src="https://github.com/caymenp/diceOfLuck-JS_Game/blob/main/winningGame.png">
