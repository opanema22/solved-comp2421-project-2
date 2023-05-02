Download Link: https://assignmentchef.com/product/solved-comp2421-project-2
<br>
In this project you will implement a program that simulates a simple text editor with the undo/redo functionalities allowed. The program will accept statements, one at a time with a maximum of 100 characters per line.




There will be some special commands as follows:

<ol>

 <li><strong>undo</strong>: this will undo (i.e., remove) that last entered statement;</li>

 <li><strong>redo</strong>: this will redo (i.e., re-add) that last removed statement;</li>

 <li><strong>print</strong>: this command will print the entire stored input text; 4. <strong>save</strong>: will save the text to a file called (<strong>txt</strong>);</li>

 <li><strong>quit</strong>: will exit the program and save all results to output.txt</li>

</ol>




Execution example:




MyCommand &gt; This is a test input

MyCommand &gt; COMP2421 – Data structures &amp; Algorithms

MyCommand &gt; test1

MyCommand &gt; <strong>print</strong>

result &gt;

This is a test input

COMP2421 – Data structures &amp; Algorithms test1

MyCommand &gt; <strong>undo</strong>

result &gt;

This is a test input

COMP2421 – Data structures &amp; Algorithms

MyCommand &gt; <strong>redo</strong>

result &gt;

This is a test input

COMP2421 – Data structures &amp; Algorithms test1

MyCommand &gt; test2

MyCommand &gt; test3

MyCommand &gt; <strong>print</strong>

This is a test input

COMP2421 – Data structures &amp; Algorithms test1 test2 test3

MyCommand &gt; <strong>quit</strong> result &gt; Good Bye!




In your implementation, each statement should be stored in a different node. Implementing the undo/redo functionalities can be done through stacks. When printing all statements, you should make sure they are printed in the sequence they were entered.


