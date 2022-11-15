# COSC 516 - Special Topics in Databases - Sept 2022

## Instructor
Dr. Ramon Lawrence, ramon.lawrence@ubc.ca, 250-807-9390<br>
**Live Classroom Schedule:** Monday/Wednesday 3:30 p.m. to 5:00 p.m.<br>
**Mode of Delivery:** ART 218 and live-stream on Zoom<br>
**Office Hours:** Mondays 1 to 3 p.m. or by an appointment<br>
**Office Location:** ASC 349<br>
**[UBCO Calendar Course Description](http://www.calendar.ubc.ca/okanagan/courses.cfm?go=name&code=COSC)**

## Course Description
**Official Calendar:** Advanced or specialized topics in database design, modelling, and implementation. This course may be taken more than once for credit. Credit will be granted for only one of COSC 416 or COSC 516 when the subject matter is of the same nature.<br>
**Prerequisite:** None. Prior database experience is helpful but not required.

**Specific description:** This course provides an applied introduction to database systems deployed in the cloud. The course begins with a review of database foundations including the relational model, SQL, and NoSQL systems. Each week a particular database system will be examined including hands-on experience with deploying and using the system. Specific systems explored include MySQL on Amazon Web Services, SQL Server/Azure DB on Microsoft Azure, and Bigtable on Google Cloud. Each student will select a database to study and present, and develop a lab assignment for other students to complete.

## Course Objectives
**Course Format:** Each course session will be done in person and streamed on Zoom. Each week a different database is presented. The first class of the week provides foundations on the database system and its particular features and use cases. Students will complete an interactive lab assignment on the database by the end of the second class of the week.

**Learning Outcomes:**
 - Analyze database use cases to determine the appropriate database systems to use based on their architectures and features.
 - Create a database system on each of the three major cloud providers (AWS, Azure, Google) and compare their properties.
 - Design technical summary documents and learning activities to educate others.
 - Construct queries and programs to interact with cloud databases including using testing frameworks.
 - Compare a variety of database technologies and systems and argue when to use them.
 - Demonstrate allocating and managing resources on a cloud provider and monitoring billing and costs.

## Marking and Evaluation
| Item | Weighting | Description |
|------|-----------|-------------|
| Assignments | 40% | Weekly assignments |
| Project | 30% | Present on a particular database system | 
| Final Exam | 30% | Saturday, December 17 in FIP 138 at 8:30 a.m.  |

## Textbook and Reference Material
 - All notes are online.
 - A textbook is not required. Students can get supplemental material from any database textbook.

## Expectations
 - Attend all classes and prepare before attending class. 
 - **Expect to spend about six hours per week in out-of-class activities.**
 - Learn the material in the course by completing all assignments. **No late assignments are accepted.**
 - Enjoy attending class activities and participate according to your personality.  Ask questions by posting on chat or raising your hand.
 - Spent time creating a good project with well-designed written documentation, video summary, and an interesting lab assignment.
 - **I want all students to pass the course, receive a good grade, and feel the course was beneficial.**

## Schedule

|   Date | Topic  | Reading and Resources |
|------------|------|-----------|
| Sept. 7 (W) | [**First day of classes.  Introduction to course and databases**](topics/1_intro) |  |
| Sept. 12 (M) | [Relational Model and Algebra](topics/2_relational_model) | [Online Relational Algebra Tool](https://dbis-uibk.github.io/relax/), [WorksOn Data Set](https://gist.github.com/rlawrenc/5a7eb3f69cbea033c04c3cdf680a2e39), [Bank Data Set](https://gist.github.com/rlawrenc/51721bd35f05ce3ef7391ff826f8f81a)  |
| Sept. 14 (W) | [SQL](topics/3_sql) | [SQL DDL](https://github.com/rlawrenc/cosc_304/tree/main/topics/5_sql_ddl), [Basic SQL](https://github.com/rlawrenc/cosc_304/tree/main/topics/6_sql), [SQL Aggregation](https://github.com/rlawrenc/cosc_304/tree/main/topics/7_sql_aggregation) |
| Sept. 19 (M) | [Amazon RDS](topics/4_amazon_rds) <br>**No in-person class due to national day of mourning** | [Amazon RDS](https://aws.amazon.com/rds/), [Read Replicas](https://aws.amazon.com/rds/features/read-replicas/), [Multi-AZ](https://aws.amazon.com/rds/features/multi-az/), [Aurora](https://aws.amazon.com/rds/aurora/), [Getting started guide](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_GettingStarted.html) |
| Sept. 21 (W) | [Amazon RDS Lab](https://classroom.github.com/a/CxwujtzS) |  |
| Sept. 26 (M) | [SQLServer on Microsoft Azure Overview](topics/5_microsoft_sqlserver_azure) | [Azure](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-azure/), [Azure SQL](https://learn.microsoft.com/en-us/azure/azure-sql/database/sql-database-paas-overview?view=azuresql)  |
| Sept. 28 (W) | [SQLServer on Microsoft Azure Lab](topics/5_microsoft_sqlserver_azure) |  |
| Oct. 3 (M) | [Bigtable on Google Cloud Overview](topics/6_google_bigtable) | [Google Bigtable](https://cloud.google.com/bigtable), [Intro Tutorial](https://codelabs.developers.google.com/codelabs/cloud-bigtable-intro-java/index.html), [Creating an Instance](https://cloud.google.com/bigtable/docs/creating-instance), [Pricing](https://cloud.google.com/bigtable/pricing), [Research Publication](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf), [SSTable](https://www.igvita.com/2012/02/06/sstable-and-log-structured-storage-leveldb/), [Client libraries](https://cloud.google.com/bigtable/docs/reference/libraries), [Java Client Library](https://github.com/googleapis/java-bigtable) |
| Oct. 5 (W) | **Project Work Class**<br>**No class** |  |
| Oct. 10 (M) | **No class due to Thanksgiving** | |
| Oct. 12 (W) | [Bigtable on Google Cloud Lab](https://github.com/cosc-516-2022/lab3) | |
| Oct. 17 (M) | [MongoDB on Mongo Atlas Overview](topics/7_mongodb_atlas) | [MongoDB](https://www.mongodb.com), [Docs](https://www.mongodb.com/docs/manual), [Pricing](https://www.mongodb.com/pricing) |
| Oct. 19 (W) | [MongoDB on Mongo Atlas Lab](topics/7_mongodb_atlas) |  |
| Oct. 24 (M) | **Project Work Class** | |
| Oct. 26 (W) | **Project Work Class**<br>**No class** | |
| Oct. 31 (M) | [Group #1 (Jon/Satabdi) - Microsoft Cosmos DB Overview](topics/8_cosmos_db) | |
| Nov. 2 (W) |  [Group #1 (Jon/Satabdi) - Microsoft Cosmos DB Lab](https://github.com/cosc-516-2022/lab5) | |
| Nov. 7 (M) | **No class for Term 1 midterm break** | |
| Nov. 9 (W) | **No class for Term 1 midterm break** | |
| Nov. 14 (M) | [Group #2 (Namrata/Sayan/Daven) - Neo4J Overview](topics/9_neo4j) | |
| Nov. 16 (W) | [Group #2 (Namrata/Sayan/Daven) - Neo4J Lab]((https://github.com/cosc-516-2022/lab6) | |
| Nov. 21 (M) | [Group #3 (Wei-Hsiang/Muhammad) - Redis Overview]() | |
| Nov. 23 (W) | [Group #3 (Wei-Hsiang/Muhammad) - Redis Overview]() | |
| Nov. 28 (M) | [Group #4 (Jumar/Devon) - Amazon Redshift Overview]() | |
| Nov. 30 (W) | [Group #4 (Jumar/Devon) - Amazon Redshift Lab]() | |
| December 5 (M) | [Group #5 (Pragya/Weixiao) - Influx Overview]() | |
| December 7 (W) | [Group #5 (Pragya/Weixiao) - Influx Lab]() | |
| December 12 (M) | [Group #6 (Erfan/Lyra) - Cassandra Overview]() | |
| December 14 (W) | [Group #6 (Erfan/Lyra) - Cassandra Lab]() | |
| December 17 (Sa) | Final Exam on Computer in FIP 138 starting at 8:30 a.m. | |


## Labs

|  Lab  |  Date  |  Topic  |
|----|------|-------|
|  | September 5 – 9 |	**No Lab during First Week of Class** |
|  | September 12 – 16 | **No Lab during Second Week of Class** |
| [1](https://github.com/cosc-516-2022/lab1) | September 19 – 23 | Lab 1: MySQL on Amazon RDS |
| [2](https://github.com/cosc-516-2022/lab2) | September 26 – 30 | Lab 2: SQLServer on Microsoft Azure |
| [3](https://github.com/cosc-516-2022/lab3) | October 3 – 7 | Lab 3: Bigtable on Google Cloud |
| [4](https://github.com/cosc-516-2022/lab4) | October 10 – 21 | Lab 4: MongoDB on Mongo Atlas |
|  | October 24 – 28 | **No Lab**  |
| [5](https://github.com/cosc-516-2022/lab5) | Oct. 31 – Nov. 4 | Lab 5: Microsoft Cosmos DB |
|  | November 7 - 11 |	**No Lab during Midterm Break** |
| [6](https://github.com/cosc-516-2022/lab6) | November 14 – 18 | Lab 6: Neo4J |
| 7 | November 21 – 25 | Lab 7: Redis |
| 8 | Nov. 28 – Dec. 2 | Lab 8: Amazon Redshift |
| 9 | December 5 - 9 | Lab 9: Influx |
| 10 | December 12 - 16 | Lab 10: Cassandra |

Potential databases for student projects:
- Key-value stores: Cassandra
- High-availability: Google Spanner
- Batch databases: Hadoop, Hive
- In-memory databases: Redis
- Warehousing/analytics: Snowflake, Amazon Redshift
- Graph databases: Amazon Neptune, Neo4J
- Time series databases: InfluxDB

## Copyright Disclaimer   
Diagrams and figures included in lecture presentations adhere to Copyright Guidelines for UBC Faculty, Staff and Students http://copyright.ubc.ca/requirements/copyright-guidelines/ and UBC Fair Dealing Requirements for Faculty and Staff http://copyright.ubc.ca/requirements/fair-dealing/.  Some of these figures and images are subject to copyright and will not be posted to Canvas.   All material uploaded to Canvas that contain diagrams and figures are used with permission of the publisher; are in the public domain; are licensed by Creative Commons; meet the permitted terms of use of UBC’s library license agreements for electronic items; and/or adhere to the UBC Fair Dealing Requirements for Faculty and Staff. Access to the Canvas course site is limited to students currently registered in this course. Under no circumstance are students permitted to provide any other person with means to access this material. Anyone violating these restrictions may be subject to legal action. Permission to electronically record any course materials must be granted by the instructor. Distribution of this material to a third party is forbidden.

## Grievances and Complaints Procedures
A student who has a complaint related to this course should follow the procedures summarized below:<br>
- The student should attempt to resolve the matter with the instructor first. Students may talk first to someone other than the instructor if they do not feel, for whatever reason, that they can directly approach the instructor. 
- If the complaint is not resolved to the student's satisfaction, the student should e-mail the Associate Head, Dr. Yves Lucet at yves.lucet@ubc.ca or the Department Head, Dr. John Braun at cmps.depthead@ubc.ca.
 
## Your Responsibilities
Your responsibilities to this class and to your education as a whole include attendance and participation. You have a
responsibility to help create a classroom environment where all may learn. At the most basic level, this means you will
respect the other members of the class and the instructor and treat them with the courtesy you hope to receive in return.
Inappropriate classroom behavior may include: disruption of the classroom atmosphere, engaging in non-class activities,
talking on a cell-phone, inappropriate use of profanity in classroom discussion, use of abusive or disrespectful language
toward the instructor, a student in the class, or about other individuals or groups.

## Academic Integrity
The academic enterprise is founded on honesty, civility, and integrity.  As members of this enterprise, all students are expected to know, understand, and follow the codes of conduct regarding academic integrity.  At the most basic level, this means submitting only original work done by you and acknowledging all sources of information or ideas and attributing them to others as required.  This also means you should not cheat, copy, or mislead others about what is your work.  Violations of academic integrity (i.e., misconduct) lead to the breakdown of the academic enterprise, and therefore serious consequences arise and harsh sanctions are imposed.  For example, incidences of plagiarism or cheating may result in a mark of zero on the assignment or exam and more serious consequences may apply if the matter is referred to the President’s Advisory Committee on Student Discipline.  Careful records are kept in order to monitor and prevent recurrences. 
A more detailed description of academic integrity, including the University’s policies and procedures, may be found in the Academic Calendar at:  http://okanagan.students.ubc.ca/calendar/index.cfm?tree=3,54,111,0.
  If you have any questions about how academic integrity applies to this course, please consult with your professor.

## Academic Integrity Course Policies
Academic integrity is critical to being a professional developer and a respected person. This is a guide to what is and is not acceptable behaviors in this course.

### In-Class Participation and Quizzes and Teamwork Collaboration
#### Allowed
- Collaboration in groups of up to 4 on Canvas quizzes and in-class exercises

#### Not Allowed
 - One person providing all answers for a quiz/exercise to a group of people of any size
 - Sharing, posting, or distributing answers to other students or websites for quizzes/exercises
 - Answering questions for another student or submitting answers on their behalf
 - Requesting help from previous students in the course or other individuals outside of the course
 - Relying on others to do work for me or not contributing reasonable effort to group activities
 - Dividing up the work for a quiz or exercise between members of an approved group (*Not Recommended*)

### Assignments
#### Allowed
- Collaborating with your approved group members (usually two) and submitting a shared answer to the assignment
- Request help from the TA or instructor and use the answer/code that they provide
- Answer general questions about assignments in chat or discussion forums (*Allowed with care*)

#### Not Allowed
 - Working on an individual assignment with a group of people and submitting minor variations of work developed together
 - For group assignment, completing all work independently and providing answer to rest of group
 - Sharing solutions to assignments with other students or on the Internet	
 - Receiving solutions to assignments from other sources (students, web, tutors)	
	
### Exams
#### Allowed
- Using course material including assignments, notes, and quizzes in an open book exam

#### Not Allowed
- Using any non-approved resource (people, web, etc.) for exams **(severe)**
- Allowing another person to write or complete any part of any exam **(severe)**
- Posting or providing answers to students who have not yet completed the exam
- Requesting help from other people or web services for open book exams
- Posting or providing exam questions and answers after exam has been completed

### Grading Practices   
Faculties, departments, and schools reserve the right to scale grades in order to maintain equity among sections and conformity to University, faculty, department, or school norms. Students should therefore note that an unofficial grade given by an instructor might be changed by the faculty, department, or school. Grades are not official until they appear on a student's academic record. http://www.calendar.ubc.ca/okanagan/index.cfm?tree=3,41,90,1014  If you have any questions about how academic integrity applies to this course, please consult with your professor.

### Disability Resource Centre
The Disability Resource Centre ensures educational equity for students with disabilities and chronic medical conditions. If you are disabled, have an injury or illness and require academic accommodations to meet the course objectives, please contact Earllene Roberts, the Diversity Advisor for the Disability Resource Centre located in the University Centre building (UNC 215). Ph: 250.807.9263 Email: earllene.roberts@ubc.ca  Web: [https://students.ok.ubc.ca/drc](https://students.ok.ubc.ca/drc)

### Equity and Inclusion Office
Through leadership, vision, and collaborative action, the Equity & Inclusion Office (EIO) develops action strategies in support of efforts to embed equity and inclusion in the daily operations across the campus. The EIO provides education and training from cultivating respectful, inclusive spaces and communities to understanding unconscious/implicit bias and its operation within in campus environments. UBC Policy 3 prohibits discrimination and harassment on the basis of BC’s Human Rights Code. If you require assistance related to an issue of equity, educational programs, discrimination or harassment please contact the EIO. Office: UNC 325H Ph: 250.807.9291 Email: equity.ubco@ubc.ca  Web: [https://equity.ok.ubc.ca](https://equity.ok.ubc.ca)

### Office of the Ombudsperson for Students  
The Office of the Ombudsperson for Students is an independent, confidential and impartial resource to ensure students are treated fairly. The Ombuds Office helps students navigate campus-related fairness concerns. They work with UBC community members individually and at the systemic level to ensure students are treated fairly and can learn, work and live in a fair, equitable and respectful environment. Ombuds helps students gain clarity on UBC policies and procedures, explore options, identify next steps, recommend resources, plan strategies and receive objective feedback to promote constructive problem solving. If you require assistance, please feel free to reach out for more information or to arrange an appointment.  Office: UNC 328 Ph: 250.807.9818 Email: ombuds.office.ok@ubc.ca   
Web: [https://ombudsoffice.ubc.ca](https://ombudsoffice.ubc.ca)

### Sexual Violence Prevention and Response Office (SVPRO)
A safe and confidential place for UBC students, staff and faculty who have experienced sexual violence regardless of when or where it took place. Just want to talk? We are here to listen and help you explore your options. We can help you find a safe place to stay, explain your reporting options (UBC or police), accompany you to the hospital, or support you with academic accommodations. You have the right to choose what happens next. We support your decision, whatever you decide. Visit svpro.ok.ubc.ca or call us at 250.807.9640.

### Independent Investigations Office (IIO)
If you or someone you know has experienced sexual assault or some other form of sexual misconduct by a UBC community member and you want the Independent Investigations Office (IIO) at UBC to investigate, please contact the IIO. Investigations are conducted in a trauma informed, confidential and respectful manner in accordance with the principles of procedural fairness. You can report your experience directly to the IIO by calling 604-827-2060. Web:  [https://investigationsoffice.ubc.ca](https://investigationsoffice.ubc.ca) E-mail: director.of.investigations@ubc.ca  

### Student Learning Hub  
The Student Learning Hub (LIB 237) is your go-to resource for free math, science, writing, and language learning support. The Hub welcomes undergraduate students from all disciplines and year levels to access a range of supports that include tutoring in math, sciences, languages, and writing, as well as help with study skills and learning strategies. For more information, please visit the Hub’s website [https://students.ok.ubc.ca/student-learning-hub](https://students.ok.ubc.ca/student-learning-hub) or call 250-807-9185.  
 
### Student Wellness   
At UBC Okanagan health services to students are provided by Student Wellness.  Nurses, physicians and counsellors provide health care and counselling related to physical health, emotional/mental health and sexual/reproductive health concerns. As well, health promotion, education and research activities are provided to the campus community.  If you require assistance with your health, please contact Student Wellness for more information or to book an appointment.  

UNC 337 250.807.9270  
email: healthwellness.okanagan@ubc.ca  
Web: [https://students.ok.ubc.ca/health-wellness](https://students.ok.ubc.ca/health-wellness)  

### SAFEWALK
Don't want to walk alone at night?  Not too sure how to get somewhere on campus?  Call Safewalk at 250-807-8076.
For more information:  [https://security.ok.ubc.ca/safewalk](https://security.ok.ubc.ca/safewalk)  or download the UBC SAFE – Okanagan app

## Reference Material
* [COSC 304](https://github.com/rlawrenc/cosc_304)
* [COSC 404](https://github.com/rlawrenc/cosc_404)
