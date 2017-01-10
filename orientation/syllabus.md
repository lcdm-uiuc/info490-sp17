# INFO 490: Advanced Data Science #

> ### [Confusion is the Sweat of Learning][https://www.wired.com/2013/10/telling-you-the-answer-isnt-the-answer/] -Rhett Alain

**INFO 490: Advanced Data Science** explores advanced concepts in data science by employing a practical approach, including machine learning; probabilistic programming; text, network, and graph analysis; and cloud computing.

***Professor:*** Dr. Robert J. Brunner

***Course Administrator:*** Edward J. Kim

***Teaching Assistants:***  
- Xinyang Lu
- Fizza Mughal
- Samantha Thrush

***Course Assistants:*** 
- Drake Eidukas
- Taeyoung Kim

For contact information see the course [moodle site](https://learn.illinois.edu/course/view.php?id=20247).

-----

## Course Goals ##

Upon completion of this course, students will be expected to understand advanced data science concepts. Students will learn the practical aspects of applying machine and statistical learning in a variety of contexts, as well as different aspects of cloud computing. Specific concepts that will be covered including supervised and unsupervised learning, dimensional reduction, clustering, probabilistic programming, text mining, graph analysis, network analysis, Hadoop, NoSQL data stores, Spark, and streaming data analysis.

## Prerequisites ##

As a pre-requisite for this course, you must have mastered the material in *INFO 490: Foundations of Data Science*. Generally, this is demonstrated by having taken this previous course. However, instructor approval can also be granted for those who can demonstrate proficiency in the required topics.

Note: At present, we are using the CS department's cluster to run the course [JupyterHub server](https://info490rb.studentspace.cs.illinois.edu). Each student is running a Dockerized version of the course software stack. This provides many advantages including robustness against crashes, simplicity of deploying software updates, reduced requirements for students (simply a modern web browser, we have used tablets and smart phones), and simplifying assignment submission. You can also run a Docker container locally, as in previous courses, but this approach is not recommended. In addition, if you work locally, since assignments are collected from your cloud-based Docker container after you have submitted them, you must ensure that you push local changes to your course cloud Docker container prior to the deadline.

As part of the orientation week activities, we have provided a demo [IPython Notebook](notebooks/intro2ip.ipynb) that you should use to get familiar with working in an IPython Notebook on the course JupyterHub server. Each week there will be an `index.ipynb` IPython Notebook that will give you access to the different course notebooks for that week, please use these on the course server to move through the course material.

## Texts ##

There are no required textbooks for this course. Instead, we will utilize Internet accessible websites, videos, and documentation as supplemental material to the lesson content. We also will include links, as relevant, to readings from books that are freely available to University of Illinois students, staff and faculty via the University's Safari subscription.

## Academic Integrity ##

Academic honesty is essential to this course and the University. Any instance of academic dishonesty (including but not limited to cheating, plagiarism, falsification of data, and alteration of grades) will be documented in the student's academic file. In addition, **at a minimum** the particular assessment, quiz, or assignment will be given a zero. Serious or repeated offenses may be punished more severely.

**Guidelines for collaborative work**: Discussing course material with your classmates is in general a good idea, but each student is expected to do his or her own work. On assignments, you may discuss the problems and concepts behind them, but you are responsible for your own answers. Please do not post code in the forums! Finally, on assessments and quizzes, your answers must of course be your own. For further info, see the [Student Code, Part 4. Academic Integrity](http://studentcode.illinois.edu/article1_part4_1-401.html).

**Automatic Plagiarism Detection**
This semester we will employ an automatic plagiarism detection tool on each assignment. This tool easily identifies submissions that are more similar than would be randomly expected. Each week the instructional staff will review the output from this tool, and as necessary formally identify students who we believe are guilty of cheating. At a minimum, the following policy will be enforced:

- **First** Offense: Warning.
- **Second** Offense: Zero on affected assignment.
- **Third** Offense: Final grade reduced by one letter grade and a notification sent to home unit.
- **Fourth** Offense: Automatic **F** in course and a notification sent to the Dean of Students.

Furthermore, each argument about the enforcement of this policy that is deemed frivolous by the instructional staff will result in ten percent reduction in the affected assignment score.

## Communication ##

The instructional staff will use the [Announcement Forum][af] on the course Moodle to communicate important course information. Do not unsubscribe from this forum or you risk missing important news!

The preferred method for student communication in this course is to use the [Q&A Forum][qaf] on the course Moodle. The instructional staff monitors this forum and will respond in less than 24 hours (in general we will respond even faster than this, especially during normal business hours). Furthermore, your fellow students may be able to help even faster. We also encourage you to search this forum prior to making a new post since your question may have already been answered.  You can search a forum on Moodle by using the __Search forums__ tool that is located on the upper right corner of any Moodle forum.

If you have a question (that is not answered in this syllabus nor on the online course forums) you can email the instructional staff, however, this should be a last resort. If we feel the question is best answered on the [Q&A Forum][qaf], we reserve the right to post your question and our answer on Moodle. Also, note the information contained in the __Point Reductions__ section of this syllabus. 

Here are the ***appropriate contacts*** for items in this course:

| Topic             | Contact            |
| ----------------- | ------------------ |
| Assessments       | Any TA             |
| Assignments       | Any TA             |
| Extra Credit      | Any CA             |
| Gradebook Items   | Any CA             |
| Grades            | Professor Brunner  |
| JupyterHub Server | Edward Kim or a CA |
| Quizzes           | Any TA             |

Finally, we have created a [gitter room][gr] for this course. This is a completely public, real-time communication channel that you can also use to ask questions.


[qaf]: https://learn.illinois.edu/mod/forum/view.php?id=1844325
[af]: https://learn.illinois.edu/mod/forum/view.php?id=1844322
[gr]: https://gitter.im/lcdm-uiuc/info490-sp17

## Office Hours ##

Scheduled office hours are listed below for all instructors. You can also communicate via the course forums and email.

| Name    | Data     | Time              | Location      |
| ------- | -------- | ----------------- | ------------- |
| Brunner | XXX      | XYZ pm - XYZ pm   | 226 Astronomy |
| Lu      | Thursday | 1:30 pm - 2:30 pm | 234 Astronomy |
| Mughal  | Tuesday  | 6:00 pm - 7:00 pm | Virtual       |
| Thrush  | XXX      | 4:00 pm - 5:00 pm | 234 Astronomy |

## Course Outline ##

Note: The following list of topics is tentative. We build the course during the semester for several reasons:

1. This is a new course (in a new field)!
2. The enrolled students span multiple colleges and even more departments across the University of Illinois.
3. Both undergraduate and graduate students are enrolled.

As a result, we feel it is imperative to be able to change the planned pace and material to benefit the majority of enrolled students.


| **Week**           | **Topics**                               |
| ------------------ | ---------------------------------------- |
| *Orientation Week* | Course Overview & Syllabus Review        |
| *Week 1*           | Introduction to Machine Learning         |
| *Week 2*           | General Linear Models                    |
| *Week 3*           | Introduction to Supervised Machine Learning |
| *Week 4*           | Tree Algorithms and Ensemble Techniques  |
| *Week 5*           | Introduction to Unsupervised Machine Learning |
| *Week 6*           | Practical Machine Learning               |
| *Week 7*           | Introduction to Text Analysis            |
| *Week 8*           | Introduction to Social Media Analysis    |
| *Week 9*           | Natural Language Processing              |
| *Week 10*          | Introduction to Network Analysis         |
| *Week 11*          | Probabilistic Programming                |
| *Week 12*          | Introduction to Cloud Computing          |
| *Week 13*          | Introduction to NoSQL DataStores         |
| *Week 14*          | Introduction to Spark                    |
| *Week 15*          | Introduction to Deep Learning            |


## Weekly Format ##

Each week will provide learning objectives and an outline of the activities for that week with a list of all deadlines and corresponding point values for assignments.

### Videos ###

Each week there will be at least one instructor created video that will offer a broader context for the new week, explain key concepts, and demonstrate important tasks (we also will try to provide per lesson videos). To view the instructor videos, you will need to login to the Illinois Mediaspace (links are embedded in the relevant weekly and lesson overviews). You will not be directly graded for watching the videos; however, we strongly encourage you to watch them as they contain information and demonstrations that will prove helpful as you work through each week's lessons. Note that information presented in course videos may be relevant for quizzes and assessments.

### Readings ###

Readings will consist of articles and excerpts from books and Web sites, internet-accessible videos demonstrating a concept, and, in some cases, IPython Notebooks that can be viewed statically on the Github website, or (via the preferred approach) by interacting with them via the course JupyterHub server. You will be required to read and be familiar with the content of these documents. Readings are contextualized as part of the weekly lesson content and are located in the "Readings" section of each lesson. For those wishing to obtain a deeper understanding, we also present optional readings that provide additional information that is not included course quizzes and assessments.

### Lessons ###

Lessons will expand upon, or clarify key concepts in the reading assignments or supplement or add to the reading. All lessons for a given week must be completed by 6:00 PM Central on Thursday of that week.

### Lesson Assessments ###

Each week will contain three lesson modules (except for the last week, which will contain only one). A lesson module will include a Moodle quiz designed to be taken after completing the readings and carefully reviewing the lesson material. Lesson quizzes have no formal time limit, but you will have ***only one*** attempt. The idea is that you can answer questions as you proceed through the readings, thus ensuring that you have mastered the relevant material before advancing to the next lesson module. The lessons assessments must all be completed by 6:00 PM Central on Thursday of that week.

### Assignments ###

Every week but the first and last will contain an assignment that will involve one or more computational tasks related to the focus for that given week. Your submitted assignments will be collected at the deadline from the course JupyterHub server. These assignments will be automatically graded for your instructor grade, and will also be randomly distributed for peer assessment. You will have up to five problems from different peers to grade for your weekly peer assessment. You will receive fifteen points for simply grading your peer's assignments. Your peer assessment score will be worth a maximum of ten points, and we will drop the two lowest scores and average the three remaining scores.

To receive full credit from instructor grading, your assignment must be submitted prior to the deadline. There will be ***NO*** grace period, late assignments will not be accepted. The assignment deadline is 6:00 PM Central on the Monday following the relevant week.

### Peer Review ###

Weekly assignments will be reviewed by your course peers, as well as automatic instructor grading. 25 points (out of the maximum 150 points for each assignment) for each weekly assignment submission will derive from peer review, 125 points (out of the maximum 150 points for each assignment) are assigned from automated instructor review. You will receive 15 points each week for simply viewing and grading your peers' assignments. Note that you can (and should) still grade your peers even if you miss an assignment submission. Peer review of an assignment must be completed by 6:00 PM Central on Saturday of the following week (i.e., you submit your assignment on a Monday and you must peer assess other students assignments by the following Saturday). You will be assigned assignments to grade approximately one hour after the late assignment deadline, thus around 1:00 pm Tuesday afternoon of each week.

| **Item**              | **Grade**      |
| --------------------- | -------------- |
| Instructor Assessment | 125 points     |
| Peer Grading          | 15 points      |
| Peer Assessments      | 10 points      |
| **Total**             | **150** points |

Several final comments about peer grading:

1. We employ peer grading in large part to enable you to see other approaches to solving the assignments. Treat this as an important aspect of the course and give reasonable grades and provide feedback to your fellow students.

2. We are exploring automatic techniques to check that peer grading is being done appropriately, which will include verification of beneficial comments. As a result, we may amend the peer grading aspect of this syllabus if we feel this technology will prove beneficial. This includes potentially changing the point distribution for current and future assignments.

3. Note that we will *only* review clearly erroneous peer assessments (this means there needs to be a major problem). Review requests that are deemed insignificant are subject to an *instructor determined point reduction*. An example of a **frivolous** request would be *I received no comments and lost several points*.

### Weekly Quizzes ###

In addition to the lesson quizzes, each week will conclude with a weekly quiz. The weekly quiz is designed to test your overall mastery of the content for each given week. Unlike the lesson quizzes, weekly quizzes will be timed and will not allow multiple attempts. The quiz must be completed by 6:00 PM Central on Friday of that week.

### Exams ###

This course is project-based in its use of assignments that build progressively on content mastery, application, and peer review; there are no exams in this course.

## Grading ##

### Grading Distribution ###
| Assignment                             | Points | Occurrences                    | Total Points |
| -------------------------------------- | ------ | ------------------------------ | ------------ |
| Pre-Class Activity: Introduce Yourself | 60     | 1                              | 60           |
| Orientation Quiz                       | 70     | 1                              | 70           |
| Lesson Assessments                     | 60     | 14 (Week 15 is only 20 points) | 860          |
| Weekly Quizzes                         | 70     | 14 (No quiz in Week 15)        | 980          |
| Assignments (Weeks 2-14)               | 150    | 13                             | 1950         |
| ***Total***                            |        |                                | ***3920***   |

Unlike past courses, we do not plan on dropping any weekly scores.

### Grading Scale ###

Final grades will be graded on a curve, if necessary. The letter grade cutoffs will be set at the traditional 90%, 80%, and 70% limits, and plus/minus will be added if you are within two points of the traditional cutoffs (so 100–98 is an A+ and 90–92 is an A-). There will be no rounding of grades, regardless of how close you are to a border.

| Percentage | Letter Grade |
| ---------- | ------------ |
| 98-100     | A+           |
| 92-98      | A            |
| 90-92      | A-           |
| 88-90      | B+           |
| 82-88      | B            |
| 80-82      | B-           |
| 78-80      | C+           |
| 72-78      | C            |
| 70-72      | C-           |
| 68-70      | D+           |
| 62-68      | D            |
| 60-62      | D-           |
| Below 60   | F            |

### Point Reductions ###

This is a large, online course with only one instructor and three teaching assistants. Thus we expect that students read the syllabus and search online forums before either emailing us directly or posting a new question in the Moodle forums. Failure to abide by this request may, at the sole discretion of the instructional staff, result in a loss of five points per **obvious** infraction. Please note that we are not trying to stifle questions (such as why is some server down?). We simply need to minimize the number of such emails/questions we receive.

### Extra Credit ###

There is a course Wiki hosted on the course github repository. If you have a problem and obtain a solution (either through your own efforts or in partnership with an instructor), consider writing your problem and solution up as a FAQ post in the github wiki. You get extra credit for doing this and also help your classmates!

To get credit for your wiki entry you must contact the course assistants. They will review your post and indicate how many points you will receive, and if they would be willing to review an edited post for additional points. You can submit multiple Wiki entries. Note that this is not a trivial task, to receive extra credit you should actually expect to perform work above and beyond the normal effort in this course.

## Sample Weekly Schedule ##

The following table summarizes the typical weekly schedule, where the assignments are collected the Monday following the Friday when quizzes are due.

| Task                                     | Days into *Week* | Date/Time                         |
| ---------------------------------------- | ---------------- | --------------------------------- |
| Week Opens                               | 0                | Monday, 12:00 am                  |
| Lessons Completed                        | 3                | Thursday, 6:00 pm                 |
| Lesson Assessments                       | 3                | Thursday, 6:00 pm                 |
| Weekly Quiz                              | 4                | Friday, 6:00 pm                   |
| Assignment Collected                     | 7                | *The following* Monday, 6:00 pm   |
| Assignments distributed for Peer Assessment | 8                | *The following* Tuesday, 12:00 pm |
| Peer Assessment Deadline                 | 12               | *The following* Saturday, 6:00 pm |
