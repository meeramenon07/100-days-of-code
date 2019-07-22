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


Day 42, May 13, 2019
Today's progress : challenge for finding repeat the string 
My solution:
function repeatStringNumTimes(str, num) {
  // repeat after me
  
  for(var i = 0; i < str.length; i++){
    if(num <= 0){
      return "";
    } else if (num === 1) {
      return str;
    } else if (num > 1){
      return str + repeatStringNumTimes(str, num-1);
    }
  }
   
}

repeatStringNumTimes("abc", 3);
Link to solution work: https://repl.it/@meeramenon07/SardonicLateLines





Day 43, May 14, 2019
Todays progress: challenge for truncating a string 
The challenge with conditions:
Basic Algorithm Scripting: Truncate a String
Truncate a string (first argument) if it is longer than the given maximum string length (second argument). Return the truncated string with a ... ending.

Remember to use Read-Search-Ask if you get stuck. Write your own code.


truncateString("A-tisket a-tasket A green and yellow basket", 8) should return "A-tisket...".
Passed
truncateString("Peter Piper picked a peck of pickled peppers", 11) should return "Peter Piper...".
Passed
truncateString("A-tisket a-tasket A green and yellow basket", "A-tisket a-tasket A green and yellow basket".length) should return "A-tisket a-tasket A green and yellow basket".
Passed
truncateString("A-tisket a-tasket A green and yellow basket", "A-tisket a-tasket A green and yellow basket".length + 2) should return "A-tisket a-tasket A green and yellow basket".
Passed
truncateString("A-", 1) should return "A...".
Passed
truncateString("Absolutely Longer", 2) should return "Ab...".

My solution:

function truncateString(str, num) {
  // Clear out that junk in your trunk

   if (num < str.length){
     return str.slice(0, (num-str.length)) + '...';
   }
   if ( num <=1 ){
    return str.slice(0, num) + '...';
  }if (str.length > num && num > 1){
    return str.slice(0, (num-1)) + '...';
  }if (num >= str.length){
    return str;
  }

  
}

truncateString("A-tisket a-tasket A green and yellow basket", 8);

My link to repl.it :
https://repl.it/@meeramenon07/truncate-string



Day 44 May 15, 2019
Todays progress - passed a challenge and practising more 
Finders Keepers challenge
solution link 
https://repl.it/@meeramenon07/IgnorantMundaneOpenlook


Day 45, May 16, 2019
Today's progress- two challenges passed
Topics covered- Title case a sentence and Splice and Slice arrays
Title case a sentence:
``````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````

function titleCase(str){
 return str.toLowerCase().split(' ').map(function(words){  
    return words.replace(words[0], words[0].toUpperCase());
 }).join(' ');

}
titleCase("I'm a little tea pot");


Slice and splice- copy elements from array one to array two

function frankenSplice(arr1, arr2, n){
  let newArray = arr2.slice();
  
  for (let i =0; i < arr1.length; i++){
     newArray.splice(n, o, arr1[i]);
     n++;
  }return newArray;
  
}
frankenSplice([1,2,3],[4.5.6], 1);
}


Day 46, May 17, 2019
Today's progress: challenges covered
Slice & Splice
Falsy Bouncer
Where do I belong



Day 47, May 19, 2019
Today's progress : Mutation challenge
Basic Algorithm Scripting: Mutations
Return true if the string in the first element of the array contains all of the letters of the string in the second element of the array.

For example, ["hello", "Hello"], should return true because all of the letters in the second string are present in the first, ignoring case.

The arguments ["hello", "hey"] should return false because the string "hello" does not contain a "y".

Lastly, ["Alien", "line"], should return true because all of the letters in "line" are present in "Alien".

Remember to use Read-Search-Ask if you get stuck. Write your own code.

solution-
```
function mutation(arr) {

    return arr[1].toLowerCase().split('').every(function(letter) {
      return arr[0].toLowerCase().indexOf(letter) != -1;
    });

  return arr;
}
```

Explanation - first change the second element of the array to lower case then split it to character array, then match every letter of this array to every letter of the first element of the array after changing the second element to lower case and then matching the letters to ensure that the index of letter is not -1

next challenge: chunky monkey challenge
Basic Algorithm Scripting: Chunky Monkey
Write a function that splits an array (first argument) into groups the length of size (second argument) and returns them as a two-dimensional array.

Remember to use Read-Search-Ask if you get stuck. Write your own code.

my solution
```
function chunkArrayInGroups(arr, size) {
  // Break it up.
  let result = [];
   while ( arr.length ) {
    result.push(arr.splice(0, size))
  }

   
  return result;
  
}

chunkArrayInGroups(["a", "b", "c", "d"], 2);

```



mutation(["hello", "hey"]);


Day 48, May 20, 2019
Today's progress: Lessons covered on OOP
- create a basic javascript object
-use dot notation to access the properties of an object
-create a method on an object
-make code more reusable with this key word
Using of keyword this.property to make code more reusable for example:
Object Oriented Programming: Make Code More Reusable with the this Keyword
The last challenge introduced a method to the duck object. It used duck.name dot notation to access the value for the name property within the return statement:

sayName: function() {return "The name of this duck is " + duck.name + ".";}

While this is a valid way to access the object's property, there is a pitfall here. If the variable name changes, any code referencing the original name would need to be updated as well. In a short object definition, it isn't a problem, but if an object has many references to its properties there is a greater chance for error.

A way to avoid these issues is with the this keyword:

let duck = {
  name: "Aflac",
  numLegs: 2,
  sayName: function() {return "The name of this duck is " + this.name + ".";}
};
this is a deep topic, and the above example is only one way to use it. In the current context, this refers to the object that the method is associated with: duck.

If the object's name is changed to mallard, it is not necessary to find all the references to duck in the code. It makes the code reusable and easier to read.

Modify the dog.sayLegs method to remove any references to dog. Use the duck example for guidance.

let dog = {
  name: "Spot",
  numLegs: 4,
  sayLegs: function() {return "This dog has " + this.numLegs + " legs.";}
};

dog.sayLegs();


Day 49, May 21, 2019
Todays progress- OOP covering following topics-
-Define a constructor function
-Use a constructor to create an object
-Extend constructors to receive arguments
-verify an object;s constructor with instanceof



Day 50, May 22, 2019
Today's progress - Object Oriented Programming -topics:
-Understanding own property
Challenge solution :

```
function Bird(name) {
  this.name = name;
  this.numLegs = 2;
}

let canary = new Bird("Tweety");
let ownProps = [];
// Add your code below this line
for (let property in canary){
  if (canary.hasOwnProperty(property)){
    ownProps.push(property);
  }
}
console.log(ownProps);
```
-Prototype properties to reduce duplication:
```
function Dog(name) {
  this.name = name;
}

Dog.prototype.numLegs = 4;

// Add your code above this line
let beagle = new Dog("Snoopy");
console.log(beagle.numLegs);

```

-Iterate over all properties of the object:

```
function Dog(name) {
  this.name = name;
}

Dog.prototype.numLegs = 4;

let beagle = new Dog("Snoopy");

let ownProps = [];
let prototypeProps = [];

// Add your code below this line 
for(let property in beagle){
  if(beagle.hasOwnProperty(property)){
    ownProps.push(property);
  } else{
    prototypeProps.push(property);
  }
}
console.log(ownProps);//prints name
console.log(prototypeProps);// prints numLegs

```
-Understand constructor property:
```
function Dog(name){
 this.name = name;
}

function joinDogFraternity(candidate){
  if(candidate.constructor === Dpg){
     return true;
  } else {
     return false;
  }
}

Day 51, May 23, 2019
Todays progress- OOP prototypes continued
```

- Set the constructor property when changing the prototype:
```
function Dog(name) {
  this.name = name; 
}

// Modify the code below this line
Dog.prototype = {
  constructor : Dog,
  numLegs: 2, 
  eat: function() {
    console.log("nom nom nom"); 
  }, 
  describe: function() {
    console.log("My name is " + this.name); 
  }
};
```
-Understand where a prototype comes from-
```
function Dog(name) {
  this.name = name;
}

let beagle = new Dog("Snoopy");

// Add your code below this line
Dog.prototype.isPrototypeOf(beagle);
```
Day 52, May 24, 2019
Today's progress: OOP- prototype
```
-Understanding prototype chains
function Dog(name) {
  this.name = name;
}

let beagle = new Dog("Snoopy");

Dog.prototype.isPrototypeOf(beagle);  // => true

// Fix the code below so that it evaluates to true
Object.prototype.isPrototypeOf(Dog.prototype);
```
-DRY- DO NOT REPEAT YOURSELF:
The eat method is repeated in both Cat and Bear. Edit the code in the spirit of DRY by moving the eat method to the Animal supertype.

```
function Cat(name) {
  this.name = name; 
}

Cat.prototype = {
  constructor: Cat, 
  
};

function Bear(name) {
  this.name = name; 
}

Bear.prototype = {
  constructor: Bear, 
  
};

function Animal() { }

Animal.prototype = {
  constructor: Animal,
  eat: function(){
    console.log("nom nom nom");
  }
};
```

day 53, May 25, 2019
Today'sprogress: prototype :
-inheriting prototype from a supertype:

```
function Animal() { }

Animal.prototype = {
  constructor: Animal, 
  eat: function() {
    console.log("nom nom nom");
  }
};

// Add your code below this line

let duck = Object.create(Animal.prototype); // Change this line
let beagle = Object.create(Animal.prototype); // Change this line

duck.eat(); // Should print "nom nom nom"
beagle.eat(); // Should print "nom nom nom" 
```

-Set the child's prototype to an instance of the parent:
```
Animal.prototype = {
  constructor: Animal,
  eat: function() {
    console.log("nom nom nom");
  }
};

function Dog() { }

// Add your code below this line
Dog.prototype = Object.create(Animal.prototype);

let beagle = new Dog();
beagle.eat();  // Should print "nom nom nom"
```
-Reset inherited constructor property:
```
function Animal() { }
function Bird() { }
function Dog() { }

Bird.prototype = Object.create(Animal.prototype);
Dog.prototype = Object.create(Animal.prototype);

// Add your code below this line


Dog.prototype.constructor = Dog;
Bird.prototype.constructor = Bird;
let duck = new Bird();
let beagle = new Dog();

```

- Add methods after inheritance:

```
function Animal() { }
Animal.prototype.eat = function() { console.log("nom nom nom"); };

function Dog() { }

// Add your code below this line
Dog.prototype = Object.create(Animal.prototype);
Dog.prototype.constructor = Dog;
Dog.prototype.bark = function(){
    console.log("woof");
};




// Add your code above this line

let beagle = new Dog();

beagle.eat(); // Should print "nom nom nom"
beagle.bark(); // Should print "Woof!"

-Override Inherited Methods
```
```
function Bird() { }

Bird.prototype.fly = function() { return "I am flying!"; };

function Penguin() { }
Penguin.prototype = Object.create(Bird.prototype);
Penguin.prototype.constructor = Penguin;

// Add your code below this line
Penguin.prototype.fly = function(){
    return "Alas, this is a flightless bird."
};
Bird.prototype.fly = function(){
    return "I am flying!"
};

// Add your code above this line

let penguin = new Penguin();
console.log(penguin.fly());
```
Examples to remember
ChildObject.prototype = Object.create(ParentObject.prototype);
Then the ChildObject received its own methods by chaining them onto its prototype:

ChildObject.prototype.methodName = function() {...};
It's possible to override an inherited method. It's done the same way - by adding a method to ChildObject.prototype using the same method name as the one to override.

Here's an example of Bird overriding the eat() method inherited from Animal:
```

function Animal() { }
Animal.prototype.eat = function() {
  return "nom nom nom";
};
function Bird() { }

// Inherit all methods from Animal
Bird.prototype = Object.create(Animal.prototype);

// Bird.eat() overrides Animal.eat()
Bird.prototype.eat = function() {
  return "peck peck peck";
};
```

Day 54, May 26, 2019

Today's progress: Use Mixin to relate common behaviour between unrelated objects:
```
let bird = {
  name: "Donald",
  numLegs: 2
};

let boat = {
  name: "Warrior",
  type: "race-boat"
};

// Add your code below this line
let glideMixin = function(obj){
   obj.glide = function() {
     console.log("Gliding, wah")
   }
}
glideMixin(bird);
glideMixin(boat);
```

- Object Oriented Programming: Use Closure to Protect Properties Within an Object from Being Modified Externally
```
function Bird() {
  let weight = 15;
    this.getWeight = function(){
      return weight;
    }
  
  
}
```
-IMMEDIATELY INVOKED FUNCTION EXPRESSION (IIFE)
```
(function () {
  console.log("A cozy nest is ready");
    
})();
```
Note that the function has no name and is not stored in a variable. The two parentheses () at the end of the function expression cause it to be immediately executed or invoked. This pattern is known as an immediately invoked function expression or IIFE.

Day 55, May 27, 2019
Today's progress : concluding the topic on Object Oriented Programming with the last chapter:
-Use an IIFE to create a module

```
let isCuteMixin = function(obj) {
  obj.isCute = function() {
    return true;
  };
};
let singMixin = function(obj) {
  obj.sing = function() {
    console.log("Singing to an awesome tune");
  };
};

let funModule = (function (){
  return {
    isCuteMixin: function(obj){
      obj.isCute = function() {
        return true;
      };
    },
    singMixin: function (obj){
      obj.sing = function(){
        console.log("Singing to an awesome tune");
      };
    }
  }
}) ();

```
Day 56, May 29, 2019
Today's 
progress: Functional programming
-calling the get function

```
 * A long process to prepare tea.
 * @return {string} A cup of tea.
 **/
const prepareTea = () => 'greenTea';

/**
 * Get given number of cups of tea.
 * @param {number} numOfCups Number of required cups of tea.
 * @return {Array<string>} Given amount of tea cups.
 **/
const getTea = (numOfCups) => {
  const teaCups = [];
  
  for(let cups = 1; cups <= numOfCups; cups += 1) {
    const teaCup = prepareTea();
    teaCups.push(teaCup);
  }

  return teaCups;
};

// Add your code below this line

const tea4TeamFCC = getTea(40) ; // :(

// Add your code above this line

console.log(tea4TeamFCC);
```

-Understanding functional programming terminology
```
/**
 * A long process to prepare green tea.
 * @return {string} A cup of green tea.
 **/
const prepareGreenTea = () => 'greenTea';

/**
 * A long process to prepare black tea.
 * @return {string} A cup of black tea.
 **/
const prepareBlackTea = () => 'blackTea';

/**
 * Get given number of cups of tea.
 * @param {function():string} prepareTea The type of tea preparing function.
 * @param {number} numOfCups Number of required cups of tea.
 * @return {Array<string>} Given amount of tea cups.
 **/
const getTea = (prepareTea, numOfCups) => {
  const teaCups = [];

  for(let cups = 1; cups <= numOfCups; cups += 1) {
    const teaCup = prepareTea();
    teaCups.push(teaCup);
  }

  return teaCups;
};

// Add your code below this line

const tea4GreenTeamFCC = getTea(prepareGreenTea, 27); // :(
const tea4BlackTeamFCC = getTea(prepareBlackTea, 13); // :(

// Add your code above this line

console.log(
  tea4GreenTeamFCC,
  tea4BlackTeamFCC
);
```
-Understanding the hazards of using imperative codes:
```
// tabs is an array of titles of each site open within the window
var Window = function(tabs) {
  this.tabs = tabs; // we keep a record of the array inside the object
};

// When you join two windows into one window
Window.prototype.join = function (otherWindow) {
  this.tabs = this.tabs.concat(otherWindow.tabs);
  return this;
};

// When you open a new tab at the end
Window.prototype.tabOpen = function (tab) {
  this.tabs.push('new tab'); // let's open a new tab for now
  return this;
};

// When you close a tab
Window.prototype.tabClose = function (index) {
  var tabsBeforeIndex = this.tabs.splice(0, index); // get the tabs before the tab
  var tabsAfterIndex = this.tabs.splice(index); // get the tabs after the tab

  this.tabs = tabsBeforeIndex.concat(tabsAfterIndex); // join them together 
  return this;
 };

// Let's create three browser windows
var workWindow = new Window(['GMail', 'Inbox', 'Work mail', 'Docs', 'freeCodeCamp']); // Your mailbox, drive, and other work sites
var socialWindow = new Window(['FB', 'Gitter', 'Reddit', 'Twitter', 'Medium']); // Social sites
var videoWindow = new Window(['Netflix', 'YouTube', 'Vimeo', 'Vine']); //  Entertainment sites

// Now perform the tab opening, closing, and other operations
var finalTabs = socialWindow
                    .tabOpen() // Open a new tab for cat memes
                    .join(videoWindow.tabClose(2)) // Close third tab in video window, and join
                    .join(workWindow.tabClose(1).tabOpen());

alert(finalTabs.tabs);
```

Day 57, May 30, 2011
Today's progress: Functional programming:
-Avoid Mutations and side effects:

```
// the global variable
var fixedValue = 4;

function incrementer () {
  // Add your code below this line
  
    return fixedValue + 1;
  
  
  // Add your code above this line
}

var newValue = incrementer(); // Should equal 5
console.log(fixedValue); // Should print 4

```
-Pass Arguments to avoid external dependence in a function
```
// the global variable
var fixedValue = 4;

// Add your code below this line
function incrementer (fixedValue) {  
  
  if (fixedValue > 0) {
    
     return fixedValue + 1;
  }
  
  // Add your code above this line
}

var newValue = incrementer(fixedValue); // Should equal 5
console.log(fixedValue); // Should print 4
```

-Refactor Global Variables out of Functions:
```
// the global variable
var bookList = ["The Hound of the Baskervilles", "On The Electrodynamics of Moving Bodies", "Philosophiæ Naturalis Principia Mathematica", "Disquisitiones Arithmeticae"];

/* This function should add a book to the list and return the list */
// New parameters should come before the bookName one

// Add your code below this line
function add (list, bookName) {
  
  return [...list, bookName];
  
  // Add your code above this line
}

/* This function should remove a book from the list and return the list */
// New parameters should come before the bookName one

// Add your code below this line
function remove (list, bookName) {
  if (list.indexOf(bookName) >= 0) {
    
     return list.filter(names => names !== bookName);
    
    // Add your code above this line
    }
}

var newBookList = add(bookList, 'A Brief History of Time');
var newerBookList = remove(bookList, 'On The Electrodynamics of Moving Bodies');
var newestBookList = remove(add(bookList, 'A Brief History of Time'), 'On The Electrodynamics of Moving Bodies');

console.log(bookList);
```
Reference used for this challenge : https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter


Day 58- June 01, 2019
Today's progress-
-Use the Map method to extract data from an array
-Implement Map on a protogype


Day 59- June 03, 2019
Use filter and map methods to extract data from array
```
// the global variable
var watchList = [
                 {  
                   "Title": "Inception",
                   "Year": "2010",
                   "Rated": "PG-13",
                   "Released": "16 Jul 2010",
                   "Runtime": "148 min",
                   "Genre": "Action, Adventure, Crime",
                   "Director": "Christopher Nolan",
                   "Writer": "Christopher Nolan",
                   "Actors": "Leonardo DiCaprio, Joseph Gordon-Levitt, Ellen Page, Tom Hardy",
                   "Plot": "A thief, who steals corporate secrets through use of dream-sharing technology, is given the inverse task of planting an idea into the mind of a CEO.",
                   "Language": "English, Japanese, French",
                   "Country": "USA, UK",
                   "Awards": "Won 4 Oscars. Another 143 wins & 198 nominations.",
                   "Poster": "http://ia.media-imdb.com/images/M/MV5BMjAxMzY3NjcxNF5BMl5BanBnXkFtZTcwNTI5OTM0Mw@@._V1_SX300.jpg",
                   "Metascore": "74",
                   "imdbRating": "8.8",
                   "imdbVotes": "1,446,708",
                   "imdbID": "tt1375666",
                   "Type": "movie",
                   "Response": "True"
                },
                {  
                   "Title": "Interstellar",
                   "Year": "2014",
                   "Rated": "PG-13",
                   "Released": "07 Nov 2014",
                   "Runtime": "169 min",
                   "Genre": "Adventure, Drama, Sci-Fi",
                   "Director": "Christopher Nolan",
                   "Writer": "Jonathan Nolan, Christopher Nolan",
                   "Actors": "Ellen Burstyn, Matthew McConaughey, Mackenzie Foy, John Lithgow",
                   "Plot": "A team of explorers travel through a wormhole in space in an attempt to ensure humanity's survival.",
                   "Language": "English",
                   "Country": "USA, UK",
                   "Awards": "Won 1 Oscar. Another 39 wins & 132 nominations.",
                   "Poster": "http://ia.media-imdb.com/images/M/MV5BMjIxNTU4MzY4MF5BMl5BanBnXkFtZTgwMzM4ODI3MjE@._V1_SX300.jpg",
                   "Metascore": "74",
                   "imdbRating": "8.6",
                   "imdbVotes": "910,366",
                   "imdbID": "tt0816692",
                   "Type": "movie",
                   "Response": "True"
                },
                {
                   "Title": "The Dark Knight",
                   "Year": "2008",
                   "Rated": "PG-13",
                   "Released": "18 Jul 2008",
                   "Runtime": "152 min",
                   "Genre": "Action, Adventure, Crime",
                   "Director": "Christopher Nolan",
                   "Writer": "Jonathan Nolan (screenplay), Christopher Nolan (screenplay), Christopher Nolan (story), David S. Goyer (story), Bob Kane (characters)",
                   "Actors": "Christian Bale, Heath Ledger, Aaron Eckhart, Michael Caine",
                   "Plot": "When the menace known as the Joker wreaks havoc and chaos on the people of Gotham, the caped crusader must come to terms with one of the greatest psychological tests of his ability to fight injustice.",
                   "Language": "English, Mandarin",
                   "Country": "USA, UK",
                   "Awards": "Won 2 Oscars. Another 146 wins & 142 nominations.",
                   "Poster": "http://ia.media-imdb.com/images/M/MV5BMTMxNTMwODM0NF5BMl5BanBnXkFtZTcwODAyMTk2Mw@@._V1_SX300.jpg",
                   "Metascore": "82",
                   "imdbRating": "9.0",
                   "imdbVotes": "1,652,832",
                   "imdbID": "tt0468569",
                   "Type": "movie",
                   "Response": "True"
                },
                {  
                   "Title": "Batman Begins",
                   "Year": "2005",
                   "Rated": "PG-13",
                   "Released": "15 Jun 2005",
                   "Runtime": "140 min",
                   "Genre": "Action, Adventure",
                   "Director": "Christopher Nolan",
                   "Writer": "Bob Kane (characters), David S. Goyer (story), Christopher Nolan (screenplay), David S. Goyer (screenplay)",
                   "Actors": "Christian Bale, Michael Caine, Liam Neeson, Katie Holmes",
                   "Plot": "After training with his mentor, Batman begins his fight to free crime-ridden Gotham City from the corruption that Scarecrow and the League of Shadows have cast upon it.",
                   "Language": "English, Urdu, Mandarin",
                   "Country": "USA, UK",
                   "Awards": "Nominated for 1 Oscar. Another 15 wins & 66 nominations.",
                   "Poster": "http://ia.media-imdb.com/images/M/MV5BNTM3OTc0MzM2OV5BMl5BanBnXkFtZTYwNzUwMTI3._V1_SX300.jpg",
                   "Metascore": "70",
                   "imdbRating": "8.3",
                   "imdbVotes": "972,584",
                   "imdbID": "tt0372784",
                   "Type": "movie",
                   "Response": "True"
                },
                {
                   "Title": "Avatar",
                   "Year": "2009",
                   "Rated": "PG-13",
                   "Released": "18 Dec 2009",
                   "Runtime": "162 min",
                   "Genre": "Action, Adventure, Fantasy",
                   "Director": "James Cameron",
                   "Writer": "James Cameron",
                   "Actors": "Sam Worthington, Zoe Saldana, Sigourney Weaver, Stephen Lang",
                   "Plot": "A paraplegic marine dispatched to the moon Pandora on a unique mission becomes torn between following his orders and protecting the world he feels is his home.",
                   "Language": "English, Spanish",
                   "Country": "USA, UK",
                   "Awards": "Won 3 Oscars. Another 80 wins & 121 nominations.",
                   "Poster": "http://ia.media-imdb.com/images/M/MV5BMTYwOTEwNjAzMl5BMl5BanBnXkFtZTcwODc5MTUwMw@@._V1_SX300.jpg",
                   "Metascore": "83",
                   "imdbRating": "7.9",
                   "imdbVotes": "876,575",
                   "imdbID": "tt0499549",
                   "Type": "movie",
                   "Response": "True"
                }
];

// Add your code below this line
let watchListOne = watchList.filter(function (item) {
   return item.imdbRating >= 8;
} );
var filteredList = watchListOne.map(function (item){
  return {title: item["Title"], rating: item["imdbRating"]}
} );

// Add your code above this line

console.log(filteredList); 
```
https://repl.it/@meeramenon07/TinyNovelFont
- Implement the filter method on a prototype
It would teach us a lot about the filter method if we try to implement a version of it that behaves exactly like Array.prototype.filter(). It can use either a for loop or Array.prototype.forEach().

Note: A pure function is allowed to alter local variables defined within its scope, although, it's preferable to avoid that as well.


Write your own Array.prototype.myFilter(), which should behave exactly like Array.prototype.filter(). You may use a for loop or the Array.prototype.forEach() method.

```
/ the global Array
var s = [23, 65, 98, 5];

Array.prototype.myFilter = function(callback){
  var newArray = [];
  // Add your code below this line
  for(let i = 0; i < this.length; i++){
    if(callback(this[i], i, this)) newArray.push(this[i]);
  }
  // Add your code above this line
  return newArray;

};

var new_s = s.myFilter(function(item){
  return item % 2 === 1;
});
console.log(new_s);
```

-Return Part of an array using slice method:

Functional Programming: Return Part of an Array Using the slice Method
The slice method returns a copy of certain elements of an array. It can take two arguments, the first gives the index of where to begin the slice, the second is the index for where to end the slice (and it's non-inclusive). If the arguments are not provided, the default is to start at the beginning of the array through the end, which is an easy way to make a copy of the entire array. The slice method does not mutate the original array, but returns a new one.

Here's an example:

var arr = ["Cat", "Dog", "Tiger", "Zebra"];
var newArray = arr.slice(1, 3);
// Sets newArray to ["Dog", "Tiger"]

Use the slice method in the sliceArray function to return part of the anim array given the provided beginSlice and endSlice indices. The function should return an array.


```
function sliceArray(anim, beginSlice, endSlice) {
  // Add your code below this line

    return anim.slice(beginSlice, endSlice);
  
  // Add your code above this line
}
var inputAnim = ["Cat", "Dog", "Tiger", "Zebra", "Ant"];
sliceArray(inputAnim, 1, 3);
\\["Dog", "Tiger"]
```

...Day 60, June 04, 2019
Today's progress-
-Functional Programming: Remove Elements from an Array Using slice Instead of splice
A common pattern while working with arrays is when you want to remo
ve items and keep the rest of the array. JavaScript offers the splice method for this, which takes arguments for the index of where to start removing items, then the number of items to remove. If the second argument is not provided, the default is to remove items through the end. However, the splice method mutates the original array it is called on. Here's an example:

var cities = ["Chicago", "Delhi", "Islamabad", "London", "Berlin"];
cities.splice(3, 1); // Returns "London" and deletes it from the cities array
// cities is now ["Chicago", "Delhi", "Islamabad", "Berlin"]
As we saw in the last challenge, the slice method does not mutate the original array, but returns a new one which can be saved into a variable. Recall that the slice method takes two arguments for the indices to begin and end the slice (the end is non-inclusive), and returns those items in a new array. Using the slice method instead of splice helps to avoid any array-mutating side effects.


Rewrite the function nonMutatingSplice by using slice instead of splice. It should limit the provided cities array to a length of 3, and return a new array with only the first three items.

Do not mutate the original array provided to the function.

```
function nonMutatingSplice(cities) {
  // Add your code below this line
  return cities.slice(0,3);
  
  // Add your code above this line
}
var inputCities = ["Chicago", "Delhi", "Islamabad", "London", "Berlin"];
nonMutatingSplice(inputCities);
```

-Functional Programming: Combine Two Arrays Using the concat Method
Concatenation means to join items end to end. JavaScript offers the concat method for both strings and arrays that work in the same way. For arrays, the method is called on one, then another array is provided as the argument to concat, which is added to the end of the first array. It returns a new array and does not mutate either of the original arrays. Here's an example:

[1, 2, 3].concat([4, 5, 6]);
// Returns a new array [1, 2, 3, 4, 5, 6]

Use the concat method in the nonMutatingConcat function to concatenate attach to the end of original. The function should return the concatenated array.

Passed
Your code should use the concat method.
Passed
The first array should not change.
Passed
The second array should not change.
Passed
nonMutatingConcat([1, 2, 3], [4, 5]) should return [1, 2, 3, 4, 5].

```
function nonMutatingConcat(original, attach) {
  // Add your code below this line
     return original.concat(attach);
    
  // Add your code above this line
}
var first = [1, 2, 3];
var second = [4, 5];
nonMutatingConcat(first, second);
```
-Functional Programming: Add Elements to the End of an Array Using concat Instead of push
```
function nonMutatingPush(original, newItem) {
  // Add your code below this line
  return original.concat(newItem);
  
  // Add your code above this line
}
var first = [1, 2, 3];
var second = [4, 5];
nonMutatingPush(first, second);
```

...Day 61, June 05, 2019
Today's progress: Functional Programming lessons-
-Analyse data using reduce method
```
var watchList = [
                 {  
                   "Title": "Inception",
                   "Year": "2010",
                   "Rated": "PG-13",
                   "Released": "16 Jul 2010",
                   "Runtime": "148 min",
                   "Genre": "Action, Adventure, Crime",
                   "Director": "Christopher Nolan",
                   "Writer": "Christopher Nolan",
                   "Actors": "Leonardo DiCaprio, Joseph Gordon-Levitt, Ellen Page, Tom Hardy",
                   "Plot": "A thief, who steals corporate secrets through use of dream-sharing technology, is given the inverse task of planting an idea into the mind of a CEO.",
                   "Language": "English, Japanese, French",
                   "Country": "USA, UK",
                   "Awards": "Won 4 Oscars. Another 143 wins & 198 nominations.",
                   "Poster": "http://ia.media-imdb.com/images/M/MV5BMjAxMzY3NjcxNF5BMl5BanBnXkFtZTcwNTI5OTM0Mw@@._V1_SX300.jpg",
                   "Metascore": "74",
                   "imdbRating": "8.8",
                   "imdbVotes": "1,446,708",
                   "imdbID": "tt1375666",
                   "Type": "movie",
                   "Response": "True"
                },
                {  
                   "Title": "Interstellar",
                   "Year": "2014",
                   "Rated": "PG-13",
                   "Released": "07 Nov 2014",
                   "Runtime": "169 min",
                   "Genre": "Adventure, Drama, Sci-Fi",
                   "Director": "Christopher Nolan",
                   "Writer": "Jonathan Nolan, Christopher Nolan",
                   "Actors": "Ellen Burstyn, Matthew McConaughey, Mackenzie Foy, John Lithgow",
                   "Plot": "A team of explorers travel through a wormhole in space in an attempt to ensure humanity's survival.",
                   "Language": "English",
                   "Country": "USA, UK",
                   "Awards": "Won 1 Oscar. Another 39 wins & 132 nominations.",
                   "Poster": "http://ia.media-imdb.com/images/M/MV5BMjIxNTU4MzY4MF5BMl5BanBnXkFtZTgwMzM4ODI3MjE@._V1_SX300.jpg",
                   "Metascore": "74",
                   "imdbRating": "8.6",
                   "imdbVotes": "910,366",
                   "imdbID": "tt0816692",
                   "Type": "movie",
                   "Response": "True"
                },
                {
                   "Title": "The Dark Knight",
                   "Year": "2008",
                   "Rated": "PG-13",
                   "Released": "18 Jul 2008",
                   "Runtime": "152 min",
                   "Genre": "Action, Adventure, Crime",
                   "Director": "Christopher Nolan",
                   "Writer": "Jonathan Nolan (screenplay), Christopher Nolan (screenplay), Christopher Nolan (story), David S. Goyer (story), Bob Kane (characters)",
                   "Actors": "Christian Bale, Heath Ledger, Aaron Eckhart, Michael Caine",
                   "Plot": "When the menace known as the Joker wreaks havoc and chaos on the people of Gotham, the caped crusader must come to terms with one of the greatest psychological tests of his ability to fight injustice.",
                   "Language": "English, Mandarin",
                   "Country": "USA, UK",
                   "Awards": "Won 2 Oscars. Another 146 wins & 142 nominations.",
                   "Poster": "http://ia.media-imdb.com/images/M/MV5BMTMxNTMwODM0NF5BMl5BanBnXkFtZTcwODAyMTk2Mw@@._V1_SX300.jpg",
                   "Metascore": "82",
                   "imdbRating": "9.0",
                   "imdbVotes": "1,652,832",
                   "imdbID": "tt0468569",
                   "Type": "movie",
                   "Response": "True"
                },
                {  
                   "Title": "Batman Begins",
                   "Year": "2005",
                   "Rated": "PG-13",
                   "Released": "15 Jun 2005",
                   "Runtime": "140 min",
                   "Genre": "Action, Adventure",
                   "Director": "Christopher Nolan",
                   "Writer": "Bob Kane (characters), David S. Goyer (story), Christopher Nolan (screenplay), David S. Goyer (screenplay)",
                   "Actors": "Christian Bale, Michael Caine, Liam Neeson, Katie Holmes",
                   "Plot": "After training with his mentor, Batman begins his fight to free crime-ridden Gotham City from the corruption that Scarecrow and the League of Shadows have cast upon it.",
                   "Language": "English, Urdu, Mandarin",
                   "Country": "USA, UK",
                   "Awards": "Nominated for 1 Oscar. Another 15 wins & 66 nominations.",
                   "Poster": "http://ia.media-imdb.com/images/M/MV5BNTM3OTc0MzM2OV5BMl5BanBnXkFtZTYwNzUwMTI3._V1_SX300.jpg",
                   "Metascore": "70",
                   "imdbRating": "8.3",
                   "imdbVotes": "972,584",
                   "imdbID": "tt0372784",
                   "Type": "movie",
                   "Response": "True"
                },
                {
                   "Title": "Avatar",
                   "Year": "2009",
                   "Rated": "PG-13",
                   "Released": "18 Dec 2009",
                   "Runtime": "162 min",
                   "Genre": "Action, Adventure, Fantasy",
                   "Director": "James Cameron",
                   "Writer": "James Cameron",
                   "Actors": "Sam Worthington, Zoe Saldana, Sigourney Weaver, Stephen Lang",
                   "Plot": "A paraplegic marine dispatched to the moon Pandora on a unique mission becomes torn between following his orders and protecting the world he feels is his home.",
                   "Language": "English, Spanish",
                   "Country": "USA, UK",
                   "Awards": "Won 3 Oscars. Another 80 wins & 121 nominations.",
                   "Poster": "http://ia.media-imdb.com/images/M/MV5BMTYwOTEwNjAzMl5BMl5BanBnXkFtZTcwODc5MTUwMw@@._V1_SX300.jpg",
                   "Metascore": "83",
                   "imdbRating": "7.9",
                   "imdbVotes": "876,575",
                   "imdbID": "tt0499549",
                   "Type": "movie",
                   "totalresponse": "True"
                }
];

// Add your code below this line
 var selectedDirector = watchList.filter(rating => rating.Director === "Christopher Nolan");
 var filteredRating = selectedDirector.map(rating => Number(rating.imdbRating));
 var averageRating = filteredRating.reduce((rating1, rating2) => rating1 + rating2)/selectedDirector.length; 


// Add your code above this line

console.log(averageRating); 
```
... Day 62 June 07, 2019
Today's progress:
Functional Programming: Split a String into an Array Using the split Method

The split method splits a string into an array of strings. It takes an argument for the delimiter, which can be a character to use to break up the string or a regular expression. For example, if the delimiter is a space, you get an array of words, and if the delimiter is an empty string, you get an array of each character in the string.

Here are two examples that split one string by spaces, then another by digits using a regular expression:

var str = "Hello World";
var bySpace = str.split(" ");
// Sets bySpace to ["Hello", "World"]

var otherString = "How9are7you2today";
var byDigits = otherString.split(/\d/);
// Sets byDigits to ["How", "are", "you", "today"]
Since strings are immutable, the split method makes it easier to work with them.


Use the split method inside the splitify function to split str into an array of words. The function should return the array. Note that the words are not always separated by spaces, and the array should not contain punctuation.
```

function splitify(str) {
  // Add your code below this line
    return str.split(/[\W]/g);
  
  // Add your code above this line
}

// => [ 'Hello', 'World', 'I', 'am', 'code' ]

Functional Programming: Combine an Array into a String Using the join Method
The join method is used to join the elements of an array together to create a string. It takes an argument for the delimiter that is used to separate the array elements in the string.

Here's an example:

var arr = ["Hello", "World"];
var str = arr.join(" ");
// Sets str to "Hello World"

Use the join method (among others) inside the sentensify function to make a sentence from the words in the string str. The function should return a string. For example, "I-like-Star-Wars" would be converted to "I like Star Wars". For this challenge, do not use the replace method.

Passed
Your code should use the join method.
Passed
Your code should not use the replace method.
Passed
sentensify("May-the-force-be-with-you") should return a string.
Passed
sentensify("May-the-force-be-with-you") should return "May the force be with you".
Passed
sentensify("The.force.is.strong.with.this.one") should return "The force is strong with this one".
Passed
sentensify("There,has,been,an,awakening") should return "There has been an awakening".
```
function sentensify(str) {
  // Add your code below this line
    return str.split(/\W/).join(' ');
  
  // Add your code above this line
}
sentensify("May-the-force-be-with-you");
```
https://repl.it/@meeramenon07/OldRepentantTrapezoids
```
splitify("Hello World,I-am code");


...Day 63, June 08, 2019
Today's progress : Functional programming lessons:
-Convert strings to url slugs:
```
//global variable
var globalTitle = "Winter is coming";
//add code below
function urlSlug(title){
   return title.toLowerCase().trim().split(/\s+/g).join('-');
}

var winterComing = urlSlug(globalTitle);// should be 'winter-is-coming"
```

-Functional Programming: Use the every Method to Check that Every Element in an Array Meets a Criteria
The every method works with arrays to check if every element passes a particular test. It returns a Boolean value - true if all values meet the criteria, false if not.

For example, the following code would check if every element in the numbers array is less than 10:

var numbers = [1, 5, 8, 0, 10, 11];
numbers.every(function(currentValue) {
  return currentValue < 10;
});
// Returns false

Use the every method inside the checkPositive function to check if every element in arr is positive. The function should return a Boolean value.

```
function checkPositive(arr) {
  // Add your code below this line
    return arr.every(function(currentValue){
        return currentValue > 0;
    });
  
  // Add your code above this line
}
checkPositive([1, 2, 3, -4, 5]);
```
-Functional Programming: Use the some Method to Check that Any Elements in an Array Meet a Criteria
The some method works with arrays to check if any element passes a particular test. It returns a Boolean value - true if any of the values meet the criteria, false if not.

For example, the following code would check if any element in the numbers array is less than 10:

var numbers = [10, 50, 8, 220, 110, 11];
numbers.some(function(currentValue) {
  return currentValue < 10;
});
// Returns true

Use the some method inside the checkPositive function to check if any element in arr is positive. The function should return a Boolean value.

```
function checkPositive(arr) {
  // Add your code below this line
    return arr.some(function(value){
      return value > 0;
   });
  
  // Add your code above this line
}
checkPositive([1, 2, 3, -4, 5]);
```
Day 64, June 10, 2019
Today's progress: started with intermediate algorithm scripting:
-Intermediate Algorithm Scripting: Sum All Numbers in a Range
We'll pass you an array of two numbers. Return the sum of those two numbers plus the sum of all the numbers between them.

The lowest number will not always come first.

sumAll([1, 4]) should return a number.
Passed
sumAll([1, 4]) should return 10.
Passed
sumAll([4, 1]) should return 10.
Passed
sumAll([5, 10]) should return 45.
Passed
sumAll([10, 5]) should return 45.
```
function sumAll(arr) {
  var min = Math.min(...arr);
  var max = Math.max(...arr);
  var sum = 0;
   for(var i = min; i <= max; i++){
     sum += i;
   }
  return sum;
}

sumAll([1, 4]);
```

-Intermediate Algorithm Scripting: Diff Two Arrays
Compare two arrays and return a new array with any items only found in one of the two given arrays, but not both. In other words, return the symmetric difference of the two arrays.

Remember to use Read-Search-Ask if you get stuck. Try to pair program. Write your own code.

Note
You can return the array with its elements in any order.
diffArray([1, 2, 3, 5], [1, 2, 3, 4, 5]) should return an array.
Passed
["diorite", "andesite", "grass", "dirt", "pink wool", "dead shrub"], ["diorite", "andesite", "grass", "dirt", "dead shrub"] should return ["pink wool"].
Passed
["diorite", "andesite", "grass", "dirt", "pink wool", "dead shrub"], ["diorite", "andesite", "grass", "dirt", "dead shrub"] should return an array with one item.
Passed
["andesite", "grass", "dirt", "pink wool", "dead shrub"], ["diorite", "andesite", "grass", "dirt", "dead shrub"] should return ["diorite", "pink wool"].
Passed
["andesite", "grass", "dirt", "pink wool", "dead shrub"], ["diorite", "andesite", "grass", "dirt", "dead shrub"] should return an array with two items.
Passed
["andesite", "grass", "dirt", "dead shrub"], ["andesite", "grass", "dirt", "dead shrub"] should return [].
Passed
["andesite", "grass", "dirt", "dead shrub"], ["andesite", "grass", "dirt", "dead shrub"] should return an empty array.
Passed
[1, 2, 3, 5], [1, 2, 3, 4, 5] should return [4].
Passed
[1, 2, 3, 5], [1, 2, 3, 4, 5] should return an array with one item.
Passed
[1, "calf", 3, "piglet"], [1, "calf", 3, 4] should return ["piglet", 4].
Passed
[1, "calf", 3, "piglet"], [1, "calf", 3, 4] should return an array with two items.
Passed
[], ["snuffleupagus", "cookie monster", "elmo"] should return ["snuffleupagus", "cookie monster", "elmo"].
Passed
[], ["snuffleupagus", "cookie monster", "elmo"] should return an array with three items.
Passed
[1, "calf", 3, "piglet"], [7, "filly"] should return [1, "calf", 3, "piglet", 7, "filly"].
Passed
[1, "calf", 3, "piglet"], [7, "filly"] should return an array with six items.

```
function diffArray(arr1, arr2) {
  
  var filteredArr1 = arr1.filter(function(ele) {
    return arr2.indexOf(ele) == -1;
  });

  var filteredArr2 = arr2.filter(function(ele) {
    return arr1.indexOf(ele) == -1;
  });
  return filteredArr1.concat(filteredArr2);
}

diffArray([1, 2, 3, 5], [1, 2, 3, 4, 5]);
```
```
...DAY 65 June 11, 2019
Today's progress: developing a landing page as part of a side project 
https://codepen.io/meeramenon07/full/RmJyBW


---Day 66, June 12, 2019
Today's progress:Challenges for intermediate algorithm scripting
-Seek and destroy challenge
Remove all elements from the initial array that are of the same value as these arguments
```
function destroyer(arr){
  var args = Array.prototype.slice.call(arguments);
    return arr.filter(function(value){
       return !args.includes(value);
    });
 }
 destroyer([1,2,3,1,2,3], 2,3);

 -Intermediate Algorithm Scripting: Wherefore art thou
Make a function that looks through an array of objects (first argument) and returns an array of all objects that have matching name and value pairs (second argument). Each name and value pair of the source object has to be present in the object from the collection if it is to be included in the returned array.

For example, if the first argument is [{ first: "Romeo", last: "Montague" }, { first: "Mercutio", last: null }, { first: "Tybalt", last: "Capulet" }], and the second argument is { last: "Capulet" }, then you must return the third object from the array (the first argument), because it contains the name and its value, that was passed on as the second argument.

```
function whatIsInAName(collection, source) {
  // What's in a name?
  var arr = [];
  // Only change code below this line
  var keys = Object.keys(source);
  arr = collection.filter(function(obj){
    return keys.every(function(key){
       return obj.hasOwnProperty(key) && obj[key] === source[key];
    });
  });
  
  // Only change code above this line
  return arr;
}

whatIsInAName([{ first: "Romeo", last: "Montague" }, { first: "Mercutio", last: null }, { first: "Tybalt", last: "Capulet" }], { last: "Capulet" });

}
```
-Day 67, June 13, 2019
Today's progress: yet another challenging challenge:Intermediate Algorithm Scripting: Spinal Tap Case
Convert a string to spinal case. Spinal case is all-lowercase-words-joined-by-dashes.

spinalCase("This Is Spinal Tap") should return "this-is-spinal-tap".
Passed
spinalCase("thisIsSpinalTap") should return "this-is-spinal-tap".
Passed
spinalCase("The_Andy_Griffith_Show") should return "the-andy-griffith-show".
Passed
spinalCase("Teletubbies say Eh-oh") should return "teletubbies-say-eh-oh".
Passed
spinalCase("AllThe-small Things") should return "all-the-small-things".
```
function spinalCase(str) {
  // "It's such a fine line between stupid, and clever."
  // --David St. Hubbins
  return str.split(/\s+|_+|(?=[A-Z][a-z])/).join('-').toLowerCase();
}

spinalCase('This Is Spinal Tap');

```
link to solution : [https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/intermediate-algorithm-scripting/spinal-tap-case]

-Day 68, June 15, 2019
Today's progress- PigLatin challenge
Intermediate Algorithm Scripting: Pig Latin
Translate the provided string to pig latin.

Pig Latin takes the first consonant (or consonant cluster) of an English word, moves it to the end of the word and suffixes an "ay".

If a word begins with a vowel you just add "way" to the end.

Input strings are guaranteed to be English words in all lowercase.

translatePigLatin("california") should return "aliforniacay".
Passed
translatePigLatin("paragraphs") should return "aragraphspay".
Passed
translatePigLatin("glove") should return "oveglay".
Passed
translatePigLatin("algorithm") should return "algorithmway".
Passed
translatePigLatin("eight") should return "eightway".
Passed
Should handle words where the first vowel comes in the end of the word.
Passed
Should handle words without vowels.

```
function translatePigLatin(str) {
  var regex = /[aeiou]/gi;
  let pigLatin = '';
  //check if the word begins with a vowel
  if(str[0].match(regex)){
    pigLatin = str + "way";
  }else if (str.match(regex)=== null){
    pigLatin = str + "ay";
  }else{
    var vowelIndice = str.indexOf(str.match(regex)[0]);
     return str.substr(vowelIndice) + str.substr(0, vowelIndice) + "ay";
  }
  return pigLatin;
}

translatePigLatin("eight");

Day 69, June 17, 2019
Today's progress: continuing with intermediate algorith scripting- it is to challenging that I am getting imposter syndrome trying to solve these challenges
-Intermediate Algorithm Scripting: Search and Replace
Perform a search and replace on the sentence using the arguments provided and return the new sentence.

First argument is the sentence to perform the search and replace on.

Second argument is the word that you will be replacing (before).

Third argument is what you will be replacing the second argument with (after).

Note
Preserve the case of the first character in the original word when you are replacing it. For example if you mean to replace the word "Book" with the word "dog", it should be replaced as "Dog"

function myReplace(str, before, after) {
   var index = str.indexOf(before);
   if(str[index] === str[index].toUpperCase()){
      after = after.charAt(0).toUpperCase() + after.slice(1);
   }
   str = str.replace(before, after);
  return str;
}

myReplace("A quick brown fox jumped over the lazy dog", "jumped", "leaped");


...Day 70, June 18, 2019
Today's progress: solved two intermediate algorithms
-Challenge : DNA Pairing
Solution:

function pairElement(str){

  var paired = [];
  var search = function(char){
     switch(char){
        case 'A' :
        paired.push(['A', 'T']);
        break;
        case 'T' :
        paired.push(['T', 'A']);
        break;
        case 'C' :
        paired.push(['C', 'G']);
        break;
        case 'G' :
        paired.push(['G', 'C']);
        break;
     }
  }
  for (var i = 0; i < str.length; i++){
     search (str[i]);
  }
  return paired;
}
pairElement("GCG");


- Challenge : Find Missing Letters:

Find the missing letters in the given passed range and if all the letters are present in a given range, then, return undefined.
My solution: 

function fearNotLetter(str){
      var startCode = str.charCodeAt(0);
      for(var i = 0; i < str.length; i++){
          if (str.charCodeAt(i) !== startCode){
             return String.fromCharCode(startCode);
          }else startCode++;
      }
}
fearNotLetter("abc");


...Day 71, June 19, 2019
Today's progress: Intermediate Algorithm Scripting: Sorted Union
Write a function that takes two or more arrays and returns a new array of unique values in the order of the original provided arrays.

In other words, all values present from all arrays should be included in their original order, but with no duplicates in the final array.

The unique numbers should be sorted by their original order, but the final array should not be sorted in numerical order.

Check the assertion tests for examples
```
function uniteUnique(arr) {

  var finalArr = [];
  for(var i = 0; i < arguments.length; i++){
    var arrayArguments = arguments[i];
  for(var j = 0; j < arrayArguments.length; j++){
    var indexValue = arrayArguments[j];

    if(finalArr.indexOf(indexValue) === -1){
      finalArr.push(indexValue);
    }
  }
  }
  return finalArr;
}

uniteUnique([1, 3, 2], [5, 2, 1, 4], [2, 1]);

...Day 72, June 20, 2019
Today's progress; intermediate js algorithm scripting challenge solving
Convert characters &, >, <, ", ', in a string to their corresponding html entities.
The solution
```
function convertHTML(str){
 var convert = str.split('');
 for (var i = 0; i < str.length; i++){
   switch(convert[i]){
    case'&' : 
     convert[i] = '&amp;';
     break;
    case '<' :
     convert[i] = '&lt;';
     break;
    case '>' :
     convert[i] - '&gt;';
     break;
    case '"' :
     convert[i] = '&quot;';
     break;
    case "'" :
    convert[i] = '&apos;';
    break;
   case '<>' :
    convert[i] = '&lt;&gt;';
    break;
  }
 }
  return convert.join('');
}
convertHTML("Dolce & Gabbana");// logs => 'Dolce &amp; Gabbana'

   }
   
 }
}

Day 73 June 22, 2019
Today's progress..continuing with algorithm challenges 
Challenge: Given a positive number, return the sum of all Fibonacci numbers that are less than or equal to num. 

function sumFibs(num){
 var prevNum = 0;
 var currNum = 1;
 var result = 0;
 while(currNum <= num){
   if(currNum % 2 !== 0 ){
    result += currNum;
   }
   currNum += prevNum;
   prevNum = currNum - prevNum;
 }
 return result;
}
sum Fibs(4);
```
Day 74 June 23/6/19
Today's progress: Sum All Primes challenge
Task:Sum all the prime numbers up to and including the provided number.

A prime number is defined as a number greater than one and having only two divisors, one and itself. For example, 2 is a prime number because it's only divisible by one and two.

The provided number may not be a prime.

Solution
```
function sumPrimes(num) {
  var sum = 0;
  function chkPrime(i){
    for (var j = 2; j < i; j++){
       if(i % j === 0){
         return false;
       }
    }
    return true;
  }
  for(var i = 2; i <= num; i++){
     if(chkPrime(i)){
      sum += i;
   }
  }
  return sum;
}

sumPrimes(10);
If the number is divisible by anything other than itself for example in this case j, then it is not a prime number or else it is prime and if the prime check number is confirmed then return iteration is sum+= i 


```
Day 75 June 24, 2019
Today's progress: continuing with intermediate algorithm scripting
Find the smallest common multiple of the provided parameters that can be evenly divided by both, as well as by all sequential numbers in the range between these parameters.

The range will be an array of two numbers that will not necessarily be in numerical order.

For example, if given 1 and 3, find the smallest common multiple of both 1 and 3 that is also evenly divisible by all numbers between 1 and 3. The answer here would be 6.

smallestCommons([1, 5]) should return a number.
Passed
smallestCommons([1, 5]) should return 60.
Passed
smallestCommons([5, 1]) should return 60.
Passed
smallestCommons([2, 10]) should return 2520.
Passed
smallestCommons([1, 13]) should return 360360.
Passed
smallestCommons([23, 18]) should return 6056820.
1
```
function smallestCommons(arr) {
  arr.sort(function(a,b){
    return b-a;
  });
  var resultArr = [];
  for(var i = arr[0]; i >= arr[1]; i--){
    resultArr.push(i);
  }
  var quotient = 0;
  var loop = 1;
  var n;
  do{
    quotient = resultArr[0] * resultArr[1] * loop;
    for(n = 2; n < resultArr.length; n++){
      if(quotient % resultArr[n] !== 0){
        break;
      }
    }
    loop++;
  }while (n !== resultArr.length);
    return quotient;
  
  

  
}


smallestCommons([1,5]);
```

Day 76, June 26, 2019
Today's progress : Intermediate algorithm scripting lessons
Intermediate Algorithm Scripting: Drop it
Given the array arr, iterate through and remove each element starting from the first element (the 0 index) until the function func returns true when the iterated element is passed through it.

Then return the rest of the array once the condition is satisfied, otherwise, arr should be returned as an empty array.

dropElements([1, 2, 3, 4], function(n) {return n >= 3;}) should return [3, 4].
Passed
dropElements([0, 1, 0, 1], function(n) {return n === 1;}) should return [1, 0, 1].
Passed
dropElements([1, 2, 3], function(n) {return n > 0;}) should return [1, 2, 3].
Passed
dropElements([1, 2, 3, 4], function(n) {return n > 5;}) should return [].
Passed
dropElements([1, 2, 3, 7, 4], function(n) {return n > 3;}) should return [7, 4].
Passed
dropElements([1, 2, 3, 9, 2], function(n) {return n > 2;}) should return [3, 9, 2].
```

function dropElements(arr, func) {
  // Drop them elements.
   while(!func(arr[0])){
      arr.shift();
   }
  return arr;
}
dropElements([1, 2, 3], function(n) {return n < 3; });

```
for my reference this explanation that I got from Richard Middleton's article in Mediumm is a great one to understand for later remembrance of this solution:
Starting Code
function dropElements(arr, func) {
 // Drop them elements.
 return arr;
}
dropElements([1, 2, 3], function(n) {return n < 3; });
What It Means
Similar to the problem before it (Finders Keepers — solution), this challenge takes a function as an argument that has to return true.

You have two arguments passed in with the function call.

dropElements([1, 2, 3], function(n) {return n < 3; });
The first is an array: [1, 2, 3]

The second is a function: [function(n){return n < 3;}

What you need to do is remove items in the array (arr) until the second argument returns true, then return the rest of the array.

The second argument returns a true or false when it runs.

Logic
So let’s take a look at this.

First, while our func is not true, or in other words isfalse we need to do something.


While func returns not true at the arrays 0 position.
Then, we need to remove the array item at the 0 position. We will do this with the shift command which takes the first element in an array and removes it.


So for example if we pass in the first item arr[0] (the number 1) and it returns false, we need to remove arr[0] from our array, shortening our array.

The Truth
When finally our func returns true, the loop will break. So in our test case.

our arr[1, 2, 3]

our (simplified)func {return n < 3;}

So our result should be [1, 2, 3] because 1 < 3 therefore for our while loop is broken and arr is returned.

If we took another test case.

dropElements([1, 2, 3, 4], function(n) {return n >= 3;});
Our result would be [3, 4] because 1 is not >= 3, 2 also is not but 3 is >= 3 and so is 4.

I also see that the alternate solution as follows also passes the test :
```

function dropElements(arr, func) {
  // Drop them elements.
   while(!func(arr[0]) && arr.length > 0){
      arr.shift();
   }
  return arr;
}
dropElements([1, 2, 3], function(n) {return n < 3; });

```

Day 77 June 27, 2019
Today's progress: Intermediate algorithm scripting practising challenge Steamroller challenge:
Flatten a nested array. You must account for varying levels of nesting.
steamrollArray([[["a"]], [["b"]]]) should return ["a", "b"].
Passed
steamrollArray([1, [2], [3, [[4]]]]) should return [1, 2, 3, 4].
Passed
steamrollArray([1, [], [3, [[4]]]]) should return [1, 3, 4].
Passed
steamrollArray([1, {}, [3, [[4]]]]) should return [1, {}, 3, 4].




```
function steamrollArray(arr) {
  // I'm a steamroller, baby
  var resultArray = [];
  function flatten(arr){
    arr.forEach(function(item){
      if(!Array.isArray(item)){
        resultArray.push(item);
      }else{
        flatten(item);
      }
    });
  }
  flatten(arr);
   return resultArray;

}

steamrollArray([1, [2], [3, [[4]]]]);
```

Day 78, June 28, 2019
Today's progress : continuing with lessons from intermediate algorithm scripting javascript
Intermediate Algorithm Scripting: Binary Agents
Return an English translated sentence of the passed binary string.

The binary string will be space separated.

binaryAgent("01000001 01110010 01100101 01101110 00100111 01110100 00100000 01100010 01101111 01101110 01100110 01101001 01110010 01100101 01110011 00100000 01100110 01110101 01101110 00100001 00111111") should return "Aren't bonfires fun!?"

binaryAgent("01001001 00100000 01101100 01101111 01110110 01100101 00100000 01000110 01110010 01100101 01100101 01000011 01101111 01100100 01100101 01000011 01100001 01101101 01110000 00100001") should return "I love FreeCodeCamp!"

```

function binaryAgent(str) {
return String.fromCharCode(...str.split(' ').map(function(char){
    return(parseInt(char,2));
  }));

  return str;
}

binaryAgent("01000001 01110010 01100101 01101110 00100111 01110100 00100000 01100010 01101111 01101110 01100110 01101001 01110010 01100101 01110011 00100000 01100110 01110101 01101110 00100001 00111111");
```

Day 79, June 30, 2019
Today's progress: Continuing with intermediate algorithm scripting
Intermediate Algorithm Scripting: Everything Be True
Check if the predicate (second argument) is truthy on all elements of a collection (first argument).

In other words, you are given an array collection of objects. The predicate pre will be an object property and you need to return true if its value is truthy. Otherwise, return false.

In JavaScript, truthy values are values that translate to true when evaluated in a Boolean context.

Remember, you can access object properties through either dot notation or [] notation.

truthCheck([{"user": "Tinky-Winky", "sex": "male"}, {"user": "Dipsy", "sex": "male"}, {"user": "Laa-Laa", "sex": "female"}, {"user": "Po", "sex": "female"}], "sex") should return true.
Passed
truthCheck([{"user": "Tinky-Winky", "sex": "male"}, {"user": "Dipsy"}, {"user": "Laa-Laa", "sex": "female"}, {"user": "Po", "sex": "female"}], "sex") should return false.
Passed
truthCheck([{"user": "Tinky-Winky", "sex": "male", "age": 0}, {"user": "Dipsy", "sex": "male", "age": 3}, {"user": "Laa-Laa", "sex": "female", "age": 5}, {"user": "Po", "sex": "female", "age": 4}], "age") should return false.
Passed
truthCheck([{"name": "Pete", "onBoat": true}, {"name": "Repeat", "onBoat": true}, {"name": "FastFoward", "onBoat": null}], "onBoat") should return false
Passed
truthCheck([{"name": "Pete", "onBoat": true}, {"name": "Repeat", "onBoat": true, "alias": "Repete"}, {"name": "FastFoward", "onBoat": true}], "onBoat") should return true
Passed
truthCheck([{"single": "yes"}], "single") should return true
Passed
truthCheck([{"single": ""}, {"single": "double"}], "single") should return false
Passed
truthCheck([{"single": "double"}, {"single": undefined}], "single") should return false
Passed
truthCheck([{"single": "double"}, {"single": NaN}], "single") should return false
1

```

function truthCheck(collection, pre) {
  // Is everyone being true?
  var array = [];
  for(var i = 0; i < collection.length; i++){
    if(!collection[i][pre]){
      array.push(collection[i]);
      

    }
  }
  if (array.length === 0){
    return true;
  }
  else{
    return false;
  }
  
}

truthCheck([{"user": "Tinky-Winky", "sex": "male"}, {"user": "Dipsy", "sex": "male"}, {"user": "Laa-Laa", "sex": "female"}, {"user": "Po", "sex": "female"}], "sex");
```
Day 80 July 2, 2019
Today's progress- Continuing with the intermediate algorithm scripting 
Intermediate Algorithm Scripting: Arguments Optional
Create a function that sums two arguments together. If only one argument is provided, then return a function that expects one argument and returns the sum.

For example, addTogether(2, 3) should return 5, and addTogether(2) should return a function.

Calling this returned function with a single argument will then return the sum:

var sumTwoAnd = addTogether(2);

sumTwoAnd(3) returns 5.

If either argument isn't a valid number, return undefined.

addTogether(2, 3) should return 5.
Passed
addTogether(2)(3) should return 5.
Passed
addTogether("http://bit.ly/IqT6zt") should return undefined.
Passed
addTogether(2, "3") should return undefined.
Passed
addTogether(2)([3]) should return undefined.
```

function addTogether() {
  const args = [...arguments];
   return args.some(arg => typeof arg !== "number")? undefined : args.length > 1?
    args.reduce((a,b) => a+b, 0) : arg => typeof arg !== "number" ? undefined : arg + args[0];
  
}

addTogether(2,3);
```

Day 81, July 4, 2019(skipped on July 3)
Today's progress: Intermediate javascript lesson
Intermediate Algorithm Scripting: Make a Person
Fill in the object constructor with the following methods below:

getFirstName() getLastName() getFullName() setFirstName(first) setLastName(last) setFullName(firstAndLast)
Run the tests to see the expected output for each method.

The methods that take an argument must accept only one argument and it has to be a string.

These methods must be the only available means of interacting with the object.

Object.keys(bob).length should return 6.
Passed
bob instanceof Person should return true.
Passed
bob.firstName should return undefined.
Passed
bob.lastName should return undefined.
Passed
bob.getFirstName() should return "Bob".
Passed
bob.getLastName() should return "Ross".
Passed
bob.getFullName() should return "Bob Ross".
Passed
bob.getFullName() should return "Haskell Ross" after bob.setFirstName("Haskell").
Passed
bob.getFullName() should return "Haskell Curry" after bob.setLastName("Curry").
Passed
bob.getFullName() should return "Haskell Curry" after bob.setFullName("Haskell Curry").
Passed
bob.getFirstName() should return "Haskell" after bob.setFullName("Haskell Curry").
Passed
bob.getLastName() should return "Curry" after bob.setFullName("Haskell Curry").
```
Solution:
var Person = function(firstAndLast) {
  var firstName = firstAndLast.split(" ")[0];
  var lastName = firstAndLast.split(" ")[1];

  this.getLastName = function(){
    return lastName;
  };

  this.getFirstName = function(){
    return firstName;
  };
  // Complete the method below and implement the others similarly
  this.getFullName = function() {
    return firstName + " " + lastName;
  };
  this.setFirstName = function(name){
    firstName = name;
  };

  this.setLastName = function(name){
    lastName = name;
  };

  this.setFullName = function(name){
     firstName = name.split(" ")[0];
     lastName = name.split(" ")[1];
  };
  
};

var bob = new Person('Bob Ross');
bob.getFullName();

Day 82 practise time
https://codepen.io/meeramenon07/full/GbBrgb


```
Day 83 July 7, 2019
Today's progress: javascript intermediate algorithm scripting lesson-The final challenge in this chapter
Intermediate Algorithm Scripting: Map the Debris
Return a new array that transforms the elements' average altitude into their orbital periods (in seconds).

The array will contain objects in the format {name: 'name', avgAlt: avgAlt}.

You can read about orbital periods on Wikipedia.

The values should be rounded to the nearest whole number. The body being orbited is Earth.

The radius of the earth is 6367.4447 kilometers, and the GM value of earth is 398600.4418 km3s-2.

orbitalPeriod([{name : "sputnik", avgAlt : 35873.5553}]) should return [{name: "sputnik", orbitalPeriod: 86400}].
Passed
orbitalPeriod([{name: "iss", avgAlt: 413.6}, {name: "hubble", avgAlt: 556.7}, {name: "moon", avgAlt: 378632.553}]) should return [{name : "iss", orbitalPeriod: 5557}, {name: "hubble", orbitalPeriod: 5734}, {name: "moon", orbitalPeriod: 2377399}].

```
function orbitalPeriod(arr) {
  var GM = 398600.4418;
  var earthRadius = 6367.4447;
  var resultArr = [];
  var a = 2 * Math.PI;
  var getOrbPeriod = function(object){
    var c = Math.pow(earthRadius + object.avgAlt, 3);
    var b = Math.sqrt(c/GM);
    var orbPeriod = Math.round(a*b);
    delete object.avgAlt;
    object.orbitalPeriod = orbPeriod;
    return object;

  };
  for(var element in arr){
    resultArr.push(getOrbPeriod(arr[element]));
  }
  return resultArr;
}

orbitalPeriod([{name : "sputnik", avgAlt : 35873.5553}]);

```

Day 84 Today's progress: JS Algorithm and data structures Projects
Palindrome Checker
Return true if the given string is a palindrome. Otherwise, return false.

A palindrome is a word or sentence that's spelled the same way both forward and backward, ignoring punctuation, case, and spacing.

Note
You'll need to remove all non-alphanumeric characters (punctuation, spaces and symbols) and turn everything into the same case (lower or upper case) in order to check for palindromes.

We'll pass strings with varying formats, such as "racecar", "RaceCar", and "race CAR" among others.

We'll also pass strings with special symbols, such as "2A3*3a2", "2A3 3a2", and "2_A3*3#A2".

palindrome("eye") should return a boolean.
Passed
palindrome("eye") should return true.
Passed
palindrome("_eye") should return true.
Passed
palindrome("race car") should return true.
Passed
palindrome("not a palindrome") should return false.
Passed
palindrome("A man, a plan, a canal. Panama") should return true.
Passed
palindrome("never odd or even") should return true.
Passed
palindrome("nope") should return false.
Passed
palindrome("almostomla") should return false.
Passed
palindrome("My age is 0, 0 si ega ym.") should return true.
Passed
palindrome("1 eye for of 1 eye.") should return false.
Passed
palindrome("0_0 (: /-\ :) 0-0") should return true.
Passed
palindrome("five|\_/|four") should return false.
```

function palindrome(str) {
  // Good luck!
  var cleanedPalindrome = str.replace(/[\W_]/g, '');
  var forwardPalindrome = cleanedPalindrome.toLowerCase();
  var reversedPalindrome = cleanedPalindrome.toLowerCase().split('').reverse().join('');
  
     if (forwardPalindrome === reversedPalindrome){
      return true;
    }
  else{
  return false;
  }
  
    
} 



palindrome("eye");


```

Day 85- Today's progress : Algorithms and data structures
JavaScript Algorithms and Data Structures Projects: Roman Numeral Converter
Convert the given number into a roman numeral.

All roman numerals answers should be provided in upper-case.

convertToRoman(2) should return "II".
Passed
convertToRoman(3) should return "III".
Passed
convertToRoman(4) should return "IV".
Passed
convertToRoman(5) should return "V".
Passed
convertToRoman(9) should return "IX".
Passed
convertToRoman(12) should return "XII".
Passed
convertToRoman(16) should return "XVI".
Passed
convertToRoman(29) should return "XXIX".
Passed
convertToRoman(44) should return "XLIV".
Passed
rest all passed
```
function convertToRoman(num) {
    var result = '';
    var decimal = [1000, 900, 500, 400, 100, 90, 50, 40, 10, 9, 5, 4, 1];
    var roman = ["M", "CM","D","CD","C", "XC", "L", "XL", "X","IX","V","IV","I"];

    // looping over every element of this array
    for(var i = 0; i < decimal.length; i++){
        //keep trying the  same number until it wont fit anymore
        while ( num % decimal[i] < num){
           //add matching roman number to the result string
            result += roman[i];
            //remove the decimal value of the roman number from num
            num -= decimal[i];
        }
    }

 return result;
}

convertToRoman(36);
```

Day 86 July 11, 2019
Today's progress: solving data structure algorithm project
JavaScript Algorithms and Data Structures Projects: Caesars Cipher
One of the simplest and most widely known ciphers is a Caesar cipher, also known as a shift cipher. In a shift cipher the meanings of the letters are shifted by some set amount.

A common modern use is the ROT13 cipher, where the values of the letters are shifted by 13 places. Thus 'A' ↔ 'N', 'B' ↔ 'O' and so on.

Write a function which takes a ROT13 encoded string as input and returns a decoded string.

All letters will be uppercase. Do not transform any non-alphabetic character (i.e. spaces, punctuation), but do pass them on.

rot13("SERR PBQR PNZC") should decode to FREE CODE CAMP
Passed
rot13("SERR CVMMN!") should decode to FREE PIZZA!
Passed
rot13("SERR YBIR?") should decode to FREE LOVE?
Passed
rot13("GUR DHVPX OEBJA SBK WHZCF BIRE GUR YNML QBT.") should decode to THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG.

function rot13(str) { // LBH QVQ VG!
  return str.split('').map.call(str, function(char){
    var n = char.charCodeAt(0);
    if(n < 65 || n > 90){
      return String.fromCharCode(n);
    }
    else if(n < 78){
      return String.fromCharCode(n+13);
    }
    else return String.fromCharCode(n-13);
  }).join('').toUpperCase();
  
  
}

// Change the inputs below to test
rot13("SERR PBQR PNZC");

Day 87 July 14, 2019
Today's progress: Completed the last of the intermediate algorithms
JavaScript Algorithms and Data Structures Projects: Telephone Number Validator
Return true if the passed string looks like a valid US phone number.

The user may fill out the form field any way they choose as long as it has the format of a valid US number. The following are examples of valid formats for US numbers (refer to the tests below for other variants):

555-555-5555
(555)555-5555
(555) 555-5555
555 555 5555
5555555555
1 555 555 5555
For this challenge you will be presented with a string such as 800-692-7753 or 8oo-six427676;laskdjf. Your job is to validate or reject the US phone number based on any combination of the formats provided above. The area code is required. If the country code is provided, you must confirm that the country code is 1. Return true if the string is a valid US phone number; otherwise return false.

telephoneCheck("555-555-5555") should return a boolean.
Passed
telephoneCheck("1 555-555-5555") should return true.
Passed
telephoneCheck("1 (555) 555-5555") should return true.
Passed
telephoneCheck("5555555555") should return true.
Passed
telephoneCheck("555-555-5555") should return true.
telephoneCheck("(555)555-5555") should return true.
Passed
telephoneCheck("1(555)555-5555") should return true.
Passed
telephoneCheck("555-5555") should return false.
Passed
telephoneCheck("5555555") should return false.
Passed
telephoneCheck("1 555)555-5555") should return false.
Passed
telephoneCheck("1 555 555 5555") should return true.
Passed
telephoneCheck("1 456 789 4444") should return true.
Passed
telephoneCheck("123**&!!asdf#") should return false.
Passed
telephoneCheck("55555555") should return false.
Passed
telephoneCheck("(6054756961)") should return false
Passed
telephoneCheck("2 (757) 622-7382") should return false.
Passed
telephoneCheck("0 (757) 622-7382") should return false.
Passed
telephoneCheck("-1 (757) 622-7382") should return false
Passed
telephoneCheck("2 757 622-7382") should return false.
Passed
telephoneCheck("10 (757) 622-7382") should return false.
Passed
telephoneCheck("27576227382") should return false.
Passed
telephoneCheck("(275)76227382") should return false.
Passed
telephoneCheck("2(757)6227382") should return false.
Passed
telephoneCheck("2(757)622-7382") should return false.
Passed
telephoneCheck("555)-555-5555") should return false.
Passed
telephoneCheck("(555-555-5555") should return false.
Passed
telephoneCheck("(555)5(55?)-5555") should return false.

```
solution:
function telephoneCheck(str) {
  var regex = /^(1\s?)?(\(\d{3}\)|\d{3})[\s\-]?\d{3}[\s\-]?\d{4}$/;
  // Good luck!
  return regex.test(str);
}

telephoneCheck("555-555-5555");

```
Day 88, July 19, 2019
Today's progress: Cash Register  Advanced Algorithm
JavaScript Algorithms and Data Structures Projects: Cash Register
Design a cash register drawer function checkCashRegister() that accepts purchase price as the first argument (price), payment as the second argument (cash), and cash-in-drawer (cid) as the third argument.

cid is a 2D array listing available currency.

The checkCashRegister() function should always return an object with a status key and a change key.

Return {status: "INSUFFICIENT_FUNDS", change: []} if cash-in-drawer is less than the change due, or if you cannot return the exact change.

Return {status: "CLOSED", change: [...]} with cash-in-drawer as the value for the key change if it is equal to the change due.

Otherwise, return {status: "OPEN", change: [...]}, with the change due in coins and bills, sorted in highest to lowest order, as the value of the change key.

Currency Unit	Amount
Penny	$0.01 (PENNY)
Nickel	$0.05 (NICKEL)
Dime	$0.1 (DIME)
Quarter	$0.25 (QUARTER)
Dollar	$1 (DOLLAR)
Five Dollars	$5 (FIVE)
Ten Dollars	$10 (TEN)
Twenty Dollars	$20 (TWENTY)
One-hundred Dollars	$100 (ONE HUNDRED)
Passed
checkCashRegister(19.5, 20, [["PENNY", 1.01], ["NICKEL", 2.05], ["DIME", 3.1], ["QUARTER", 4.25], ["ONE", 90], ["FIVE", 55], ["TEN", 20], ["TWENTY", 60], ["ONE HUNDRED", 100]]) should return an object.
Passed
checkCashRegister(19.5, 20, [["PENNY", 1.01], ["NICKEL", 2.05], ["DIME", 3.1], ["QUARTER", 4.25], ["ONE", 90], ["FIVE", 55], ["TEN", 20], ["TWENTY", 60], ["ONE HUNDRED", 100]]) should return {status: "OPEN", change: [["QUARTER", 0.5]]}.
Passed
checkCashRegister(3.26, 100, [["PENNY", 1.01], ["NICKEL", 2.05], ["DIME", 3.1], ["QUARTER", 4.25], ["ONE", 90], ["FIVE", 55], ["TEN", 20], ["TWENTY", 60], ["ONE HUNDRED", 100]]) should return {status: "OPEN", change: [["TWENTY", 60], ["TEN", 20], ["FIVE", 15], ["ONE", 1], ["QUARTER", 0.5], ["DIME", 0.2], ["PENNY", 0.04]]}.
Passed
checkCashRegister(19.5, 20, [["PENNY", 0.01], ["NICKEL", 0], ["DIME", 0], ["QUARTER", 0], ["ONE", 0], ["FIVE", 0], ["TEN", 0], ["TWENTY", 0], ["ONE HUNDRED", 0]]) should return {status: "INSUFFICIENT_FUNDS", change: []}.
Passed
checkCashRegister(19.5, 20, [["PENNY", 0.01], ["NICKEL", 0], ["DIME", 0], ["QUARTER", 0], ["ONE", 1], ["FIVE", 0], ["TEN", 0], ["TWENTY", 0], ["ONE HUNDRED", 0]]) should return {status: "INSUFFICIENT_FUNDS", change: []}.
Passed
checkCashRegister(19.5, 20, [["PENNY", 0.5], ["NICKEL", 0], ["DIME", 0], ["QUARTER", 0], ["ONE", 0], ["FIVE", 0], ["TEN", 0], ["TWENTY", 0], ["ONE HUNDRED", 0]]) should return {status: "CLOSED", change: [["PENNY", 0.5], ["NICKEL", 0], ["DIME", 0], ["QUARTER", 0], ["ONE", 0], ["FIVE", 0], ["TEN", 0], ["TWENTY", 0], ["ONE HUNDRED", 0]]}.

```
// Create an object which hold the denominations and their values
var denom = [

  { name: 'ONE HUNDRED', val: 100.00},

  { name: 'TWENTY', val: 20.00},
  { name: 'TEN', val: 10.00},
  { name: 'FIVE', val: 5.00},
  { name: 'ONE', val: 1.00},
  { name: 'QUARTER', val: 0.25},
  { name: 'DIME', val: 0.10},
  { name: 'NICKEL', val: 0.05},
  { name: 'PENNY', val: 0.01}
];

function checkCashRegister(price, cash, cid) {
  var output = { status: null, change: [] };
  var change = cash - price;

  // Transform CID array into drawer object
  var register = cid.reduce(function(acc, curr) {
    acc.total += curr[1];
    acc[curr[0]] = curr[1];
    return acc;
  }, { total: 0 });

  // Handle exact change
  if (register.total === change) {
    output.status = 'CLOSED';
    output.change = cid;
    return output;
  }

  // Handle obvious insufficient funds
  if (register.total < change) {
    output.status = 'INSUFFICIENT_FUNDS';
    return output;
  }

  // Loop through the denomination array
  var change_arr = denom.reduce(function(acc, curr) {
    var value = 0;
    // While there is still money of this type in the drawer
    // And while the denomination is larger than the change remaining
    while (register[curr.name] > 0 && change >= curr.val) {
      change -= curr.val;
      register[curr.name] -= curr.val;
      value += curr.val;

      // Round change to the nearest hundreth deals with precision errors
      change = Math.round(change * 100) / 100;
    }
    // Add this denomination to the output only if any was used.
    if (value > 0) {
        acc.push([ curr.name, value ]);
    }
    return acc; // Return the current change_arr
  }, []); // Initial value of empty array for reduce

  // If there are no elements in change_arr or we have leftover change, return
  // the string "Insufficient Funds"
  if (change_arr.length < 1 || change > 0) {
    output.status = 'INSUFFICIENT_FUNDS';
    return output;
  }

  // Here is your change, ma'am.
  output.status = 'OPEN';
  output.change = change_arr;
  return output;
}
// Example cash-in-drawer array:
// [["PENNY", 1.01],
// ["NICKEL", 2.05],
// ["DIME", 3.1],
// ["QUARTER", 4.25],
// ["ONE", 90],
// ["FIVE", 55],
// ["TEN", 20],
// ["TWENTY", 60], 
// ["ONE HUNDRED", 100]]

checkCashRegister(19.5, 20, [["PENNY", 1.01], ["NICKEL", 2.05], ["DIME", 3.1], ["QUARTER", 4.25], ["ONE", 90], ["FIVE", 55], ["TEN", 20], ["TWENTY", 60], ["ONE HUNDRED", 100]]);

```
Day 89, July 20, 2019
Today's progress. I turned the catApp lesson into a project by building it on codepen
https://codepen.io/meeramenon07/full/pMJJqO

Day 90, July 22, 2019
Today;s progress: Completed the cat App coding lessons  today using bootstrap library
HTML :
```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous"/>
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">

<div class="container-fluid">
  <div class="row">
    <div class="col-xs-8">
      <h2 class="text-primary text-center">CatPhotoApp</h2>
    </div>
    <div class="col-xs-4">
      <a href="#"><img class="img-responsive thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
    </div>
  </div>
  <img src="https://bit.ly/fcc-running-cats" class="img-responsive" alt="Three kittens running towards the camera.">
  <div class="row">
    <div class="col-xs-4">
      <button class="btn btn-block btn-primary"><i class="fa fa-thumbs-up"></i> Like</button>
    </div>
    <div class="col-xs-4">
      <button class="btn btn-block btn-info"><i class="fa fa-info-circle"></i> Info</button>
    </div>
    <div class="col-xs-4">
      <button class="btn btn-block btn-danger"><i class="fa fa-trash"></i> Delete</button>
    </div>
  </div>
  <p>Things cats <span class="text-danger">love:</span></p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <div class="row">
      <div class="col-xs-6">
        <label><input type="radio" name="indoor-outdoor"> Indoor</label>
      </div>
      <div class="col-xs-6">
        <label><input type="radio" name="indoor-outdoor"> Outdoor</label>
      </div>
    </div>
    <div class="row">
      <div class="col-xs-4">
        <label><input type="checkbox" name="personality"> Loving</label>
      </div>
      <div class="col-xs-4">
        <label><input type="checkbox" name="personality"> Lazy</label>
      </div>
      <div class="col-xs-4">
        <label><input type="checkbox" name="personality"> Crazy</label>
      </div>
    </div>
    <div class="row">
      <div class="col-xs-7">
    <input type="text" class="form-control" placeholder="cat photo URL" required>
      </div>
      <div class="col-xs-5">
    <button type="submit" class="btn btn-primary"><i class="fa fa-paper-plane"></i> Submit</button>
      </div>
    </div>
  </form>
</div>

The css:
<style>
  h2 {
    font-family: Lobster, Monospace;
  }

  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }
</style>
```
link to project on codepen:
[https://codepen.io/meeramenon07/pen/pMJJqO]
