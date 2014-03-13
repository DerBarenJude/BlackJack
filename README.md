BlackJack
=========

AP Computer Science BlackJack Program

##Introduction

BlackJack is a simple Java program for an AP Computer Science class.The program is a playable game of BlackJack in which there is a dealer, player, and deck. The basic Heirarchy of the program follows BlackJack Play. 

Game Rules > Dealer > Player > Shoe > Deck > Hand > Card

Implementation of a GUI is a goal once the basic console game is finished.


##Card:

The Card class is the basis of the entire program. When a card is created two integers and passes into the constructor which determine the Rank and Suit of the card (ex. Jack of Spades). Based on the Rank, a numerical vlaue "value" is assigned to the card which will be used later to calculate Hand totals.

The Card class has methods to retrive important variables as well as a setAce() method which changes the value of an Ace from 11 to 1 (from the rules of BlackJack). Card, along with almost every other class, Card contains a toString() method which overrides the default one and organizes the information.

##Deck:

A deck is a collection of 52 card in which there are 13 different ranks and 4 suits per rank. The deck is created by iteration over the number of Ranks and Suits to get 52. The constructor uses a private ArrayList of Cards and fills it with the its iteration over the total number of cards.

In retrospect, Deck is useless in comparison to Shoe as Shoe has to be an ArrayList of Cards as well, therefore a massive deck. Shoe does a better function job being an ArrayList of Cards rather than Decks because it is easier to access the shoe's cards that way.

##Shoe: 

WIP

###Update 3/12/14:

Project due 3/15/14 and will only include a console version. After the project is turned in the program will continue to be developed with a GUI and bug fixes as priorities. Ideally interfaces and other changes can be implemented once the core game mechanics are finished.


