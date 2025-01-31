MSDS689 Problem Solving with Python
=======

(*Proposed to be MSDS695 Data Structures and Algorithms year 2020*)

This course give students a deeper and more general view of data structures and algorithms. While students have examined a number of data structures, such as binary trees, already, this course provides a much more in-depth study. This depth will benefit them greatly in the advanced machine learning course. This course also tends to address many of the difficult algorithm questions students get during job interviews. The critical data structures covered in this class are: lists, linked lists, trees, graphs, hash tables, and tries. The course also covers a variety of common and useful recursive and non-recursive algorithms, such as searching and sorting.

This course is part of the [MS in Data Science program at the University of San Francisco](https://www.usfca.edu/arts-sciences/graduate-programs/data-science).

# Resources

Here is a great free book on [algorithms by Jeff Erickson](http://jeffe.cs.illinois.edu/teaching/algorithms/).

I'll be pulling some material from Kleinberg and Tardos, *Algorithm Design*. US copyright law allows me to make copies of small portions of books for educational use, which I have done. Please see compressed pdf `kleinberg-common-running-times.7z` in Canvas course files area. (Do not post that material publicly.)

A very useful set of [programming-concepts-for-data-science](https://nbviewer.jupyter.org/github/shik3519/programming-concepts-for-data-science/blob/master/notebooks/03-common%20datastructures%20and%20algorithms.ipynb) by former USF MSDS student [Shikhar Gupta](https://github.com/shik3519).

[10 Steps to Solving a Programming Problem](https://codeburst.io/10-steps-to-solving-a-programming-problem-8a32d1e96d74)

# Course Learning Objectives (CLOs)

By the end of this course, students will be able to:

1. Describe object-oriented programming and use objects to construct linked lists, trees, and graph data structures
2. Implement critical algorithms, such as searching and list manipulations
3. Build hash tables
4. Create Trie data structures
5. Design recursive algorithms
6. Compare algorithmic complexity using “big-O” notation

# Administrivia

**INSTRUCTOR.** [Terence Parr](http://parrt.cs.usfca.edu). I’m a professor in the computer science and [data science program](https://www.usfca.edu/arts-sciences/graduate-programs/data-science) departments and was founding director of the MS in Analytics program at USF (which became the MS data science program).  Please call me Terence or Professor (the use of “Terry” is a capital offense).

**SPATIAL COORDINATES:**<br>

* Class is held at 101 Howard in 5th floor classroom 527.
* My office is room 607 @ 101 Howard up on mezzanine

**TEMPORAL COORDINATES.** Fri Jan 25 - Fri Mar 8, 2019

* Section 01: Fri 10-11:55AM
* Section 02: Fri 2:20-4:15PM 
* Exams: Fri 15 Feb before class 9:15am-9:55, Fri Mar 8 in class 10am for both classes at once (different room likely)

**INSTRUCTION FORMAT**. Class runs for 1:55 hours, 2 days/week. Instructor-student interaction during lecture is encouraged and we'll mix in mini-exercises / labs during class. All programming will be done in the Python 3.6 (not 3.7) programming language, unless otherwise specified.

**TARDINESS.** Please be on time for class. It is a big distraction if you come in late.

**ACADEMIC HONESTY.** You must abide by the copyright laws of the United States and academic honesty policies of USF. You may not copy code from other current or previous students. All suspicious activity will be investigated and, if warranted, passed to the Dean of Sciences for action.  Copying answers or code from other students or sources during a quiz, exam, or for a project is a violation of the university’s honor code and will be treated as such. Plagiarism consists of copying material from any source and passing off that material as your own original work. Plagiarism is plagiarism: it does not matter if the source being copied is on the Internet, from a book or textbook, or from quizzes or problem sets written up by other students. Giving code or showing code to another student is also considered a violation.

The golden rule: **You must never represent another person’s work as your own.**

If you ever have questions about what constitutes plagiarism, cheating, or academic dishonesty in my course, please feel free to ask me.

**Note:** Leaving your laptop unattended is a common means for another student to take your work. It is your responsibility to guard your work. Do not leave your printouts laying around or in the trash. *All persons with common code are likely to be considered at fault.*

## Student evaluation

| Artifact | Grade Weight | Due date |
|--------|--------|--------|
|[OO hashtable](projects/oohtable/oohtable.md)| 10% | Sun, Feb 3 11:59pm |
|[Isolation Forest](projects/iforest/iforest.md)| 40% | Sun, Mar 3 11:59pm |
|Exam 1| 20%| 9:15AM-9:55AM Fri Feb 15 |
|Exam 2| 30%| 10AM-11:00AM Fri Mar 8 |

All projects will be graded with the specific input or tests given in the project description, so you understand precisely what is expected of your program. Consequently, projects will be graded in binary fashion: They either work or they do not. The only exception is when your program does not run on the grader's or my machine because of some cross-platform issue. This is typically because a student has hardcoded some file name or directory into their program. In that case, we will take off *a minimum* of 10% instead of giving you a 0, depending on the severity of the mistake. Please go to github and verify that the website has the proper files for your solution. That is what I will download for testing.

Each project has a hard deadline and only those projects working correctly before the deadline get credit.  My grading script pulls from github at the deadline.  *All projects are due at the start of class on the day indicated, unless otherwise specified.*

**Grading standards**. I consider an **A** grade to be above and beyond what most students have achieved. A **B** grade is an average grade for a student or what you could call "competence" in a business setting. A **C** grade means that you either did not or could not put forth the effort to achieve competence. Below **C** implies you did very little work or had great difficulty with the class compared to other students.

# Syllabus

* Review hash table construction, discuss OO htable project
* Review [OO notebook](https://github.com/parrt/msds501/blob/master/notes/OO.ipynb) and [Operator overloading notebook](notes/operator-overloading.ipynb)
* [Problem-solving](notes/problem-solving.md)
* Do "quizzes" called Pairs  and OO programming on Canvas
* [Core data structures](notes/core-data-structures.pdf)
* [Introduction to algorithm complexity](notes/complexity.pdf) (“Big-O” notation); see [Measuring execution time notebook](notes/execution-time.ipynb)
* Do complexity practice quiz
* [Anomaly detection with isolation forests](notes/isolation-forests.pdf)
* [Getting a grip on recursion](notes/recursion.pdf); see [recursion notebook](https://github.com/parrt/msds689/blob/master/notes/recursion-notebook.ipynb)
* [Walking data structures](notes/walking-structures.pdf); see [walking notebook](https://github.com/parrt/msds689/blob/master/notes/walking.ipynb)
* [Regression tree stumps notebook](https://github.com/parrt/msds689/blob/master/notes/stumps.ipynb)
* [Sorting](notes/sorting.pdf); see [Sorting notebook](https://github.com/parrt/msds689/blob/master/notes/sorting.ipynb)
* [Searching](notes/searching.pdf); see [Searching notebook](https://github.com/parrt/msds689/blob/master/notes/searching.ipynb)
* [Graphs](notes/graphs.pdf); see [Graphs notebook](https://github.com/parrt/msds689/blob/master/notes/graphs.ipynb)

The use of recursive algorithms will be emphasized frequently and wherever appropriate to reinforce this critical mechanism. Discussion of formal algorithm complexity will also be emphasized throughout the lectures.

**USF policies and legal declarations**

*Students with Disabilities*

If you are a student with a disability or disabling condition, or if you think you may have a disability, please contact <a href="/sds">USF Student Disability Services</a> (SDS) for information about accommodations.

*Behavioral Expectations*

All students are expected to behave in accordance with the <a href="/fogcutter">Student Conduct Code</a> and other University policies.

*Academic Integrity*

USF upholds the standards of honesty and integrity from all members of the academic community. All students are expected to know and adhere to the University's <a href="/academic-integrity/">Honor Code</a>.

*Counseling and Psychological Services (CAPS)*

CAPS provides confidential, free <a href="/student-health-safety/caps">counseling</a> to student members of our community.

*Confidentiality, Mandatory Reporting, and Sexual Assault*

For information and resources regarding sexual misconduct or assault visit the <a href="/TITLE-IX">Title IX</a> coordinator or USFs <a href="http://usfca.callistocampus.org" target="_blank">Callisto website</a>.
