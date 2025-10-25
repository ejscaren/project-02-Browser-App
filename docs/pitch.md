<h3>Pitch</h3>
<hr>
<p>The plan is to make a 2d game that has the player shoot at enemies and get a score. This score will then update a leaderboard that is showcased on the title. 
  The user will control the player and have a competitive battle against the enemies. Upon death the score is reset and players will restart.</p>
  <br>
<p>Players name and score will be tracked with local storage, for fast login, and on the leaderboard, so they will be reconized. I will use public API to have some sort of 
tailored scene for users. Jsonbin will store and update leaderboard.</p>
<br>
<p>Public get: JokeAPI https://sv443.net/jokeapi/v2/</p>
<p>Request will supply joke for title screen everytime on reload.</p>
<br>
<p>JSONbin plan: </p>
<p>Will use variable for name and points scored. Will update when someone scores higher than top 3 scores. Will PUT new score in correct place.</p>
<p>example, {name: x, score: y}</p>
