# cs2110-homework-5-intro-to-assembly-solved
**TO GET THIS SOLUTION VISIT:** [CS2110 Homework 5-Intro to Assembly Solved](https://www.ankitcodinghub.com/product/cs2110-homework-5-intro-to-assembly-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92770&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2110 Homework 5-Intro to Assembly Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Purpose

So far in this class, you have seen how binary or machine code manipulates our circuits to achieve a goal. However, as you have probably figured out, binary can be hard for us to read and debug, so we need an easier way of telling our computers what to do. This is where assembly comes in. Assembly language is symbolic machine code, meaning that we don’t have to write all of the ones and zeros in a program, but rather symbols that translate to ones and zeros. These symbols are translated with something called the assembler. Each assembler is dependent upon the computer architecture on which it was built, so there are many different assembly languages out there. Assembly was widely used before most higher-level languages and is still used today in some cases for direct hardware manipulation.

1.2 Task

The goal of this assignment is to introduce you to programming in LC-3 assembly code. This will involve writing small programs, translating conditionals and loops into assembly, modifying memory, manipulating strings, and converting high-level programs into assembly code.

You will be required to complete the four functions listed below with more in-depth instructions on the following pages:

1. gcd.asm

2. merge.asm

3. studlyCaps.asm 4. palindrome.asm

1.3 Criteria

Your assignment will be graded based on your ability to correctly translate the given pseudocode into LC-3 assembly code. Check the deliverables section for deadlines and other related information. Please use the LC-3 instruction set when writing these programs. More detailed information on each instruction can be found in the Patt/Patel book Appendix A (also on Canvas under “LC-3 Resources”). Please check the rest of this document for some advice on debugging your assembly code, as well some general tips for successfully writing assembly code.

You must obtain the correct values for each function. While we will give partial credit where we can, your code must assemble with no warnings or errors (Complx will tell you if there are any). If your code does not assemble, we will not be able to grade that file and you will not receive any points. Each function is in a separate file, so you will not lose all points if one function does not assemble. Good luck and have fun!

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
2 Detailed Instructions 2.1 Part 1: GCD

To start you off with this homework, we are implementing the GCD function! Store the result of the operation in the label ANSWER. Arguments A and B are stored in memory, and you will load them from there to perform this operation. Implement your assembly code in gcd.asm.

Suggested Pseudocode:

<pre>    ANSWER = 0;
    while (a != b) {
</pre>
<pre>        if (a &gt; b) {
            a = a - b;
</pre>
<pre>        } else {
            b = b - a;
</pre>
} }

ANSWER = a;

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
2.2 Part 2: Array Merge

The second assembly function is to implement the “merge” part of merge-sort into an array in memory. You will be merging two pre-sorted input arrays into a third array, so that the third array is also sorted. The third array will have enough space for the final answer. Use the pseudocode to help plan out your assembly and make sure you are sorting it properly! Implement your assembly code in merge.asm.

Suggested Pseudocode:

<pre>    x = 0; // first index of ARR_X
    y = 0; // first index of ARR_Y
    z = 0; // first index of ARR_RES
    while (x &lt; LENGTH_X &amp;&amp; y &lt; LENGTH_Y) {
</pre>
<pre>        if (ARR_X[x] &lt;= ARR_Y[y]) {
            ARR_RES[z] = ARR_X[x];
            z++:
            x++;
</pre>
<pre>        } else {
            ARR_RES[z] = ARR_Y[y];
            z++;
            y++;
</pre>
} }

<pre>    while (x &lt; LENGTH_X) {
        ARR_RES[z] = ARR_X[x];
        z++;
        x++;
</pre>
<pre>    }
    while (y &lt; LENGTH_Y) {
</pre>
<pre>        ARR_RES[z] = ARR_Y[y];
        z++;
        y++;
</pre>
<pre>    }
    // the final merged array should be in ARR_RES
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
2.3 Part 3: Studly Caps

The third assembly function is to turn a null-terminated string into a string with studly caps. Studly caps, also known as alternating caps, sticky caps, or occasionally “SpongeBob case”, consists of alternating the letters in a string between lowercase and uppercase. In this function, the first letter is expected to be lowercase and the subsequent letters alternate between uppercase and lowercase depending on the index. The index starts at 0, if the index is even, the character should be lowercase. If the index is odd, the character is expected to be uppercase.

The label STRING will contain the address of the first character of the string to be converted. Convert the string in-place, so that the result string is also stored at the same label STRING. Remember that strings are just arrays of consecutive characters. You are given four constants to use in your program, LOWERA which is the value of the ASCII character ‘a’, LOWERZ which is the value of ‘z’, UPPERA which is the value of ‘A’, and UPPERZ which is the value of ‘Z’. Implement your assembly code in studlyCaps.asm

Assume that the strings are random: they can contain characters, numbers, spaces and sym- bols.

To convert a character between lowercase and uppercase, refer to the ASCII table and remember that each of these characters are represented by a word (16-bits) in the LC-3’s memory. This is a null-terminated string, meaning that a 0 will be stored immediately after the final character in memory!

NOTE:

• 0 is the same as ‘\0’ • 0 is different from ‘0’

Suggested Pseudocode:

<pre>    string = "TWENTY 1 ten"
    i = 0;
    while (string[i] != 0) {
</pre>
<pre>        if (i % 2 == 0) {
            // should be lowercase
            if (’A’ &lt;= string[i] &lt;= ’Z’) {
</pre>
<pre>                string[i] = string[i] | 32;
            }
</pre>
<pre>        } else {
            // should be uppercase
            if (’a’ &lt;= string[i] &lt;= ’z’) {
</pre>
<pre>                string[i] = string[i] &amp; ~32;
            }
</pre>
}

i++; }

The result here is tWeNtY 1 TeN.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
2.4 Part 4: Palindromes

For the final problem, your goal is to determine whether a null-terminated string is a palindrome. A palindrome is a word, phrase or a sequence of numbers that reads the same backward as forward. For instance, “racecar” is a palindrome because it is “racecar” when read both backward and forward.

The label STRING will contain the address of the first character of the string to be checked. Remember that this string is null-terminated. The result will be stored at the label RESULT. If the given string is a palindrome, the result should be set to 1. Else, it should be set to 0. Implement your assembly code in palindrome.asm

Assume every alphabetic character in the string is in lowercase. The string can contain num- bers.

NOTE:

• 0 is the same as ‘\0’ • 0 is different from ‘0’

Suggested Pseudocode:

<pre>    string = "racecar";
    len = 0;
</pre>
<pre>    // to find the length of the string
    while (string[len] != ’\0’) {
</pre>
len = len + 1; }

<pre>    // to check whether the string is a palindrome
    result = 1;
    i = 0;
    while (i &lt; length) {
</pre>
<pre>        if (string[i] != string[length - i - 1]) {
            result = 0;
</pre>
break; }

i = i + 1; }

3 Deliverables

Turn in the following files on Gradescope:

1. gcd.asm

2. merge.asm

3. studlyCaps.asm 4. palindrome.asm

Note: Please do not wait until the last minute to run/test your homework. Last minute turn-ins will result in long queue times for grading on Gradescope. You have been warned.

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
4 Running the Autograder and Debugging LC-3 Assembly

When you turn in your files on Gradescope for the first time, you may not receive a perfect score. Does this mean you change one line and spam Gradescope until you get a 100? No! You can use a handy Complx feature called “replay strings”.

<ol>
<li>First off, we can get these replay strings in two places: the local grader, or off of Gradescope. To run the local grader:
• Mac/Linux Users:

<ol>
<li>(a) &nbsp;Navigate to the directory your homework is in (in your terminal on your host machine, not in the Docker container via your browser)</li>
<li>(b) &nbsp;Run the command sudo chmod +x grade.sh</li>
<li>(c) &nbsp;Now run ./grade.sh</li>
</ol>
• Windows Users:

<ol>
<li>(a) &nbsp;In Git Bash (or Docker Quickstart Terminal for legacy Docker installations), navigate to the directory your homework is in</li>
<li>(b) &nbsp;Run chmod +x grade.sh</li>
<li>(c) &nbsp;Run ./grade.sh</li>
</ol>
When you run the script, you should see an output like this:

Copy the string, starting with the leading ’B’ and ending with the final backslash. Do not include the quotation marks.

Side Note: If you do not have Docker installed, you can still use the tester strings to debug your assembly code. In your Gradescope error output, you will see a tester string. When copying, make sure you copy from the first letter to the final backslash and again, don’t copy the quotations.
</li>
<li>Secondly, navigate to the clipboard in your Docker image and paste in the string.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
<ol start="3">
<li>Next, go to the Test Tab and click Setup Replay String</li>
<li>Now, paste your tester string in the box!</li>
<li>Now, Complx is set up with the test that you failed! The nicest part of Complx is the ability to step through each instruction and see how they change register values. To do so, click the step button. To change the number representation of the registers, double click inside the register box.</li>
<li>If you are interested in looking how your code changes different portions of memory, click the view tab and indicate ’New View’</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
7. Now in your new view, go to the area of memory where your data is stored by CTRL+G and insert the address

8. One final tip: to automatically shrink your view down to only those parts of memory that you care about (instructions and data), you can use View Tab → Hide Addresses → Show Only Code/Data.

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
5 Appendix

5.1 Appendix A: ASCII Table

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: ASCII Table — Very Cool and Useful!

</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
5.2 Appendix B: LC-3 Instruction Set Architecture

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
5.3 Appendix C: LC-3 Assembly Programming Requirements and Tips

<ol>
<li>Your code must assemble with NO WARNINGS OR ERRORS. To assemble your program, open the file with Complx. It will complain if there are any issues. If your code does not assemble you WILL get a zero for that file.</li>
<li>Comment your code! This is especially important in assembly, because it’s much harder to interpret what is happening later, and you’ll be glad you left yourself notes on what certain instructions are contributing to the code. Comment things like what registers are being used for and what less intuitive lines of code are actually doing. To comment code in LC-3 assembly just type a semicolon (;), and the rest of that line will be a comment.</li>
<li>Avoid stating the obvious in your comments, it doesn’t help in understanding what the code is doing.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Good Comment

<pre>ADD R3, R3, -1
BRp LOOP
</pre>
Bad Comment

<pre>ADD R3, R3, -1
BRp LOOP
</pre>
</div>
<div class="column">
<pre>; counter--
; if counter == 0 don’t loop again
</pre>
<pre>; Decrement R3
; Branch to LOOP if positive
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="4">
<li>DO NOT assume that ANYTHING in the LC-3 is already zero. Treat the machine as if your program was loaded into a machine with random values stored in the memory and register file.</li>
<li>Following from 3, you can load the file with randomized memory by selecting “File” ¿ “Advanced Load” and selecting randomized registers/memory.</li>
<li>Do NOT execute any data as if it were an instruction (meaning you should put .fills after HALT or RET).</li>
<li>Do not add any comments beginning with @plugin or change any comments of this kind.</li>
<li>Test your assembly. Don’t just assume it works and turn it in.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
12

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
6 6.1

1.

2.

6.2

1.

6.3

1.

2.

6.4

</div>
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 14">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
