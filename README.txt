OPL Final Project. 
Gregory James Caldwell Jr. 

The Basics: 
The basis of the code is that it reads in decklist in .txt form, 
from the sub folder decks and builds a data base that gathers 
information via look ups on the json file provided. Finally 
the information is shown on screen inside of Dr. Racket to the user
in a neat bundle including the card image.  

My Part: 
I provided the portion of main.rkt that does the displaying of the
statistics, I also provided the Json files and images that are being displayed.
I also made 5 of the decklist, and gather the other 10 from the internet.
I created a few simple functions that changed the representation of the GUI. 
I have 6 functions that when given a number will convert it to the desired string
to be printed, and 1 function that colours the text depending on how often that card 
shows up in the database. Lastly I did large part in developing a way to print out 
the decklist inside of the Dr. Racket. 

Class Concepts Used: 
The major points that were used in the project learned from class are the 
use of list, displaying the images is in the form of list, know all of the 
syntax to work on Racket List was the most useful part of this project for me. 
But I did very minimal work on the hash tables that utilise things learned
from PS7, P7 helped a lot in learning to drive the section of 
the code my partner provided. I used a lot of 'ask to get information via the gets.
from the work I did on printing out the decklist the major class concept was  

Problems: 
Not all the images are the same size so the GUI isn't exactly pretty. 
The analysis on the number gives huge fractions so the 5th display 
line doesn't show well. 
Display image has limited ability, maybe should has use the Racket GUI, 
to let people sift through cards with clicks rather than typing. 

How to Drive the Code:
The code has 5 predefined card inside of it so you can easily look at some cards
but if you wanted to look up a card you knew was in Standard. 
( This links shows all the cards legal in MTG Standard 
http://gatherer.wizards.com/Pages/Search/Default.aspx?format=%5B%22Standard%22%5D )
the code could be easily driven to search for that card use the function (view "card name")