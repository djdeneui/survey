# HTML

## HTML stands for hypertext markup language.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Tabletop Games Survey Form</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1 id="title">Tabletop Games Survey</h1>
    <p id="description">Please fill out the information and best describe your favorite tabletop game experiences.</p>
    <form id="survey-form">
      <fieldset>
        <label id="name-label" for="name">Name: <input id="name" name="name" type="text" placeholder="First and Last Name" required></label>
        <label id="email-label" for="email">Email: <input id="email" name="email" type="email" placeholder="ilovegames@email.com" required></label>
        <label id="number-label" for="number">Age:<input id="number" name="Age" type="number" min="10" max="120" placeholder="10+" required /></label>
      </fieldset>

      <fieldset form="form-group">
        <legend>Favorite Tabletop Game Style</legend>

        <input id="board-games" type="radio" name="option" class="inline" value="game-style" checked>
        <label for="board-games" class="inline">Board Games</label>

        <input id="card-games" type="radio" name="option" class="inline" value="game-style"> 
        <label for="card-games" class="inline">Card Games</label>
        <br>
        <input id="role-playing-games" type="radio" name="option" class="inline" value="game-style">
        <label for="role-playing-games" class="inline">Role-Playing Games</label>
      </fieldset>

      <fieldset>
        <legend>Select at least 3 Top Favorite Tabletop Game Genres:</legend>
        <label for="dexterity"><input value="dexterity" type="checkbox" name="dexterity" class="inline" checked />Dexterity</label>
        <label for="dungeon-crawler"><input value="dungeon-crawler" type="checkbox" name="dungeon-crawler" class="inline" />Dungeon Crawler</label>
        <label for="social-deduction"><input value="social-deduction"id="social-deduction" type="checkbox" name="social-deduction" class="inline" />Social Deduction</label>
        <label for="deck-builder"><input value="deck-builder" id="deck-builder" type="checkbox" name="deck-builder" class="inline" />Deck Builder</label>
        <label for="eurogame"><input value="eurogame" id="eurogame" type="checkbox" name="eurogame" class="inline" />Eurogame</label>
        <label for="strategy"><input value="strategy" id="strategy" type="checkbox" name="strategy" class="inline" />Strategy</label>
        <label for="other"><input value="other" id="other" type="checkbox" name="other" class="inline" />Other (specify below):<input type="text"></input></label>
        
      </fieldset>

      <fieldset>
        <label for="dropdown">What time of day do you play?
          <select id="dropdown" name="Time you play">
            <option value="">(select one)</option>
            <option value="1">Morning</option>
            <option value="2">Afternoon</option>
            <option value="3">Evening</option>
            <option value="4">Other</option>
          </select>
        </label>
        <label for="bio">If "Other" please explain:
          <textarea id="bio" name="bio" rows="3" cols="30" placeholder="I play from evening until midnight..."></textarea>
        </label>
      </fieldset>

      </label>
      <input id="submit" type="submit" value="Submit" />
    </form>
  </body>
</html>

** end of undefined **

** start of undefined **

body {
  width: 100%;
  height: 100vh;
  margin: 0;
  background-color: #1b1b32;
  color: #f5f6f7;
  font-family: Tahoma;
  font-size: 16px;
}

h1, p {
  margin: 1em auto;
  text-align: center;
}

form {
  width: 60vw;
  max-width: 500px;
  min-width: 300px;
  margin: 0 auto;
  padding-bottom: 2em;
}

fieldset {
  border: none;
  padding: 2rem 0;
  border-bottom: 3px solid #3b3b4f;
}

fieldset:last-of-type {
  border-bottom: none;
}

label {
  display: block;
  margin: 0.5rem 0;
}

input,
textarea,
select {
  margin: 10px 0 0 0;
  width: 100%;
  min-height: 2em;
}

input, textarea {
  background-color: #0a0a23;
  border: 1px solid #0a0a23;
  color: #ffffff;
}

.inline {
  width: unset;
  margin: 0 0.5em 0 0;
  vertical-align: middle;
}

input[type="submit"] {
  display: block;
  width: 60%;
  margin: 1em auto;
  height: 2em;
  font-size: 1.1rem;
  background-color: #3b3b4f;
  border-color: white;
  min-width: 300px;
}

input[type="file"] {
  padding: 1px 2px;
}

.inline{
  display: inline; 
}


** end of undefined **
