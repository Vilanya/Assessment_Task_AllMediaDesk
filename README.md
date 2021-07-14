# Assessment_Task_AllMediaDesk

This repository contains the solutions to the following tasks. 

**Part 1 **
Develop a term calculator that can handle (), *, /, +, and -. For example, if the user enters the term (5 + 8) * 3/8 +3, the term calculator shall calculate and output the result according to the school rules of term calculations.
These rules are: () before * and /, * and / before + and -. Several * and / are calculated from left to right, several + and - also from left to right.
Important: The actual algorithm must be implemented itself. The use of functions like eval in JavaScript are not permitted.

**Part 2 **
Peter likes numbers. As a meditation exercise, he likes to write down all the numbers starting with 1 whose digits are sorted in ascending order. For example, 11235888 is such a number. After a while, he stops.
Write an efficiently designed program which, after entering a number between 1 and 10 ^ 18, represents the last number checked by Peter, outputs the last number written down by Peter.
 Examples: Input: 23245 Input: 11235888 Input: 111110 Input: 33245
Output: 22999 Output: 11235888 Output: 99999 Output: 29999
 Tip: Going through the numbers one by one and testing them is not efficient enough.

**Part 3, based on Part 1 **
Allow the term calculator to accept lines in the form y = <TERM> with x as an additional possible character in the term. If such a complete equation is given, you display a simple x / y graph. For each value on the x axis, calculate y and plot the point (a continuous line is even better).
