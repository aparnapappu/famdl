# famdl

It's [Wordle](https://www.powerlanguage.co.uk/wordle/) but for the fam!

[TODO fix] Play it [**here**](https://famdl.net/).

## Introduction

Wordle is a word game similar to the TV show [Lingo](<https://en.wikipedia.org/wiki/Lingo_(British_game_show)>).
This version has a word list of commonly used words in the pappu-bhola-trujjillo family.
You get 6 tries to guess a 5-letter target word. After each guess, the letters light up in various colors as clues. Green means a letter is correct in this spot; yellow means a letter is _elsewhere_ in the target word; gray means a letter is not in the target word at all.

Click _About_ inside the game to learn by example.

## History

In 2021, Josh "powerlanguage" Wardle created _Wordle_, a version of the Lingo word game that you can play once a day. The target word is the same for everyone each day, and you can share results to Twitter and compare with your friends. This made Wordle [go absolutely viral](https://www.nytimes.com/2022/01/03/technology/wordle-word-game-creator.html) around January 2022.



## For developers

You're very welcome to create your own Wordle offshoot/remix based on _hello wordl_. To get started, you can [fork the code](https://docs.github.com/en/get-started/quickstart/fork-a-repo) on GitHub.

To run the code locally, first install [Node.js and npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm#using-a-node-version-manager-to-install-nodejs-and-npm). Then, in this directory, open a terminal and run `npm install` followed by `npm run start`. _famdl_ will be running at http://localhost:3000/. Any changes you make to the source code will be reflected there. Have fun!

Finally, `npm run deploy` will deploy your code to the `gh-pages` branch of your fork, so that everyone can play your version at https://yourname.github.io/famdl (or the name of your fork if you renamed it).
