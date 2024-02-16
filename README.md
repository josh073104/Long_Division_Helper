This project was colaborative. My contributions include:

division.js
  
    -Added functionality to the "yesButton", "noButton", and "endedPlayAgain" elements
    -Within the functionality for when the "noButton" is clicked, added 
        the mechanisms to set up and switch to the recap page ("gameEndPage")
    -Added functionality to restart the game upon completion
    -Made changes to the announceIncorrect() and announceCorrect() functions to clear messages that were displayed using 
        setTimeout functions to resolve a bug that kept happening upon completion of the game
    -Made changes to the announceSuccess() function to add funcitonality for restarting the game or switching to a problem
        recap page upon completion of the game using yes and no buttons
    -Made major changes to the displayQuotientDigit() function to add color coordination of each digit based on its 
        numerical place
    -Made major changes to the alignAnswer() function in order to maintain alignment of the displayed digits in their 
        respecitve columns with newly implemented color coordination
    -Made major changes to the addSigns() function to allow it to work with the color coordination
    -Made changes to the displaySubtractionResult() and displayMultiplicationResult() functions so that they keep the 
        displayed digits properly aligned in their columns
    -Made changes to the displayBringDownDigit() function to make sure the digit being brought down was aligned correctly
        on screen and color coordinated. Also implemented an arrow image that displays that indicates the 'drop down' itself for
        accessibility
    -General bug fixing and testing of all changes and new features implemented
    -All documentation of newly added features and some documentation of already existing features
  

index.html

    -Added the "gameEndPage" section, and all of its contents
    -Added the "yesButton" and "noButton" to the "gamePage" (the "nobutton" is actually the button to display the recap)

styles.css

    -Added styles for the "yesButton", "noButton", and "endedPlayAgain" elements
