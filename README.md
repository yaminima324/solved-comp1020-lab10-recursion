Download Link: https://assignmentchef.com/product/solved-comp1020-lab10-recursion
<br>
<ul>

 <li>Recursion</li>

</ul>

Notes:

<ul>

 <li>The three exercises in this lab are independent – they can be done in any order.</li>

 <li>Only one of the three exercises is required, but try to do as many as you can. The Silver exercise requires StdDraw.</li>

</ul>

<ol>

 <li>Start with the file <strong>java</strong>.</li>

 <li>Add a <em>recursive </em>method <strong>double largestInList(int n, double[] list)</strong> which will find the largest of the first <strong>n</strong> elements of the array of doubles <strong>list</strong>. Assume <strong>n</strong> is between 1 and <strong>length</strong>. You <em>must </em>use recursion to do this – no loop of any kind is allowed.</li>

</ol>

A fractal image is one which is made up of smaller versions of the same image. Here’s how to create a simple fractal image:

<ul>

 <li>To make a “level n” image in a square area

  <ol>

   <li>divide it into four smaller “quadrants”: the upper left, upper right, lower left, and lower right – all square areas taking up exactly ¼ of the original area each.</li>

   <li>Draw 4 lines from the center of the whole area to the centres of each of the 4 quadrants.</li>

   <li>Draw “level n-1” fractal images in each of the four quadrants, in exactly the same way.</li>

  </ol></li>

 <li>A “level 1” image is the smallest. A “level 0” image doesn’t draw anything at all.</li>

</ul>

Here are pictures of level 1-3 images:




<ol>

 <li>Start with the file <strong>java</strong>.</li>

 <li>Complete the <em>recursive </em>method <strong>void drawFractal(double xMin, double xMax, double yMin, double yMax, int nLevels)</strong> which will draw a fractal image, of level <strong>nLevels</strong>, in the rectangular area specified by the other four parameters.</li>

 <li>Run the supplied main method. You can click the mouse button in the <strong>StdDraw</strong> window to advance from one level of fractal to the next, from level 1 up to level 8.</li>

</ol>




This is a very challenging question. Good luck!

There are 11 different ways to write a sum of positive integers (greater than 0) that add up to 6, if the integers are in descending order:

6

5+1

4+2

4+1+1  3+3

3+2+1

3+1+1+1  2+2+2

2+2+1+1

2+1+1+1+1

1+1+1+1+1+1




<ol>

 <li>Start with the file <strong>java</strong>.</li>

 <li>Complete the method <strong>void printAllSums(int n)</strong> which will <em>print </em>all of the ways to write a sum of positive integers that add up to <strong>n</strong>, exactly as shown above (for <strong>n</strong>=6). This method will not be recursive itself. It should simply call the one below. (It should be a 1-line method.)</li>

 <li>Create a more general <em>recursive </em>version of <strong>printAllSums</strong>, with an extra parameter or two, which will allow the sums to be easily computed and printed. The single-parameter version above should call this one. Note that this will be a <strong><em>very</em></strong> short method, but it may be difficult to figure out how to do it. Look at the patterns in the example above and try to spot a simple recursion. Good luck.</li>

 <li>Run the supplied main program which will test your methods for <strong>n</strong>=1, 2, and 6.</li>

</ol>





