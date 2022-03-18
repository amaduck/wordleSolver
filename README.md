# wordleSolver
Wordle solver in HTML / javascript

An exercise to remember how to write javascript, and to learn to use gitHub

An inelegant solution to begin - aims to present all possible solutions to the various wordle-esque games, based on given information

Webpage has 6 sections:
1) Known letters (5 max) - any letters, position of which is known
2) Letters which are known, but not known where. Any solution will be checked to ensure any letters highlighted here are included
3) Letters which don't occur anywhere in the word
4) Individually unavailable letters - eg an A may appear in the word, but definitely not as letter 3
5) Buttons
6) Results section

Each letter has an associated array of potential letters. Code works by checking all potential combinations, first again the array of necessary letters, then against the dictionary
