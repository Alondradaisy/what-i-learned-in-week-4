# What I Learned in Week 4 at Code Immersives
## A week in review by Daisy Warren

## WEEK 4 FOCUSED ON GETTING FAMILIARIZED WITH FUNCTIONS

**FUNCTIONS**

__1. FUNCTION FUNCTIONALITY__

_Functions are like recipes, that instruct users on what to do (but in this case, the computer).There is a certain way to call a function, for example:

function greetUser() {

};

**function** = the reserve word / keyword for writing a function. 

**greetUser** = the name of the function in camelCase.

**()** = the parentheses house _parameters_ and _arguments_ that pass into the function || sometimes these two can be mixed up, but they're not the same.

    - _parameters_ = the named variable methods that can be passed through a function. || 
    -> function greetUser(parameter) {};
    - _arguments_ = the values that can be passed through a function. ||
    -> function greetUser(argument) {}; 

**{}** = the curly braces define the block of code || otherwise thought of as the set of instructions.

**;** = the closing of a function || though the semi-colon isn't necessary to be able to run the code, better safe than sorry.


__2. QUOKKA VS CODE EXTENSION__

_Quokka_ is a VS CODE extension that allows us to toggle it on or off to see what part(s) of our code in running. Here's the brief breakdown of the three colored squares:

- Green = code running
- Red = not running
- White = did not call our function

__3. DECLARING A FUNCTION VS CALLING A FUNCTION__

Though the two terms may sound the same, their differences can be seen & remembered in the way they're documented. For example, 

- Declaring a function: function hangUp()
- Calling a function: hangUp()

Here we see how declaring uses the keyword 'function' while calling the function uses the name of the actual function. When we console.log() a function, we call a function, not declare it.

__4. STRINGS__

_Strings_ and tell the function what to do and all have properties. A property is a variable that is stored as part of another characteristic or attribute of that variable.  The properties always start with a (.)
  
  -> length is always how many characters something is starting at zero (0)... 0,1,2,3,... || spaces are always counted as characters

  - 'hello guys' vs 'helloguys'
  - ' ' vs '' 

  -> for example: firstName.length || .length is the main one for strings || 

  -> index = a # in line, in zero based counting || to find the length of something, we have the find the index of it using square brackets []

  * const cc = 8473627493284759
    const last4 = cc[12] + cc[13] + cc[14] + cc[15];
    last4; 4759

__5. METHODS__

_Methods_ are a special kind of property that is a function and does not take any parameters. Properties always start with a (.) For example:

-> .toUpperCase(); or .toLowerCase();

-> .teach();

-> .yell();

const yelledName = firstName.toUpperCase();

yelledNamed; COLIN JAFFE

const quietName = firstName.toLowerCase();

quietName; colin jaffe

firstName; colin jaffe


**-> We can think of strings as a street of houses, the index as the address on that street, & the character as the house itself.**

**STAY TUNED FOR WEEK IN REVIEW 5!** 

