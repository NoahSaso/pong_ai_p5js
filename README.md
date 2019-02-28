pong_ai_p5js
============

Simple pong game used to train an AI using the [NEAT](https://en.wikipedia.org/wiki/Neuroevolution_of_augmenting_topologies) algorithm (with [Neataptic](https://github.com/wagenaartje/neataptic)) written in p5js.

Mess with it here:

[https://noahsaso.github.io/pong_ai_p5js](https://noahsaso.github.io/pong_ai_p5js)

Instructions
============

Click `Play Trained AI` button at the bottom of the page to play my trained AI.

The right paddle will follow your mouse, and the left paddle is controlled by the AI.

Update
======
This was a cool experiment, but the way it was setup never really allowed it to learn how to win or maximize efficiency. This is because each AI played against itself, so instead of trying to beat itself, which would prevent its score to increase, the AI would learn to keep the game going. This is bad. My original intention was to create an efficient AI that attacked, not just defended. I'm forking this repository to train AI against OTHER AI to hopefully make a smarter Pong player.
