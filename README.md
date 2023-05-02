Download Link: https://assignmentchef.com/product/solved-comp6651-programming-assignment-2
<br>
<h2>1      Problem</h2>

You are given an array of <em>N </em>elements which are initialized to 0. You are given a sequence of <em>M </em>operations of the sort (<em>p,q,r</em>). The operation (<em>p,q,r</em>) signifies that the integer <em>r </em>should be added to all array elements <em>A</em>[<em>p</em>]<em>,A</em>[<em>p </em>+ 1]<em>,…,A</em>[<em>q</em>]. You are to output the maximum element in the array that would result from performing all <em>M </em>operations. There is a naive solution that simply performs all operations and then returns the maximum value, that takes <em>O</em>(<em>MN</em>) time. We are looking for a more efficient algorithm.

<h2>2      Input</h2>

The first line will have two integers <em>N </em>and <em>M </em>separated by a space. The next <em>M </em>lines each have 3 integers separated by spaces. The input can be assumed to obey the following constraints:

3 ≤ <em>N </em>≤ 10<sup>7</sup>

1 ≤ <em>M </em>≤ 2 ∗ 10<sup>5</sup>

1 ≤ <em>p </em>≤ <em>q </em>≤ <em>N</em>

0 ≤ <em>r </em>≤ 10<sup>9</sup>

<strong>3      Output</strong>

The output should be a single line containing the required maximum value.

<h2>4      Example</h2>

Sample Input

6 3

1 3 200 2 5 50

3 6 100

Sample Output

350

Explanation

The array has 6 elements initialized to 0, and there will be 3 operations.

After the first operation, the array would be [200<em>,</em>200<em>,</em>200<em>,</em>0<em>,</em>0<em>,</em>0].

After the second operation, the array would be [200<em>,</em>250<em>,</em>250<em>,</em>50<em>,</em>50<em>,</em>0].

After the third operation, the array would be [200<em>,</em>250<em>,</em>350<em>,</em>150<em>,</em>150<em>,</em>100]. So the required answer is the maximum value in the array, which is 350.

<h2>5      Requirements</h2>

For the constraints given above, your program should run in 1 second. You must submit source code for a program written in C/C++/Java on the Electronic Assignment System. Some test cases will be provided on the course website. You can verify if your program works on the test cases before submitting.


