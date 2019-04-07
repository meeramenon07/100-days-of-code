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


-
