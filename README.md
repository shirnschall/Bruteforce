# Bruteforce

A very fast and easy to use bruteforce-algorithm written in C

## Speed

| Number of guesses |   Time  |
|:-----------------:|:-------:|
|     10,000,000    |  0.014s |
|    100,000,000    |  0.138s |
|   1,000,000,000   |  1.383s |
|   10,000,000,000  |  11.152s|

## Usage

Simply include the bruteforce.h header file in your C or C++ project and you can use the getGuess() function!        

### getGuess()

Once called the getGuess function will continue to guess new strings/words until you manually interrupt it.    
If you want to you can easily change the algorithm to stop after a certain length of word. How to do this is documented in the bruteforce.cpp file.     
If you want the algorithm to start with a certain word/length, you would have to change the initialisation of the guess[] array.
