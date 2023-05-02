Download Link: https://assignmentchef.com/product/solved-compsci121-in4matx141-assignment-1-text-processing-functions
<br>
<h1>General Specifications</h1>




<ol>

 <li>Programing language: You are free to write the program in any programming language of your choice. However, the next homework will work with a web-crawler written in Python 2.7, so we encourage you to use this homework to brush up your knowledge of Python.</li>

 <li>Make sure to break down your program into classes/methods/functions corresponding to the parts in this specification. They will be tested separately.</li>

 <li>The function signatures in this specification are informal; their purpose is to explain the inputs and outputs of the methods.</li>

 <li>At points, the assignment may be underspecified. In those cases, make your own assumptions and be prepared to defend them.</li>

</ol>

<strong> </strong>

<h1>Part A: Word Frequencies (40 points)</h1>

<strong> </strong>

Write a program that takes a text file as a command line argument and outputs the word frequency in decreasing order.

<strong> </strong>

Briefly, implement the following functionality:

<ol>

 <li>Read an input file passed as a <em>command</em>​<em> line argument</em>​. Please ensure you clearly understand what command line arguments are.</li>

 <li>Tokenize the text of the file. A token is a sequence of alphanumeric characters, independent of capitalization (so “<em>Apple” and</em>​ ​ “<em>apple”</em>​           ​ are the same token)</li>

 <li>Count the number of occurrences of each word in the tokens generated.</li>

 <li>Print out the word frequency counts onto the screen. <em>The</em>​<em> print out should be ordered by decreasing frequency. (so, highest frequency words first). Resolve ties alphabetically. </em></li>

</ol>

Here is an example of an input file and corresponding output after computing the word frequency:

<u>Input:</u>




Here’s a fun-fact! White tigers live mostly in “India”.

Wild lions live mostly in “Africa”.




<u>Output (Tokens and their counts):</u>




in – 2 live – 2 mostly – 2

a – 1

africa – 1 fact – 1 fun – 1 here – 1 india – 1 lions – 1 s – 1 tigers – 1 white – 1

wild – 1




NOTE: Tokens should only contain alphanumeric characters (alphabets and numbers). Any other characters such as punctuation marks, symbols, etc. should be eliminated.




The TA will use test text file(s) during the evaluation of your assignment. For this part, it is expected that your program will read this text file, tokenize its contents, count the tokens, and print out the word (token) frequencies in the order specified

above.

<strong> </strong>

<h1>Part B: Intersection of two files (60 points)</h1>




Write a program that reads the contents of two text files and outputs the <em>number</em>​<em> of tokens they have in common</em>​. Here is an example of input/output:










If required, you can reuse code you wrote for part A.




The TA will use test text file(s) during the evaluation of your assignment. Note that some of the text files may be VERY LARGE.




Once you have implemented your program, please perform an analysis of its runtime complexity: does it run in linear time relative to the size of the input? Polynomial time? Exponential time?




For this part, programs that perform better will be given more credit than those that perform poorly. It will help the TA if you specify the run-time complexity of your program in the form of comments in your code.


