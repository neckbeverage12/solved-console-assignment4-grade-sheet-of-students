Download Link: https://assignmentchef.com/product/solved-console-assignment4-grade-sheet-of-students
<br>
A teacher needs to determine the performance of her students. Total class strength (i.e. maximum number of students in a class) is limited to 50. Each student is given a roll number that is a 4 digit integer value ranging from 1000 – 9999. Teacher evaluates the students on 5 different exams, each having different weight-age and total marks.

Teacher needs a program that can: 1.      get input from the teacher:

<ul>

 <li>weight-age of each of 5 exams sequentially  total marks of each of 5 exams sequentially</li>

 <li>roll number and score of each student in all the 5 exams input on a single line, separated by white space. For multiple students multiple lines are input, terminating with an end of input delimiter taken as 0. If a student was absent in a specific exam then her score in the exam will also be 0. Following is a sample input showing data of 3 students:</li>

</ul>

1050 5 10 0 30 23

1042 7 11 5 19 21

1061 2 13 1 15 17

0

<ol start="2">

 <li>Compute the total score obtained by each student using the following formula:</li>

</ol>

Σ s<sub>i</sub> / t<sub>i</sub> * w<sub>i               </sub>,<sub>                      </sub>for i in the range 1 – 5,           where, i represents the exam, s represents score earned in the exam, t represents total marks of the exam, w represents weight-age of the exam

<ol start="3">

 <li>Display the mark sheet showing for each student: roll number, score obtained in each exam and the total score obtained. Mark sheet needs to be shown either in the <strong>ascending order of roll number</strong> or <strong>descending order of total score</strong>. Ask the teacher to enter the sort order as input.</li>

 <li>Allow the teacher to search for the marks details of a specific student based upon the roll number</li>

</ol>

Use <strong>parallel arrays</strong> to implement the program. Implement support for sorting and searching using <strong>Selection Sort</strong> and <strong>Binary Search</strong>.