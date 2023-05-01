Download Link: https://assignmentchef.com/product/solved-embsys100-module-6-pass-by-value-nature-of-c
<br>
The goals for the assignment this week:

<ol>

 <li>To gain in depth understanding of the pass-by-value nature of C.</li>

 <li>To gain hands on experience with the ARM Cortex-M4 assembly language.</li>

</ol>

Problems:

<ol>

 <li>Create a function that allows swapping of two pointers.

  <ol>

   <li>Explain what the “main” function does to the CSTACK in order setup the input arguments prior to calling the swap_pointer() function?</li>

   <li>And what are the values in R0 &amp; R1 when swap_pointer() is called?</li>

   <li>Share a screen shot of the local variables inside of “main” after the function swap_pointer() returns, showing the values of the pointers and what they are pointing to, similar to the picture below:</li>

  </ol></li>

</ol>

<ol start="2">

 <li>Run <strong>sqrAsm</strong> code from the class demo:

  <ol>

   <li>Copy <a href="https://canvas.uw.edu/courses/1325909/files/folder/EMBSYS%20100%2019/Code?preview=58709707">HelloWorld</a> from Assignment 1.</li>

   <li>Download the file <a href="https://canvas.uw.edu/courses/1325909/files/folder/EMBSYS%20100%2019/Code?preview=59879636">s</a> and copy it to the project directory.</li>

   <li>In IAR, add sqrAsm.s file to your project. Now you should be able to see the file from the Workspace Window.</li>

   <li>Modify main.c to call sqrAsm function.</li>

   <li>Run your program on the board, and capture a snapshot image of the output from TeraTerm.</li>

  </ol></li>

 <li>Create a new file <strong>s</strong> and add the file to the same HelloWorld project above.

  <ol>

   <li>Write the assembly code to take an input argument, divide it by 2, and return the result.</li>

   <li>Invoke the function “PrintString” from within divAsm before doing the division computation.</li>

   <li>Add a comment for every statement in your assembly function code.</li>

   <li>In the main.c, invoke dev2Asm(foo) and capture the screen output from TeraTerm.</li>

  </ol></li>

</ol>

<ol start="4">

 <li>Implement a swap function in assembly and call it “<strong>swapCharsAsm</strong>”:

  <ol>

   <li>It takes as input two variables of char data type and swaps the two chars</li>

   <li>Add a comment for every statement in your assembly function code.</li>

   <li><strong><u>Bonus:</u> </strong>Returns 0 if the two chars are identical; otherwise, return 1.</li>

  </ol></li>

</ol>

<ol start="5">

 <li><strong><u>Bonus:</u></strong> Implement the swap_pointer() function from #1 above in assembly and call it <strong>swapPointersAsm</strong>().

  <ol>

   <li>Add a comment for every statement in your assembly function code.</li>

   <li>Take a snap shot of the output after invoking the swapPointerAsm() subroutine.</li>

  </ol></li>

</ol>