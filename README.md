# Number compositions -game
This is a simple javascript game that works as an example in [ViLLE Edugame Hackathon 2016](http://villeteam.fi/en/hackathon) and is the basis for theming competition. 

To get started, clone this project and change the remote to use your own git account. 
```
git clone https://github.com/changty/number-composition.git
cd number-composition
git remote set-url origin https://github.com/USERNAME/OTHERREPOSITORY.git
```

Verify changes: 
```
git remote -v
```

Open the index.html in browser and start playing/hacking!

## Game logic
The player tries to get the target value shown on the play area using numbers given in options. There operation to combine numbers can be addition, subtraction, division or multiplication. That is defined separately in each problem in the dataset.

If the player gets a correct answer, the answer is saved via "sendAnswer"-function and the player is presented with next problem or game over screen, if the player is out of questoins. 

In addition and multiplication, the player gets a wrong answer, if the combined value is bigger than the target value. In division and subtraction the player gets wrong answer, if the answer is smaller than the target value.


## Good resources for learning CSS
* [CSS3 Cheat sheet](http://www.lesliefranke.com/files/reference/csscheatsheet.html) Basic CSS commands
* [W3Schools](http://www.w3schools.com/css/) Lots of examples  

## Graphics
* [Awesome game art tutorials](http://www.2dgameartguru.com/) for GIMP and Inkscape
* [Keynney graphics](http://www.kenney.nl/) (Public domain assets, high quality)  
* [OpenGameArt.org](http://opengameart.org/) 
* [Pixabay](https://pixabay.com/)

**Remeber to only use assets that are public domain, CC0 or similarly licenced**

## Recommended software
* [SublimeText3](https://www.sublimetext.com/3) Epic code editor
* [Inkscape](https://inkscape.org/en/) Open source vector graphics editor
* [GIMP](https://www.gimp.org/) Free image editor

## Sounds
* [Freesound.org](https://www.freesound.org/) 

## The Structure 
Drawn with [Draw.io](http://draw.io) 

See more on styling by reading the comments in **base_theme.css**

[Editing styles in realtime using Chrome's developer tools.](https://developer.chrome.com/devtools)



![CSS-Elements](https://cdn.rawgit.com/changty/number-composition/master/CSS-NC.svg)
![CSS-Elements](CSS-NC.svg)



## The Flow 
Drawn with [Draw.io](http://draw.io) 

![Flow chart](https://cdn.rawgit.com/changty/number-composition/master/number-compositions.svg)

