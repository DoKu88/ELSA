# ELSA: Electronic Linguistic Software Assistant

## The purpose of this project is to have a home assistant that when given voice
## commands responds by either executing the commands and/or giving audio 
## feedback. These commands include things such as changing the lights, texting
## people, playing music, etc. 

## The way that this going to be organized is modularly in C++. We are going to
## divide the program into several componets, with the core being converting the
## text input into actual commands that will be executed. As inputs we will use
## a Google API to transfer speech to text or possibly direct text. Then we will
## pass that text to the core text to command module. The core text to command 
## module will then use that data to effectively do something. 

## Then general idea is to use C++ data encapsulation via C++ classes to 
## modularize development. 

## Example of Data Pipeline:
speech data -> Google API (speech to text) -> text data -> 
Text to Command Module -> Bluetooth -> speaker


