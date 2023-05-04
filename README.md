Download Link: https://assignmentchef.com/product/solved-cs4000-homework-1
<br>
<ol>

 <li>(10 pts.) Implement a “hello-world” program using OpenMP. Your program should create as many threads as their are processors/cores on your current machine. From each thread that you create, your program should print:</li>

</ol>

Hello from thread i.

This is &lt;Your Name&gt;’s first parallel program

There are currently n threads running

Implement your program so that the text given above is printed in one block for each thread.

<ol start="2">

 <li>(10 pts.) Consider the following problem. Given an <em><sub>n</sub></em>×<em><sub>n </sub></em>matrix of numbers, an integer <em>m</em>, and a modulus <em><sub>q</sub></em>, find the largest product of <em><sub>m </sub></em>modulo <em><sub>q </sub></em>numbers in a row, either vertically, horizontally, or diagonally. Write a program that outputs the value of the largest product on a line by itself. For example, consider the following 5 ×5 matrix of values with the value <em><sub>m </sub></em>= 4 and <em><sub>q </sub></em>= 1000000 :</li>

</ol>

10 1 1 1 1

1 10 11 12 13 1 1 10 11 12

1 1 1 10 1

1 1 1   1 10

Your program should produce the answer “17160” (10 × 11 × 12 × 13). When <em><sub>m </sub></em>= 5, your program should answer “100000”

Implement your program in C++ and provide adequate documentation. Test input/output examples will be provided to help you debug your code.

<ol start="3">

 <li>(20 pts.) Use OpenMP to implement a parallel version of the program that you implemented in problem #2. Implement your program using #pragma omp parallel.</li>

</ol>

Compare your program’s running time to your original program. Your program should be at least 75% efficient on a four core machine on put of a 1000 x 1000 array with <em>m </em>= 500.

Implement your program in C++ and provide adequate documentation.