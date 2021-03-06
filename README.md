# Shmabble
![Shmabble WORD?](http://www.quickanddirtytips.com/sites/default/files/images/5384/Scrabble.jpg)

- [Intro](#intro)
- [Getting Started](#getting-started)
- [Wireframes](#wireframes)
- [Technologies Used](#technologies-used)
- [Userflow](#userflow)
- [MVP](#mvp)
- [Improvements Made](#improvements-made)
- [Todo](#todo)


## Intro & Inspiration
Shmabble is a one player word game againast the clock. Players will make as many words on the board as possible in the alotted time. My inspiration for this game was the [IOS App "2408"] [2048].

## Getting Started
Before starting you will be propted to choose a difficulty. The easier options will give you more time and require less points to beat the game. The more difficult options give less time to get more points. Find a link to pay below. Please make sure to download and turn on the [Allow-Control-Allow-Origin] [cors] plugin for the Chrome browser.

## Rules
* The first word played must have one chip on yellow square in the of the board. 
* All new words have to branch off previous played words. 
* You must play real words. Words will be checked against the glosbe dictionary API. 

[Play Shmabble!](https://jdpeck90.github.io/Shmabble_game/)

## Technologies Used
* [HTML] [html] - Layout
* [CSS] [css] - Styling
* [Javascript] [js] - For interactivity
* [jQuery] [jquery] - Ajax and DOM manipulation

## Userflow
![UserFlowIMG](https://s25.postimg.org/oxjg59bjf/Full_Wire_Frame.png)

## Wireframes
![IntroIMG] [intro]
![GameplayIMG] [gameplay]
![LoseIMG] [lose]
![WinIMG] [win] 


## MVP 
My minimial viable product for this game was having a simple word game web app were users could play against the clock and get points for the words they played. I also wanted a a highscore board that could hold scores with local storage. 

## Improvements Made
* Connected this app to the glosbe online dictionary api to check if the played words are in the dictionary.
* Wrote an algorithm to make sure that the letters played are in the same row or column. 
* Wrote an algorithm to connect previously played chips to newly played chips to create new words.


## Todo
* Call the glosbe api from the backend so players can avoid having to use any external plugins to make the game work. 
* Create pop-up alerts that would appear to tell the user any positive or negative news about the game. (ie. Points per play, chips are not in a line, word isn't real, time is almost up)
* Set up highscores to rearrange with best score first
* Add username field to help distinguish highscores.
  
   [jquery]: <http://jquery.com>
   [css]: <https://www.w3.org/Style/CSS/Overview.en.html>
   [html]: <https://www.w3.org/html/>
   [js]: <https://www.javascript.com/>
   [2048]: <https://itunes.apple.com/us/app/2048/id840919914?mt=8>
   [userflow]: <https://s25.postimg.org/n5qhacs6n/Full_Wire_Frame.png>
   [gameplay]: <https://s25.postimg.org/4eok06xm7/Shmabble_GAMEPLAY.png>
   [intro]: <https://s25.postimg.org/kqylpxbxr/Shmabble_INTRO.png>
   [win]: <https://s25.postimg.org/jegwo1ei7/Shmabble_WIN.png>
   [lose]: <https://s25.postimg.org/862q090of/Shmabble_LOSE.png>
   [cors]: <https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi?hl=en>
