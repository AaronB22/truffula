# Truffula Notes
As part of Wave 0, please fill out notes for each of the below files. They are in the order I recommend you go through them. A few bullet points for each file is enough. You don't need to have a perfect understanding of everything, but you should work to gain an idea of how the project is structured and what you'll need to implement. Note that there are programming techniques used here that we have not covered in class! You will need to do some light research around things like enums and and `java.io.File`.

PLEASE MAKE FREQUENT COMMITS AS YOU FILL OUT THIS FILE.

## App.java
-Overall control file
-uses TruffulaOptions to set config settings

## ConsoleColor.java
-converts the ANSI color code into useable varibles for simple use

## ColorPrinter.java / ColorPrinterTest.java
-Converts the text given to it to be colored
-Determines what color should be used for printing
-Prints out the colored text
-TEST FILE: checks if the text is printed in the current color

## TruffulaOptions.java / TruffulaOptionsTest.java
-Congig files that determine if hidden files are shown or not
-Also determines if color should be used
-TEST Files test if configs are used correctly
## TruffulaPrinter.java / TruffulaPrinterTest.java
-the main print. Main controller for the prints
-tested the overall prints
## AlphabeticalFileSorter.java
-sorts the tree alphabetical order