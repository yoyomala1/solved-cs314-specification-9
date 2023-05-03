Download Link: https://assignmentchef.com/product/solved-cs314-specification-9
<br>
<p dir="ltr" align="left"><b>Programming Assignment 9: </b>Individual Assignment. You must complete this assignment on your own. You may not acquire from any source (e.g.  another student or an internet site) a partial or complete solution to a problem or project that has been assigned. You may <b>not</b> show another student your solution to an assignment. You <b>may not</b> have another person (current student, former student, tutor, friend, anyone) “walk you through” how to solve an assignment. You may get help from the instructional staff. You may discuss general ideas and approaches with other students but you may not develop code together. Review the <a href="https://www.cs.utexas.edu/~scottm/cs314/syllabus.htm#Collaboration" target="_blank" rel="nofollow noopener" data-saferedirecturl="https://www.google.com/url?q=https://www.cs.utexas.edu/~scottm/cs314/syllabus.htm%23Collaboration&amp;source=gmail&amp;ust=1618940014563000&amp;usg=AFQjCNF6Oox_babrxxlANEhjX2K3cZOTfA">class policy on collaboration from the syllabus</a>.

<ul>

 <li>Placed online: Wednesday, April 7</li>

 <li>20 points, ~2% of final grade.</li>

 <li>Due: no later than 11 pm, Thursday, April 22 (<strong>The week after exam 2</strong>.)</li>

 <li><a href="https://www.cs.utexas.edu/~scottm/cs314/Assignments/index.htm" target="_blank" rel="nofollow noopener" data-saferedirecturl="https://www.google.com/url?q=https://www.cs.utexas.edu/~scottm/cs314/Assignments/index.htm&amp;source=gmail&amp;ust=1618940014563000&amp;usg=AFQjCNEeOOyCBc1poRxbOz8VZqp9Wl58mQ">General Assignment Requirements</a></li>

</ul>

<p align="left">The purposes of this assignment are:

<ol>

 <li>implement a binary search tree</li>

 <li>observe the behavior of binary search trees when adding data in no particular order and data already in sorted order</li>

</ol>

<hr>

<p dir="ltr"><b>Description: </b>Implement a binary search tree class. Make the data structure generic using Java’s generics and parameterized data types. You are free to use the code we developed together in lecture, just put a comment stating the code came from lecture. If you did not attend lecture or take notes notes during lecture, you shall develop the code on your own. I expect you to use the simple insertion algorithm we developed in class. <strong>Like assignment 1, you may not look up algorithms, in this case for balanced binary search trees. </strong><b>You may not use the TreeSet or TreeMap classes from the Java standard library</b> when implementing your Binary Search Tree. You will use the Java TreeSet class in some experiments.

<b>Provided Files:</b>

<table border="2" width="100%" cellspacing="6" cellpadding="6">

 <tbody>

  <tr>

   <td align="right" valign="top" width="15%" height="19"></td>

   <td width="50%" height="19">File</td>

   <td width="50%" height="19">Responsibility</td>

  </tr>

  <tr>

   <td align="right" width="15%" height="38">Source Code</td>

   <td width="50%" height="38"><a href="https://www.cs.utexas.edu/~scottm/cs307/javacode/utilities/Stopwatch.java" target="_blank" rel="nofollow noopener" data-saferedirecturl="https://www.google.com/url?q=https://www.cs.utexas.edu/~scottm/cs307/javacode/utilities/Stopwatch.java&amp;source=gmail&amp;ust=1618940014563000&amp;usg=AFQjCNEU4SEOxW8Yz54IN59MvzSRp473DQ">Stopwatch.java</a>. Used to record times of experiments in questions.java.</td>

   <td width="50%" height="38">Provided by me. Do not alter.</td>

  </tr>

  <tr>

   <td align="right" width="15%" height="19">Implementation</td>

   <td width="50%" height="19"><a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A9_BinarySearchTrees/BinarySearchTree.java" target="_blank" rel="nofollow noopener" data-saferedirecturl="https://www.google.com/url?q=https://www.cs.utexas.edu/~scottm/cs314/javacode/A9_BinarySearchTrees/BinarySearchTree.java&amp;source=gmail&amp;ust=1618940014563000&amp;usg=AFQjCNHtUvcVX1lpyRql2aAJTlozRs-nEQ">BinarySearchTree.java </a>An implementation of a binary search tree.</td>

   <td width="50%" height="19">Provided by you and me. Mostly you.</td>

  </tr>

  <tr>

   <td align="right" width="15%" height="38">Documentation</td>

   <td width="50%" height="38"><a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A9_BinarySearchTrees/BinarySearchTree.html" target="_blank" rel="nofollow noopener" data-saferedirecturl="https://www.google.com/url?q=https://www.cs.utexas.edu/~scottm/cs314/javacode/A9_BinarySearchTrees/BinarySearchTree.html&amp;source=gmail&amp;ust=1618940014563000&amp;usg=AFQjCNEkK7IVV9i8Y1tyRwGZIRCyxkrd9A">Javadoc for the BinarySearchTree class.</a></td>

   <td width="50%" height="38">Provided by me.</td>

  </tr>

  <tr>

   <td align="right" width="15%" height="57">Test code</td>

   <td width="50%" height="57"><a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A9_BinarySearchTrees/BSTTester.java" target="_blank" rel="nofollow noopener" data-saferedirecturl="https://www.google.com/url?q=https://www.cs.utexas.edu/~scottm/cs314/javacode/A9_BinarySearchTrees/BSTTester.java&amp;source=gmail&amp;ust=1618940014563000&amp;usg=AFQjCNEg7z17QjgFq-fTwXneBTuZlQHLoQ">BSTTester.java</a> contains several tests for the BinarySearchTree class. You must ensure the tests are correct and your class must pass these tests. Delete the original tests. Add at least 2 more tests per method.</td>

   <td width="50%" height="57">Provided by you and me.</td>

  </tr>

  <tr>

   <td align="right" width="15%" height="15">Reflection</td>

   <td width="50%" height="15"><a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A9_BinarySearchTrees/questions.txt" target="_blank" rel="nofollow noopener" data-saferedirecturl="https://www.google.com/url?q=https://www.cs.utexas.edu/~scottm/cs314/javacode/A9_BinarySearchTrees/questions.txt&amp;source=gmail&amp;ust=1618940014563000&amp;usg=AFQjCNG5NiWAJI34ZUFp8lIaIzAayxZfoQ">questions.txt </a>Place your answers to these questions in a comment at the top of your BSTTester.java file.</td>

   <td width="50%" height="15">Provided by me.</td>

  </tr>

  <tr>

   <td align="right" width="15%" height="15">All Files</td>

   <td width="50%" height="15"><a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A9_BinarySearchTrees/BST_All.zip" target="_blank" rel="nofollow noopener" data-saferedirecturl="https://www.google.com/url?q=https://www.cs.utexas.edu/~scottm/cs314/javacode/A9_BinarySearchTrees/BST_All.zip&amp;source=gmail&amp;ust=1618940014563000&amp;usg=AFQjCNGQgYpyLGwzJlR4NilmwQw5QFPRRA">All files in one zip.</a></td>

   <td width="50%" height="15">Provided by me.</td>

  </tr>

 </tbody>

</table>

<b>BinarySearchTree.java</b> is class that implements a binary search tree as discussed in lecture. It is acceptable to use the naive insertion and removal algorithms. I have specified the methods for the class. Complete the implementation under the constraints of the<a href="https://www.cs.utexas.edu/~scottm/cs314/Assignments/index.htm" target="_blank" rel="nofollow noopener" data-saferedirecturl="https://www.google.com/url?q=https://www.cs.utexas.edu/~scottm/cs314/Assignments/index.htm&amp;source=gmail&amp;ust=1618940014563000&amp;usg=AFQjCNEeOOyCBc1poRxbOz8VZqp9Wl58mQ"> general requirements</a>. <b>There is a method named printTree which prints out a representation of the current tree. It is a horizontal representation. This method is already done and can be useful in debugging. Read the documentation for details.</b>

<b>BinarySearchTree.BSTNode</b>. This is a class nested inside the BinarySearchTree class. Use instances of this class to store the data in the binary search tree. This is very similar to the BSTNode class presented in class, but now we are nesting it inside the BinarySearchTree class. This allows you to access the instance variables of a BSTNode object directly.

<b>BSTTester.java</b> contains several tests for the BinarySearchTree class. After you are sure the original tests are correct and that your class passes them, delete the original tests. Add at least 2 tests per method in the BinarySearchTree class.

questions.txt contains a number of questions to and experiments regarding your completed BinarySearchTree class. Place your answers in a comment at the <u><b>top</b></u> of your BSTTester class.

<b>Note:</b> The <code>get(int kth)</code>, <code>getAllLessThan(E val)</code>, and <code>getAllGreaterThan(E val)</code> methods shall be as efficient as possible in terms of time and space. Meaning make the T(N) as small as possible. You could use the <code>getAll</code> method but you will very likely fail some stress tests if you take that approach. You must stop your search or processing as soon as you can. Don’t do any extra work.

<hr>

<b>Submission: </b>Complete the header in the BinarySearchTree and BSTTester classes.  Replace &lt;NAME&gt; with your name. Note, you are stating, <u>on your honor</u>, that you did the assignment on your own.

Create a zip file name a9.zip with your BinarySearchTree.java and BSTTester.java files. The zip file must <b>not</b> contain any directory structure, just the required file.

<a href="https://www.cs.utexas.edu/~scottm/cs314/handouts/creating_a_zip_file_via_eclipse.htm" target="_blank" rel="nofollow noopener" data-saferedirecturl="https://www.google.com/url?q=https://www.cs.utexas.edu/~scottm/cs314/handouts/creating_a_zip_file_via_eclipse.htm&amp;source=gmail&amp;ust=1618940014563000&amp;usg=AFQjCNHpWoFsV_zogmmunvI7k8O1zv0FQw">See this page for instructions on how to create a zip via Eclipse. </a>

<p align="left">Turn in a9.zip <a href="https://guides.instructure.com/m/4212/l/41972-how-do-i-submit-an-online-assignment" target="_blank" rel="nofollow noopener" data-saferedirecturl="https://www.google.com/url?q=https://guides.instructure.com/m/4212/l/41972-how-do-i-submit-an-online-assignment&amp;source=gmail&amp;ust=1618940014563000&amp;usg=AFQjCNHBSaKgMoTPezm0VosIuy0j2yzEGw">via your Canvas account</a> to programming assignment 9.

<ul>

 <li><p align="left">Ensure you files are named BinarySearchTree.java and BSTTester.java.. Failure to do so will result in points off.</li>

 <li><p align="left">Ensure BinarySearchTree.java and BSTTester.java are part of the default package. Do not add a <code>package</code> statement to either file.</li>

 <li><p align="left">Ensure your zip has no internal directory structure. When the file is unzipped no directories (folders) are created. (Note, the built in unzip feature of some versions of Windows and Apple OS X “help” by adding a directory when you unzip with the same name as the file. The unzip we use on the CS Linux system does not do this. Neither do unzip programs such as 7zip.)</li>

 <li><p align="left">Ensure you submit the assignment under Programming Assignment 9 in Canvas.</li>

 <li><p dir="ltr" align="left">We will compile and run our tester harness on the CS department Linux machines. To ensure you have no problems (strange imports, package statements) I suggest you move your files to a directory on your CS department account and compile and run them from the command line.</li>

</ul>