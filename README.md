Download Link: https://assignmentchef.com/product/solved-cpe212-project-01
<br>
<h3>Project01 Goals</h3>

The purpose of this project is to exercise, and revisit topics introduced in CPE211.  We will be going through and implementing various functions in this assignment needed to accomplish our task.




<h3>Project01 Description</h3>

For this project, you will complete the provided partial C++ program by implementing 4 functions to perform simple image processing operations on images stored as 15×15, two dimensional arrays of integers.  The image processing operations are:




<ul>

 <li>Load Image</li>

 <li>Flip Image 3) Transpose</li>

</ul>

4) Rotate Image




The rotate image functions will be given a direction of clockwise or counter clockwise, while the flip image will be given a direction of vertical or horizontal.  You will implement these functions in the project01.cpp file.  Prototypes for these functions have already been provide in the project01.hpp file.




The main() function has already been implemented for you so that you have a common way to test your code.  The main() function will scan your input file and execute it appropriately.  All program output is performed by the code in main.cpp.  <strong>DO NOT INCLUDE ANY OUTPUT STATEMENTS IN YOUR project01.cpp FILE.  </strong>

<strong> </strong>

Hint: Make your output match the provided solution.

<strong><u>Running the Sample Solution on </u></strong><strong><u>blackhawk</u></strong>

<strong><em>The best description of what your code should do is the Sample Solution for the project.   </em></strong>

Run the sample solution by typing the following at <strong>blackhawk</strong> terminal window command prompt

<strong>/home/facstaff/taf0004/CPE212SP20/Project01/project01   imagefilename </strong>where <strong>imagefilename</strong> is the name of one of the provided input files (for example, <strong><em>p01input1.txt</em></strong>).  <strong><em>Your current working directory must contain the input files for this to work.</em></strong>

<strong><u>Unzipping Sample Input Files on </u></strong><strong><u>blackhawk</u></strong>

Use the Firefox browser to access Angel and download <strong>main.cpp</strong> and the sample input files into your <strong>Project01</strong> directory.  At terminal window prompt, use the <strong><em>unzip</em></strong> utility to uncompress the files.




For example:  <strong>unzip  NameOfZipFileHere</strong> to unzip the files into your current directory.

Since this project is worth <strong>ten points</strong>, you have been given five input files (which utilize the three image files) to test your program.  <strong> </strong>

<strong><u>Running the Preview Script on </u></strong><strong><u>blackhawk</u></strong>

Run the preview script by typing the following in a <strong>blackhawk</strong> terminal window command prompt

<h2><u>/home/facstaff/taf0004/CPE212SP20/Project01/preview01.bash </u></h2>

<strong>This script will run both the </strong><strong>Sample Solution</strong><strong> AND </strong><strong>your project01</strong><strong> executable program on the complete set of input files, and it compares the outputs of the two programs line by line to identify errors in your program’s outputs.  Make sure that the output of your program exactly matches the output of the Sample Solution. </strong>







<h1>Project01 Compilation Instructions</h1>

This project consists of two C++ files and one header: main.cpp, project01.cpp and project01.hpp.  All three have been provided, along with a makefile to help you compile your program.  A makefile contains the sequence of commands required to compile and assemble (link) your executable program.  The provided file works on <strong>Blackhawk</strong>.  For this assignment, you will need to use the following command line command to build your program




make




which will create an executable named project01 from the provided files.  If your program compiles successfully, you can then type:

./project01 NameOfInput.txt

To execute the program assuming that the input file is located in the same directory.  Example:




./project01 p01input1.txt




<h1>Project 01 Specifications</h1>













<h1>Project01 Sample (15×15) image file</h1>










<strong>        </strong>

<h1>Important Project01 Submission Instructions</h1>

You are provided the main() function within the main.cpp file.  This is where all the test files will be ran to test your code.  Through the program’s execution, it will run various functions that you will implement within the project01.cpp file.  <strong>YOU WILL ONLY SUBMIT THIS PROJECT01.CPP FILE TO CANVAS. </strong>




<strong><u>THE FOLLOWING ARE VERY IMPORTANT INSTRUCTIONS:</u></strong>

<em>1)</em> <em>Do not modify the </em><em>main.cpp </em><em>file</em>

<em>Modifying the </em><em>main.cpp </em><em>file will result in </em><strong><em>zero credit</em></strong> <em>(</em><em>0 points</em><em>) on this assignment </em><em>2)</em> <em>Do not modify the header file </em><em>project01.hpp</em><em>.</em><em>  </em>

<em>Modifying the </em><em>project01.hpp  </em><em>file will result in </em><strong><em>zero credit</em></strong> <em>(</em><em>0 points</em><em>) on this assignment </em><em>3)</em> <em>All of your work must be done within the </em><em>project01.cpp </em><em>file.  </em><em>  </em>

<ul>

 <li><em>All output is done in the </em><em>cpp </em><em>file. Adding your own outputs to </em><em>project01.cpp </em><em>will result in </em><strong><em>zero credit</em></strong> <em>(</em><em>0 points</em><em>).</em></li>

 <li><em>Do not include the statement </em><em>using namespace std; </em><em>in your code. Any time you reference an item from the standard library, you should use </em><em>std::name</em><em>.  Example, if you need to declare a string, you should declare it as </em><em>std::string myString;</em></li>

 <li><strong><em>ONLY SUBMIT THE </em></strong><strong><em>cpp</em></strong><strong><em> FILE. DO NOT SUBMIT ANY OTHER FILES WITH YOUR SUBMISSION. </em></strong></li>

</ul>