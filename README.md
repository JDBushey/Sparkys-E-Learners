# Sparkys-E-Learners
Repository for all code and website assests

How to see what this would look like as a website:
1. Download all of the files and folders
2. Open index.html in chrome or whatever internet browser you use

How I made this:
I designed this using webflow and then built it and scraped the html because the site would not let me add in the games or modify the html directly. A lot of the text and images for the website are just place holders and should be replaced. 

What I have in mind for making the games:
I have the html set up to make use of the p5.js library to assist in building the games. If you don't know what that is feel free to check out the website: https://p5js.org/. The website also has a built in code editor for creating new programs. I set up an example on the preset-words page of a drawing game that runs the code in the sketch.js file located in the game.code folder. This means that is should be relatively easy to take any game from the p5.js editor and add it into the website. Personally I have found that both javascript as a languge and p5.js as a library are easy to work with and very well documented. The fact that the games can be created with a web based editor will also make them easier to share. My thought is that those who know how to code can work on the games using the editor while those who don't can fill in the text and images on the website and help with designing and play testing the games. Of course we may have to change the html or create a database for the website and everyone is welcome to help in anyway they can. 

The folders and what they do (some of this is just my best guess so apologies if I'm off):
The ajax.googleapis.com folder and d3e54v103j8qbb.cloudfront.net folder contain contain javascript code used throughout the html primarily for formating

The assests folder contains the css file, more formating javascript and images used through out the html. Currently many of the images used are refernced from another website; however, those are just placeholders and the actual images sould be placed into the assests folder. 

The html.files folder contains the html files that serve as the bulk of the website. index.html is the home page by convention. The pages that will contain the games themselves are seperated into a subfolder called games. Currently the custom-words page uses generic images as placeholders for the games while the preset-words page has an example game to show the implimination process for adding a game into the page. Each of these games could potentially be seperated into its own page, but for the time being I was envisioning multiple games on the same page. If we go the multiple games per page route we should make sure that the games all has a sort of click button to start playing screen before the game begins. 

The game.code folder is intended to store the javascript code for each of the games. I should also be used for any classes needed for any of those games. Currently there is a file called sketch.js in there. That file serves as a test of the implimintation of a game into an html page and would be a bad way of nameing the code for each of the games. It might be a good idea to create a subfolder for each of the games.


