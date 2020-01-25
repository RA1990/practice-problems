
# Practice Problems
A repo containing some fun coding challenges. The are in no particular order.

## Bigger words

Build a function that takes in a string and an array of strings. The function should output an array of strings that are longer than the single input string.

- Write a function that takes two parameters
	- Parameter 1 - A string
	- Parameter 2 - An array of strings
- The function should output all the words from the input array (parameter 2) that are longer than the input string (parameter 1)
- Example:
	- `var myArray = ['bug', 'insect', 'mammal', 'reptile', 'mammoth', 'turtles'];`
	- `biggerWords('whales', myArray);`
	- Output - `['reptile', 'mammoth', 'turtles']`

## Total Reverse 

Build a function that takes in an array and reverses it

- Write a function that takes one parameter
	- Parameter 1 - An array of anything
- The function should output an array that is in reverse order from the input array
- Example: 
	- `var myArray = ['hello', 45, 'Bob', 'what', '23'];`
	- `arrayReverse(myArray);`
	- Output - `['23', 'what', 'Bob', 45, 'hello']`
- Avoid using pre-built functions that do something similar

## One to Multi

Build a function that sorts an array into a multidimensional array grouped by data type

- Write a function that takes one parameter 
	- Parameter 1 - An array of anything
- The function should output a multidimensional array grouped by data type
- Example: 
	- `var myArray = ['hello', 34, true, false, 'goodbye', 56, 12, '25', true];`
	- `groupArray(myArray);`
	- Output - `[['hello, 'goodbye', '25'], [34, 56, 12], [true, false, true]]`

## Sort

Build a function that takes in an array of strings and outputs a new array with the same strings in alphabetical order. 

- Write a function that takes one parameter
	- Parameter 1 - An Array of strings
- The function should output an array containing all the strings from the input array but in alphabetical order
- Example:
	-`var myArray = ['mouse', 'cat', 'dog', 'human'];`
	- `sort(myArray);`
	- Output - `['cat', 'dog', 'human', 'mouse']`
- Try doing this using a **Bubble Sort**, if you are unsure what that is <a href="https://www.google.com" target="_blank">Click Here</a>

## FizzBuzz

Build a function that prints the numbers from 1 to 100. But for multiples of three print “Fizz” instead of the number and for the multiples of five print “Buzz”. For numbers which are multiples of both three and five print “FizzBuzz”.

- Write a function that takes no parameters
- The function should output the numbers 1 through 100, following the rules from above

## Spirals

Build a function that takes one parameter and prints out the Fibonacci sequence based on the input parameter. 

- Write a function that takes one parameter
	- Parameter 1 - A number
- The function should output the Fibonacci sequence to the number of spaces set by parameter 1 starting from zero.
- Example:
	- `fibSequence(12);`
	- Output - `0 1 1 2 3 5 8 13 21 34 55 89`
- If you are unfamiliar with the Fibonacci sequence <a href="https://www.google.com" target="_blank">Click Here</a>

## Igpay Atinlay

Build a function that will translate text into "Pig Latin" Take the first consonant and move it to the end of a word and then affix "ay" to the end of that word."

- Write a function that takes one parameter
	- Parameter 1 - A string
- The function should output your input string translated into Pig Latin
	- Example: 
		- `var myString = "Hello my name is Stu"`
		- `translate(myString);
		- Output - `"ellohay ymay ameya siay tusay"`

#### Making it better!

- There are several more rules to Pig Latin, try incorporating as many as you can into your function.
	- There are different rules for words that start with vowel sounds or silent letters for example.
	- <a href="http://en.wikipedia.org/wiki/Pig_Latin">Here</a> is a link to an explanation of all the rules.
- Also try maintaining capitalization of words that are capitalized in your input string.
	- Example: 
		- `"Hello there"` would be `"Ellohay heretay"`

## More to come! 
=======

### Drills Level 0
- instructions
  - each drill set is self-grading.  It will show you which ones are wrong.
  - put your work in the file yourcode.js
  - do not change/remove the function names in yourcode.js, just change the contents/parameters
  - see the results in test.html
  - do not modify test.js
  - the feedback in test.html will tell you what arguments the function will receive
  - the feedback in test.html will tell you what return value is expected from your function
  - multiple tests will be run on your function.  A solution that may work for one test may not work for the other tests.
  
- <a href="https://github.com/Learning-Fuze/practice-problems/blob/master/drills01/README.md" target="_blank">sumArray<br>fitWithinVal<br>getAllNamesShorterThan<br>makeLabel</a>
- <a href="https://github.com/Learning-Fuze/practice-problems/blob/master/drills02/README.md" target="_blank">countOccurences<br>wordLengths<br>getMinMaxMean<br>findMode</a>
- <a href="https://github.com/Learning-Fuze/practice-problems/blob/master/drills03/README.md" target="_blank">getPath<br>getPathParts<br>getCapitalCount<br>correctCalcChecker</a>
- <a href="https://github.com/Learning-Fuze/practice-problems/blob/master/drills04/README.md" target="_blank">jQuery practice problems: changeElements<br>appendTextToElement<br>addClass<br>removeElements</a>
- <a href="https://github.com/Learning-Fuze/practice-problems/blob/master/drills05/README.md" target="_blank">jQuery practice problem: populateRecords</a>
- <a href="https://github.com/Learning-Fuze/practice-problems/blob/master/drills06/README.md" target="_blank">jQuery practice problems: removeClassFromElement<br>hideElements<br>addAttributeToElement<br>addAttributeToElement</a>

### Level 0
- <a href="practice29/README.md" target="_blank">do math</a>
- <a href="practice30/README.md" target="_blank">random number or array element</a>
- <a href="practice31/README.md" target="_blank">math combo</a>
- <a href="practice32/README.md" target="_blank">find middle of string</a>
- <a href="practice33/README.md" target="_blank">invert positive number</a>
- <a href="practice36/README.md" target="_blank">get vowels</a>
- <a href="practice37/README.md" target="_blank">alternate caps</a>

### Level 1
- <a href="practice02/README.md" target="_blank">Array reverser</a>
- <a href="practice03/README.md" target="_blank">Data Type Sorter</a>
- <a href="practice04/README.md" target="_blank">Array sort</a>
- <a href="practice05/README.md" target="_blank">FizzBuzz</a>
- <a href="practice20/README.md" target="_blank">Randomize Array</a>
- <a href="practice21/README.md" target="_blank">Bipolar Loop</a>

### Level 2
- <a href="practice01/README.md" target="_blank">Bigger Words</a>
- <a href="practice06/README.md" target="_blank">Numeric Spirals</a>
- <a href="practice07/README.md" target="_blank">Igpay Atlinlay</a>
- <a href="practice09/README.md" target="_blank">Fitting Words</a>
- <a href="practice11/README.md" target="_blank">Even Odds</a>
- <a href="practice13/README.md" target="_blank">Math Computation Sequences</a>
- <a href="practice17/README.md" target="_blank">Skippy Numbers</a>
- <a href="practice11/README.md" target="_blank">Sort Objects</a>
- <a href="practice22/README.md" target="_blank">Sort Objects by field</a>
- <a href="practice25/README.md" target="_blank">Array Add</a>
- <a href="practice26/README.md" target="_blank">Search Array</a>

### Level 3
- <a href="practice08/README.md" target="_blank">Char Convert</a>
- <a href="practice12/README.md" target="_blank">Math Sequence</a>
- <a href="practice14/README.md" target="_blank">Array Factors</a>
- <a href="practice23/README.md" target="_blank">Find Factors</a>
- <a href="practice28/README.md" target="_blank">Roman Numerals</a>
- <a href="practice38/README.md" target="_blank">Phone Number Conversion</a>

### Level 4
- <a href="practice15/README.md" target="_blank">Numeric Toggles</a>
- <a href="practice24/README.md" target="_blank">Matrix Add</a>

### Level 5
- <a href="practice10/README.md" target="_blank">Permutations</a>
- <a href="practice16/README.md" target="_blank">Factor of Sequence</a>

### Level 6
- **NEW** <a href="practice39/README.md" target="_blank">Wave Patterns (easy/medium)</a>

### Level 7
- <a href="practice35/README.md" target="_blank">Dependency Calculation</a>

### Level 8
- **NEW** <a href="practice39/README.md" target="_blank">Wave Patterns (hard)</a>

### Level 9
- <a href="practice18/README.md" target="_blank">Calculate Multi Average</a>

### Level 10
- <a href="practice27/README.md" target="_blank">Recursive Numeric Spirals<

