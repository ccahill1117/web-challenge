# Instructions

1. Fork this repo on GitHub.
1. Create a program that can interactively play the game of Tic-Tac-Toe against a human 
   player. 
   * The program should win or draw, but never lose.
   * The human player should make the first move.
   * The program should announce the result of the game before clearing the board for 
     another round of play.
1. Commit early and often, with good messages.
1. Push your code back to GitHub and send us a pull request.

> If you don't want to broadcast your intentions by forking this, feel free to clone it 
  and work locally. Then, send us a tar.gz of your solution, including your `.git` folder 
  so we can see your commit history.

We are more interested in getting a view into how you approach the problem than 
anything else, so a good commit history is vital. 

This isn't a timed test, so don't think of the commit history as being a measure of 
pace - we're not looking at that.
We understand this is something you'll be working on in between other things.
If, for some reason, you feel unable to complete the entire exercise, that's fine.
Just try to give us enough code to look at to get a sense of your approach.

# Implementation Guidelines

Your implementation should meet the following requirements:

* The game logic should be executed server-side (you pick the language/framework but we 
  use a mix Django and Flask in Python).
* The interface for the game should be a JavaScript Single Page App (SPA) running
  in a browser (again, you pick the frameworks/toolchains but we use a mix of React and 
  Angular 1.x).
* You should rewrite this `README.md` to include build/run instructions for your apps 
  (both client and server).

For a little extra credit:

* The SPA should _not_ be hosted by the server-side app, but instead through a separate 
  server process (the client app should be completely standalone).

