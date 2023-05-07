Download Link: https://assignmentchef.com/product/solved-ism3255-asg06
<br>
In this assignment, you will modify you two classes from ASG04: MainClass and Course

The Course class should have:

<ol>

 <li>Attributes that can be read and written: (Use Shortened get and set)

  <ul>

   <li><u>Description</u> (text) // course name</li>

   <li><u>Period</u> (integer)</li>

   <li><u>Credits</u> (integer)</li>

   <li><u>MaxEnrollment</u> (integer) with the default value 30.</li>

  </ul></li>

 <li>Attributes that are read-only:

  <ul>

   <li><u>Id</u> (text)a</li>

   <li><u>Section</u> (integer)</li>

  </ul></li>

 <li>A DEFAULT CONSTRUCTOR where <u>MaxEnrollment</u> is set to 30.</li>

 <li>A parameterized CONSTRUCTOR that takes parameters for <u>Id</u>, <u>Section</u>, <u>Description</u>, <u>Period</u>, <u>Credits</u>, and <u>MaxEnrollment</u> and initializes the attributes to those parameters (USE CONSTRUCTORS)</li>

 <li>Your parameterized Constructor should verify that <u>MaxEnrollment</u> is not greater than 30. If the input for <u>MaxEnrollment</u> is greater than 30, it should be automatically set to the default of 30.

  <ul>

   <li>Hint: Check the “Car” example. You just need a simple if condition inside your parameterized constructor.</li>

  </ul></li>

 <li>A method called <u>PrintCourseInfo</u> which will print out information about the course in the following format:</li>

</ol>

Business Systems 2 (Course ID: ISM3255, Section: 5555)

Period: 2

Credits: 2

Maximum Enrollment: 30

Once you have designed your course class, write a MainClass with a main method. Your main method should:

<ol>

 <li>Instantiate a course objects (<u>course1)</u> with input from user (ReadLine for each attribute)

  <ul>

   <li>Hint: Test your code with hardcoded values first, so that you don’t have to enter values every time you test your code.</li>

   <li>Hint: Test your parameterized constructor by entering a value greater than 30 for <u>MaxEnrollment</u></li>

  </ul></li>

 <li>Print out course1 attributes using the <u>PrintCourseInfo</u> method you created</li>

</ol>

<h3><u>Instructions for Submission</u></h3>

<h3><u> </u></h3>

<h3>1.      Your code should start with these two lines:</h3>

<h3>a.       //Group Number: &lt;your group number&gt;</h3>

<h3>b.      //PRESENT Members &lt;members working on this assignment&gt;</h3>

<h3>2.      Submit both classes that you created as attachments using the E-Learning Assignment tool.</h3>


