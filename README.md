# cmsc216-project-5-solved
**TO GET THIS SOLUTION VISIT:** [CMSC216 Project 5 Solved](https://www.ankitcodinghub.com/product/cmsc216-project-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;71412&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC216 Project 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (4 votes)    </div>
    </div>
In this project you will write AVR assembly code that corresponds to C code provided. There are two deadlines associated with this project:.

<h1>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The Makefile</h1>
In the code distribution you’ll see two .c files for each function you need write; you’ll fill in the third (a .S file).

<ul>
<li>c – A reference C implementation of what you should write.</li>
<li>c – A main() that invokes your code (or the reference, depending on the Makefile) with various inputs to print the output.</li>
<li>S – Here is where you will define the function that in AVR assembly mimics the reference code.</li>
</ul>
The Makefile has several rules. For example, for palindrome.S:

make palindrome_s&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /* builds executable */ make palindrome_s.run /* runs the program using simulator */ make palindrome_s.gdb /* runs the debugger */

Although the base name of the assembly file is palindrome, we use palindrom s. You can also see the expected output for a test based on the reference code (C code). For example, for palindrome.S:

make palindrome_r.run /* runs the reference code (C code) */

Notice the use of r. By the way, the driver code contains the public tests.

<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Specifications</h1>
For each C routine, create an assembly program that produces the same output, given identical input. Your primary goal should be to produce a working version of each program. Your secondary goal is to make it no more complicated than it needs to be.

The input is provided by main(); you will not be expected to read integers or halt (cli/sleep) at the end of your functions. You need only implement the routine, and the _driver.c will invoke the routine as needed.

<h2>2.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Palindrome</h2>
Ask if it seems unclear. Palindromes are words or phrases that are the same forward as backwards, the C code shows an example of how to do it.

You may optimize the code, since array subscript operations are not straightforward. (You need to get to a pointer to read from memory, the pointer is in X, Y, or Z, and although you can access at a constant offset from a pointer (“LDD Rd, Z+q”) there is no single AVR instruction for array subscripting (variable pointer + variable offset).)

<h2>2.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Fibonacci</h2>
Given <em>n </em>as a (uint16_t) parameter, it returns the <em>n</em>th Fibonacci number. This routine <strong>must </strong>be implemented in a recursive fashion otherwise you will lose most of the credit.

<h2>2.3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Integer Square Root</h2>
Compute the square root of an integer, using the bitwise algorithm at <a href="https://en.wikipedia.org/wiki/Integer_square_root">https://en.wikipedia.org/wiki/ </a><a href="https://en.wikipedia.org/wiki/Integer_square_root">Integer_square_root</a><a href="https://en.wikipedia.org/wiki/Integer_square_root">.</a>

You will need the logical shift instructions. To shift left by one, “lsl r24”. To shift left by two, repeat the instruction. Same for shifting right.

<h2>2.4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Reverse Prefix Sum</h2>
Transform an array by adding the value at an index to the sum of the remainder of the array. Return the sum. The return value may be a 16-bit integer, but the array is of 8-bit integers. (Do not concern yourself with behavior on overflow, just assume it will not happen.) The reverse prefix sum routine <strong>must </strong>be implemented in a recursive fashion otherwise you will lose most of the credit.

<h2>2.5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Rules</h2>
<ol>
<li>You may refer as much as you like to the output of avr-gcc -S. You may run “make isqrt_reference.s” for example. We expect you to use this information only to help with individual fragments, for example, to learn how to add two words together, call shift instructions, find which instructions to execute, etc. We expect you to avoid copying any code from the compiler output.</li>
<li>(Restated…) You are expected to write the assembly code; this is preparation for exam questions. You can look at the compiler’s output if you need inspiration, but turning in something conspicuously similar to the compiler’s output will lose (at least) style points. The output of the compiler is inefficient, uncommented, and has an identifiable style that is more complicated than what humans would write.</li>
</ol>
Notice that you don’t need to look at the compiler’s output in order to implement the project.

<ol start="3">
<li>Don’t change the C code.</li>
<li>You don’t have to worry about the maximum length of 80 for a line of code. (You might write long comments.)</li>
<li>Your comments should be descriptive of the intent, not of the action. A comment per line after a semicolon descriptive of what is happening is necessary. (I.e., “stash n for later use” is an ok comment. “move r24 into r20” is not.) A description of the variable that each register represents is useful.</li>
<li>Obey the callee-save and caller-save conventions; you must not clobber registers that the C driver does not expect you to clobber. If you have close control over only calling functions that you have personally written, you may be able to get away with skipping saving some caller-save registers; do not take advantage of this feature.</li>
<li>Do not use rcall to call functions.</li>
</ol>
