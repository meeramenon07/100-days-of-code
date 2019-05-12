# 100 Days Of Code - Log
Day 1: April 01, 2019 
**Today's Progress**: Started the module on regular expressions
**Thoughts:** A bit tough to understand at first but got to crack it after reading it again for few times and managed to hit the green light in the run test submit .
**Link to work:** 
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/using-the-test-method

Day 2 April 02, 2019
** Today's Progress** Continuing with the module on regular expressions
Rgex getting easier to understand now :-)

**Link to work : **
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-literal-strings

https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-a-literal-string-with-different-possibilities

https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/ignore-case-while-matching

https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/extract-matches


Day 3 April 03, 2019
**Today's Progress** Continuing with the module on regular expressions lessons
Regular Expressions: 
-find more than the first match
-Match anything with wildcard period
-Match single character with multiple possibilities challenge : got stuck here/ I had done a small mistake by placing the flag before the slash but now it is rectified thanks to the suggestion of one the code campers.
-Match letters of the alphabet
-Match letters of the alphabet and numbers 
-Match single characters not specified
-Match characters that occur one or more times


**Links to work**
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/find-more-than-the-first-match
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-anything-with-wildcard-period
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-single-character-with-multiple-possibilities
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-single-character-with-multiple-possibilities
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-numbers-and-letters-of-the-alphabet
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-letters-of-the-alphabet
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-single-characters-not-specified
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-characters-that-occur-one-or-more-times

Day 4 April 04, 2019
** Today's Progress** Trying to finish the Regular Expressions lessons
-Match characters that occur zero or more times
-Find one or more criminals in a hunt
I just realised that the links to work when clicked does not generate the solution that I worked for my test so I wonder what to do?I am trying to paste the work here with solution:
// example crowd gathering
let crowd = 'P1P2P3P4P5P6CCCP7P8P9';

let reCriminals = /C+/; // Changed

let matchedCriminals = crowd.match(reCriminals);
console.log(matchedCriminals);

-Find characters with lazy matching
-
**Links to work**
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-characters-that-occur-zero-or-more-times
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/find-characters-with-lazy-matching

Day 5 April 05, 2019
-Regular Expressions: Match beginning String Patterns
-Regular Expressions : Match ending string patterns
-Regular Expressions : Match all letters and numbers
-Regular Expressions : Match everything but letters and numbers
-Regular Expressions : Match all numbers
-Regular Expressions : Match all non-numbers
**Links to work **
[Regex Match beginning string patterns](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-beginning-string-patterns)
[Regex Match ending string patterns](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-ending-string-patterns)
[Regex Match all letters and numbers](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-all-letters-and-numbers)
[Regex Match everything but letters and numbers](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-everything-but-letters-and-numbers)
[Regular Expressions match all numbers](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-all-numbers)
[Regular Expressions match all non-numbers](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions/match-all-non-numbers)

Day 6 : April 06, 2019
**Today's progress : Continuing with the Regex chapters
-Restrict Possible Usernames : Challenge :
Very challenging and interest challenge this one
You need to check all the usernames in a database. Here are some simple rules that users have to follow when creating their username.

1) The only numbers in the username have to be at the end. There can be zero or more of them at the end.

2) Username letters can be lowercase and uppercase.

3) Usernames have to be at least two characters long. A two-letter username can only use alphabet letter characters.

let username = "JackOfAllTrades";
let userCheck = /^[a-z]{2,}\d*$/i;//after changing the line here
let result = userCheck.test(username);

-Regex : Match white space
The shorthand used for matching white space is \s
This shorthand can also match characters \r\t\f\n\v
(return,tab, form feed, and new line characters)
Time for challenge :
Change the regex countWhiteSpace to look for multiple whitespace characters in a string.
let sample = "Whitespace is important in separating words";
let countWhiteSpace = /\s/g;//changed the line
let result = sample.match(countWhiteSpace);

-Regex : Match non white space
The shorthand for this is \S

Day 7 : April 07, 2019
**Today's progress : Continuing with regex chapters
-Specify upper and lower number of matches
**Work test**
let let ohStr = "Ohhh no";
let ohRegex = /oh{3,6}\sno/i; // Changed
let result = ohRegex.test(ohStr);
The challenge was : Change the regex ohRegex to match only 3 to 6 letter h's in the word "Oh no" 
\s will match the white space and flag i will match the cases

-Specify only the lower number of matches
The challenge is to Change the regex haRegex to match the word "Hazzah" only when it has four or more letter z's.
in the following
let haStr = "Hazzzzah";
let haRegex = / // Change this line
let result = haRegex.test(haStr);

My work solution 
let haStr = "Hazzzzah";
let haRegex = /haz{4,}ah/i // 
let result = haRegex.test(haStr);

flag i is for the cases


Day 8 : April 08 2019
** Today's Progress: About to finish the chapter on Regex

-Regex: Specify exact number of matches
Time for some Work challenge: Change the regex timRegex to match the word "Timber" only when it has four letter m's.
in the following :
let timStr = "Timmmmber";
let timRegex = /       /; // Change this line
let result = timRegex.test(timStr);

Solution after changing the above line:
let timStr = "Timmmmber";
let timRegex = /tim{4}ber/i; //changed line
let result = timRegex.test(timStr);

-Regex: Check for all or none
Time for challenge work;
let favWord = "favorite";
let favRegex = /     /; // Change this line
let result = favRegex.test(favWord);

Here is my solution-

let favWord = "favorite";
let favRegex - /favou?rite/; // changed
let result = favRegex.test(favWord);

-Regex- Positive and Negative Lookahead
Positive Lookahead uses the sign (?=...) and negative lookahead uses sign (?!...)
I want to write this example provided in the chapter to remember the rules and codes
Example is that of a simple password checker that looks for between 3 and 6 characters and atleast one number:
let password = "abc123";
let checkPass = /(?=\w{3,6})(?=\D*\d)/;
checkPass.test(password);// returns true

Time for some work challenge in the chapter
Use lookaheads in the pwRegex to match passwords that are greater than 5 characters long and have two consecutive digits.

let sampleWord = "astronaut";
let pwRegex = /(?= \W {5,}) (?= \D*\d{2})/;
let result = pwRegex.test(sampleWord);
The first lookahead looks for characters greater than 5 where the shorthand \w will look for characters that will match all letters and numbers. The second lookahead will look for digits and non number characters. The number 2 in the string depects characters with two digits.The shorthand \D is for non numbers, \d for digits and * is for zero or more characters.



Day 9 April 09 2019

*** Today's Progress: Concluding the Regex chapter
Regex: Reuse Patterns using Capture Groups
Using parenthesis() to find repeat sub strings and backslash \ followed by a number to state where that repeat group will appear.
example
let repeatStr = "regex regex";
let repeatRegex = /(\w+)\s\1/;
repeatRegex.test(repeatStr); // Returns true
repeatStr.match(repeatRegex); // Returns ["regex regex", "regex"]

Time for a tough challenge( this was tough for me to figure out but thanks to a fellow code camper's reply from last year, I was able to figure it out so clearly) Here is the problem with the clear solution with explanation:

Use capture groups in reRegex to match numbers that are repeated only three times in a string, each separated by a space.

let repeatNum = "42 42 42";
let reRegex = /        /  //;change this line
let result = reRegex.test(repeatNum);

solution :
let repeatNum = "42 42 42";
let reRegex = /^(d+)\s\1\s\1$ /;
Explanation :
^ start
(\d+) the first number
\s a space
\1 the next number
\s a space
\1 the final number
$ the end of the string
So we match the original number with (\d+), and then we match it a further two times using \1. In total, that makes us look for three matches of that number, with spaces \s between each of them. 


-Regex- Use capture groups to search and replace
using replace() 
.replace(search parameter, "string to be replaced ")
let wrongText = "The sky is silver.";
let silverRegex = /silver/;
wrongText.replace(silverRegex, "blue");
// Returns "The sky is blue."
You can also access capture groups in the replacement string with dollar signs ($).

"Code Camp".replace(/(\w+)\s(\w+)/, '$2 $1');
// Returns "Camp Code"
let huhText = "This sandwich is good.";
let fixRegex = /good/; // Change this line
let replaceText = "okey-dokey"; // Change this line
let result = huhText.replace(fixRegex, replaceText);


Day 10, April 10, 2019
Regex- Remove white space at the beginning and end
I am stuck here and cannot fully pass the challenge,so, going to refer to my notes again before going to come back to this chapter again tomorrow.


Day 11, April 11, 2019
*** Today's Progress : Managed to pass my last chapter on Regex finally

Regex: Remove space from beginning and end of a string

let hello = "   Hello, World!  ";
let wsRegex = /    /; // Change this line
let result = hello; // Change this line

let hello = "   Hello, World!  ";
let wsRegex = /^\s*|\s*$/g; // Changed
let result = hello.replace(wsRegex, ""); // Changed

Very challenging indeed this one.
^\s  white space in the beginning
* some  non digit characters
| or operand
\s*$ white space and non digit character at the end
g is the global flag
so the result will be "Hello, World!" due the changed codes above as shown, with only one space remaining in between the two words and removing the occurences of white spaces in the beginning and end of the string.


Day 12. April 12, 2019
*** Today's progress : Instead of going forward with the next chapter set, I decided to do revision of the past few weeks' chapters on basic java scrript, es6 and regex so that i can remember the codes better
Today- I finished revision of basic java scr
ipt from my hand written notes

Day 13, April 13, 2019
*** Today's progress : I did my second day of revising ES and Regex

Day 14, April 14, 2019
***  Today's progress: 
I was reading up on css animation and implemented that on a website that i was practising on. I was trying to rotate my main image but ended up geting image shaking effect despite of my css code for rotate. Trying to figure out what went wrong. Will be working on it unless I figure it out myself or from some help.
Link to work : https://codepen.io/meeramenon07/full/qwaWeP


Day 15, April 15, 2019
***  Today's progress:
Watched the video on Java script for beginners by teacher Beau - a free video from freeCodeCamp so that I can take a step back to remember the chapter on js I will watch it for two days to understand my codes even better and it is a fantastic video on java script.
Link to video :https://www.freecodecamp.org/news/learn-javascript-full-course/


Day 16, April 16, 2019
*** Today's progress: Continued watching the java script video by teacher Beau. Its the most amazing tutorial video that I have watched and learned from. Today, I learnt and revised about calling functions, function arguments, returning functions both valid and invalild, Boolean values, Conditional logic with If statements, Global versus Local scope in functions, storing array, Logical and operator, Equality and Inequality operator, etc.



Day 17, April 17, 2019
*** Today's progress : Continued watching the java script video by teacher Beau for revision. Today, I covered the following topics :
Returning Boolean values from functions
Returning early patterns from functions
Function And operator
Function OR operator
Else statements
Else If Statements
Logical order in Else If Statements
If Else chain 
Switch statements
Default options in switch statments
Gold code
Multiple identital options in switch statements
Replacing If Else chains with Switch
Replacing If Else chains with Switch statements



Day 18, April 18, 2019
*** Today's progress: Continued watching the Javascript video by teacher Beau for my revision. I covered the following topics  today:
Accessing Object Properties with dot notation
Acessing Object properties with bracket notation
Accessing Object properties with variables
Updating Object properties
Add New properties to an Object
Delete properties from an Object
Using Objects for Lookups
Testing Objects for properties
Manipulating complex Objects
Accessing Nested Objects




Day 19, April 19, 2019

*** Today's progress : Revision of Javascript
Accessing nested arrays
Accessing nested objects




Day 20, April 20, 2019
Today's progress : Revising my Javascript chapters through the video by teacher Beau
Covered lessons were :
Count backwards with a For Loop
Iterate through an Array with a For loop
Iterate through an array with a While loop
Nesting For loops
The above lessons were really heavy so I had to play the video many times to actually understand and solve the challenges myself but was very rewarding considering the fact that now I really understand it after watching this video, so, many thanks to teacher Beau as I understood more after these video lessons more in my second round of video revisions.





Day 21, April 21, 2019
Today's progress : Finished watching the video on Javascript by Beau, Part 1.
Covered the following lessons today:
Iterate with Do While Looops
Profile Lookup
Generate Random Fractions
Generate Random Whole Numbers
Generate Random Whole Numbers within a Range
Use the parseInt Function
Use the parseInt Function with a Radix
Use the conditional Ternary Operator
Use Multiple Conditional Ternary Operators






Day 22, April 22, 2019
Today's progress : Started the video on Javascript by Beau, Part 2 on ES6
Covered the following topics on ES6
Explore the differences between var and let keyword
Scope of var and let keywords
Declare a Read-only variable with Const keyword
Mutate an array declared with const
Prevent object mutation declared with const





Day 23, April 23, 2019
Today's progress : Continue watching the video on JS by Beau, Part 2: ES6
Covered the following topics on ES6:
⌨️ (2:47:17) 114. Use Arrow Functions to Write Concise Anonymous Functions
⌨️ (2:28:24) 115. Write Arrow Functions with Parameters
⌨️ (2:49:27) 116. Write Higher Order Arrow Functions
⌨️ (2:53:04) 117. Set Default Parameters for Your Functions
⌨️ (2:54:00) 118. Use the Rest Operator with Function Parameters





Day 24, April 24, 2019
Today's progress : Continue watching the video on javascript by Beau, Part 2 : ES6
Covered the following topics on ES6:
⌨️ (2:55:31) 119. Use the Spread Operator to Evaluate Arrays In-Place
⌨️ (2:57:18) 120. Use Destructuring Assignment to Assign Variables from Objects
⌨️ (3:00:18) 121. Use Destructuring Assignment to Assign Variables from Nested Objects
⌨️ (3:01:55) 122. Use Destructuring Assignment to Assign Variables from Arrays
⌨️ (3:03:40) 123. Use Destructuring Assignment with the Rest Operator to Reassign Array





Day 25, April 25, 2019
Today's progress: watching the javascript video part 2 on ES6 covering the following topics today:
⌨️ (3:05:05) 124. Use Destructuring Assignment to Pass an Object as a Function's
⌨️ (3:06:39) 125. Create Strings using Template Literals



****************************************************************
Day 26, April 26, 2019
Today's progress : Continued watching the video on javascript by Beau, Part 2 : ES6
Covered the following topics:
126. Write Concise Object Literal Declarations Using Simple Fields
⌨️ (3:12:24) 127. Write Concise Declarative Functions with ES6
⌨️ (3:12:56) 128. Use class Syntax to Define a Constructor Function
⌨️ (3:15:11) 129. Use getters and setters to Control Access to an Object




************************************************************************
Day 27, April 27, 2019
Today's progress: Finished watching the video on Javascript for beginners part 1 and part 2
Covered the following topics today while concluding the video:
⌨️ (3:20:25) 130. Understand the Differences Between import and require
⌨️ (3:22:33) 131. Use export to Reuse a Code Block
⌨️ (3:23:40) 132. Use * to Import Everything from a File
⌨️ (3:24:50) 133. Create an Export Fallback with export default
⌨️ (3:25:26) 134. Import a Default Export



Day 28, April 28, 2019
Today's progress: Introduction to debugging challenges in js
covered the following topics today:
Use the JavaScript Console to Check the Value of a Variable
Pass
Understanding the Differences between the freeCodeCamp and Browser Console
Use typeof to Check the Type of a Variable
Catch Misspelled Variable and Function Names
Catch Unclosed Parentheses, Brackets, Braces and Quotes
Catch Mixed Usage of Single and Double Quotes
Catch Use of Assignment Operator Instead of Equality Operator
Catch Missing Open and Closing Parenthesis After a Function Call
Catch Arguments Passed in the Wrong Order When Calling a Function
Catch Off By One Errors When Using Indexing



Day 29, April 29, 2019
Today's progress: Completed the debugging lessons and started the Basic Data Structure lessons
Covered the following topics today:
Use Caution When Reinitializing Variables Inside a Loop
Prevent Infinite Loops with a Valid Terminal Condition
Introduction to the Basic Data Structure Challenges
Use an Array to Store a Collection of Data
Access an Array's Contents Using Bracket Notation
Add Items to an Array with push() and unshift()
Remove Items from an Array with pop() and shift()
Remove Items Using splice()



Day 30, April 30, 2019
Today's progress : Doing the lessons onData structure 
Covered the following topics today:
Add Items Using splice()
Copy Array Items Using slice()
Copy an Array with the Spread Operator




Day 31, May 1, 2019
Today's progress: Doing the lessons on data structure
Covered the following topics today:
Combine Arrays with the Spread Operator
Check For The Presence of an Element With indexOf()




Day 32, May 2, 2019
Today;s progress: Doing lessons on data structure
Covered following topics today-
Iterate Through All an Array's Items Using For Loops
I got stuck at the next topic which I am planning to research well before proceeding with it, dont find this topic clearly explained anywhere ! it is 'create complex multi dimensional arrays'



Day 33, May 03, 2019
Today;s progress: Doing the lessons on data structure
Covered following topics today:
Create complex multi-dimensional arrays
Add Key-Value Pairs to JavaScript Objects
Modify an Object Nested Within an Object
Access Property Names with Bracket Notation



Day 34, May 04, 2019
Today's progress : Doing the lessons on data structure
Covered following topics today:
Use the delete Keyword to Remove Object Properties
Check if an Object has a Prdataoperty



Day 35, May 05, 2019
Today's progress- lessons on data structure
Topics covered:
 Iterate Through the Keys of an Object with a for...in Statement



Day 36, May 06, 2019
Today's progress: lessons concluded on data structure
Topics covered today:
Generate an Array of All Object Keys with Object.keys()
Modify an Array Stored in an Object



Day 37, May 07, 2019
Today's progress: lessons started on Basic Algorithm scripting
Topics covered today :
Convert Celsius to Fahrenheit
Reverse a string
Factorialize a Number
The factorialize challenge is very challenging so noting down my solution here for my record:
function factorialize(num) {
  let factorializeNum = 1;
  for (let i = 1; i < num; i--){
   factorializeNum = (num * factorialize(num - 1)); 
  }
  return factorializeNum;
}

factorialize(5);



Day 38, May 08, 2019
Today's progress : Basic Algorithm scripting lesson
Topic covered today:
Find the longest word in a strong
My solution using the split() method  and for loop iteration:
function findLongestWord(str){
 strSplit = str.split(' ');
 var longestWord = 0;
 for (var i = 0; i < strSplit.length; i++) {
  if strSplit[i].length > longestWord{
     longestWord = strSplit[i].length;
  }
 }
 return longestWord;
}
findLongestWord ("The quick brown fox jumped over the lazy dog");
 
Day 39, May 09. 2015
I skipped

Day 40, May 10, 2019
Today's progress: completed the challenge for finding the largest number in an array 
My solution :
`````````````````````````````````````````````````````````````````
function largestOfFour(arr) {
  // You can do this!
  var result = [];
  for (var i = 0; i < arr.length; i++){
    var largestNumber  = arr[i][0];
      for (var j = 1; j < arr[i].length; j++){
        if (arr[i][j] > largestNumber){
          largestNumber = arr[i][j];
      }
    }
    result.push(largestNumber);
  }


  return result;
}
````````````````````````````````````````````````````````````````
Day 41, May 12 & Day 42 (May 11, 2019 - May 12, 2019)
Today's progress (May 12, 2019):
Finished the challenge for finding the ending 
Basic algorithm scripting : find the ending 

