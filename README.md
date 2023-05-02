Download Link: https://assignmentchef.com/product/solved-comp2560-lab-6-exec
<br>
Write a C program called <em>executebash.c</em>. It prints out on the screen

EXAM! EXAM! EXAM!

and then forks a child to execute a bash script named <em>mybash</em>. This <em>mybash</em> program prints out on the screen

STUDY! STUDY! STUDY!

Part II

Write a C program to execute multiple Unix commands in parallel.

<ul>

 <li>The number of Unix commands is not fixed.</li>

 <li>There is no communication among the Unix commands.</li>

 <li>The Unix commands are given as command line arguments.</li>

 <li>For simplicity, you can assume that each Unix command has exactly one argument except that the last one can have either no argument or one argument.</li>

</ul>

For example,

&gt;&gt;&gt;&gt;&gt; miniminishell cat openfile.c ls –l ps

includes three Unix commands: <em>cat</em> with one argument <em>openfile.c</em>, <em>ls</em> with one argument <em>–l</em>, and <em>ps</em> with no argument.

For each Unix command, use a separate process to execute it. You need to print out each process id.











