Download Link: https://assignmentchef.com/product/solved-csci203-lab3-virtual-initialization
<br>
For this exercise you are to implement a virtually initialized array and test it for correctness.

As usual, your program will prompt for the name of an input file and the read and process the data contained in this file.

You will use three integer arrays, <strong>data[]</strong>, <strong>forward[]</strong> and <strong>backward[]</strong> each containing 100 elements.

Your test data will consist of a file containing two parts:

<ol>

 <li>A sequence of pairs: <strong>what</strong>,<strong> where</strong>. You are to store the value <strong>what</strong> in location <strong>where</strong> of the <strong>data</strong> array using virtual initialization. I.e. <strong>data[where] = what</strong>.</li>

 <li>This sequence is terminated by the pair <strong>‐1 ‐1</strong></li>

 <li>This is followed by a sequence of single integer values, <strong>probe</strong>. For each such value you are to test whether <strong>data[probe]</strong> has been initialized and print one of the following two messages: Position <strong>probe</strong> has not been initialized.</li>

</ol>

Position <strong>probe</strong> has been initialized to value <strong>data[probe]</strong>.

<ol start="4">

 <li>This sequence is terminated by the value <strong>‐1</strong></li>

</ol>

A sample input file might contain:




<strong>42 7 </strong>

<strong>93 9 </strong>

<strong>11 4 </strong>

<strong>‐1 ‐1 </strong>

<strong>7 </strong>

<strong>8 </strong>

<strong>9 </strong>

<strong>‐1 </strong>

<strong> </strong>

For which the output would be:




<strong>Position 7 has been initialized to value 42. </strong>

<strong>Position 8 has not been initialized. </strong>

<strong>Position 9 has been initialized to value 93. </strong>

As usual, do not use classes or STL

When you are finished, test your program using the provided text file named “Ex3.txt” and show your code and the output to your lab tutor to receive your mark. Also, submit your file via unix (banshee) using the submit command below.

<strong>$ submit -u <em>login </em>-c CSCI203 –a ex3 <em>filename </em></strong>

where ‘<strong><em>login</em></strong>‘ is your UNIX login ID and ‘<strong><em>filename</em></strong>’ is the name of your file.

If you are unable to attend your lab class and demonstrate your work on time due to circumstances beyond your control (e.g. sickness), contact the coordinator (Ian or Koren) to request an extension.


