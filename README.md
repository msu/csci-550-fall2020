# CSCI 550: Advanced Data Mining

**NOTE: This is a live document and is subject to change throughout the
semester.**

Clustering, classification and pattern recognition; performing automated
discovery of knowledge from a data set.

## Meeting Times

Mon, Wed, Fri 09:00-09:50, [Online](https://www.google.com/url?q=https://us04web.zoom.us/j/74532365028?pwd%3DV3hOV040Q1d2VFA0SThkUDlxNVp3Zz09&sa=D&source=calendar&usd=2&usg=AOvVaw0S8d9uRPfR6jww-I0UsAD)

## Instructor

David L. Millman, Ph.D.

**Email**: david.millman@montana.edu

**Office hours**: Mon 13:00-13:50, Fri 12:00-12:50 or by appointment

**Office**: Off campus until further notice

**Github**: [dlm](https://github.com/dlm)

## Learning Outcomes

After successfully completing this course, students will be able to:

- Create a system for extracting information from a large dataset
- Evaluate the performance of that system
- Analyze the ethical and security implications of the system

## Technology

- [Zoom](https://zoom.us)
- [Miro](https://miro.com)
- Collaboration device (e.g. [Wacom one pen
  tablet](https://www.wacom.com/en-us/products/pen-tablets/one-by-wacom))

## Textbook

Required:

* [Data Mining and Machine Learning: Fundamental Concepts and Algorithms, 2nd
Edition](https://dataminingbook.info/book_html/) by Mohammed J. Zaki, Wagner
Meira, Jr., (DM below)


Optional and highly recommended:

* [Mathematical Foundations for Data
  Analysis](http://www.cs.utah.edu/~jeffp/M4D/M4D.html) by Jeff Phillips (M4D
  below)
* [Mining of Massive Datasets](http://i.stanford.edu/~ullman/mmds/book0n.pdf) by
  Jure Leskovec, Anand Rajaraman, and Jeffrey D. Ullman (MoMD below)
* [Lecture Notes from Modern Algorithmic
  Toolbox](http://timroughgarden.org/notes.html) by Tim Roughgarden and Greg
  Valiant (MAT below)
* [Dimension Reduction: A Guided
  Tour](https://www.microsoft.com/en-us/research/publication/dimension-reduction-a-guided-tour-2/)
  by Chris J.C. Burges) (DIM below)
* [Foundations of Data Science](https://www.cs.cornell.edu/jeh/book.pdf) by
  Avrim Blum, John Hopcroft, and Ravindran Kannan (FoDS below)

Others will be added as relevant.

### (Recommended) Background

* **M 221 -- Introduction to Linear Algebra** Matrix algebra, systems of linear
  equations, determinants, vector algebra and geometry in Euclidean 3-space,
  eigenvalues, eigenvectors.

* A course in probability or statistics

* Willingness to get your hands dirty writing code and doing math

## Class schedule

The lecture schedule is subject to change throughout the semester, but here is
the current plan. Assignments and due dates will be updated as they're assigned
in class.

You can access the folders for
[Videos](https://montana.box.com/v/csci-550-fall2020) and [Notes](./notes/).
File names are the date of the lecture.
Videos are hosted on MSU's Box and notes are in this repository.
See below for specific links.

### Aug

| Date  | Description                                   | Assigned                           | Due                                   | Reading       | Links                                                | Video                                                                 |
|-------|-----------------------------------------------|------------------------------------|---------------------------------------|---------------|------------------------------------------------------|-----------------------------------------------------------------------|
| 08/17 | [Intro](.)                                    |                                    |                                       |               | [miro](https://miro.com/app/board/o9J_knKraI4=/)     |                                                                       |
| 08/19 | [Data](./notes/2020-08-19.pdf)                |                                    |                                       | DM Ch 1.1     | [miro](https://miro.com/app/board/o9J_knQ3mn0=/)     | [1](https://montana.box.com/s/y6rghuqtjou1s2pwpjz0c7dck5vj890c) of 1  |
| 08/21 | [Sim, LA Review](./notes/2020-08-21.pdf)      |                                    |                                       | DM Ch 1.2     | [miro](https://miro.com/app/board/o9J_knfQi9s=/)     | [1](https://montana.box.com/s/sphrp4z6whjtwjbqcwm07y068lseeqco) of 1  |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 08/24 | [Data: Prob View 1](./notes/2020-08-24.pdf)   |                                    |                                       | DM Ch 1.3     |                                                      | [1](https://montana.webex.com/recordingservice/sites/montana/recording/playback/423919c56f4f45ccb47b07d618cbc60a) of 1 |
| 08/26 | [Data: Prob View 2](./notes/2020-08-26.pdf)   |                                    |                                       | DM Ch 1.4     |                                                      | [1](https://montana.box.com/s/1vy8l1q8uw3s6r68rbm638ppktrh6i0c) of 1  |
| 08/28 |                                               |                                    |                                       |               |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 08/31 |                                               |                                    |                                       |               |                                                      |                                                                       |

### Sept

| Date  | Description                                   | Assigned                           | Due                                   | Reading       | Links                                                | Video                                                                 |
|-------|-----------------------------------------------|------------------------------------|---------------------------------------|---------------|------------------------------------------------------|-----------------------------------------------------------------------|
| 09/02 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/04 |                                               |                                    |                                       |               |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/07 | NO CLASS (Labor Day)                          |                                    |                                       |               |                                                      |                                                                       |
| 09/09 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/11 |                                               |                                    |                                       |               |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/14 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/16 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/18 |                                               |                                    |                                       |               |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/21 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/23 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/25 |                                               |                                    |                                       |               |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/28 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/30 |                                               |                                    |                                       |               |                                                      |                                                                       |

### Oct

| Date  | Description                                   | Assigned                           | Due                                   | Reading       | Links                                                | Video                                                                 |
|-------|-----------------------------------------------|------------------------------------|---------------------------------------|---------------|------------------------------------------------------|-----------------------------------------------------------------------|
| 10/02 |                                               |                                    |                                       |               |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/05 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/07 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/09 |                                               |                                    |                                       |               |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/12 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/14 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/16 |                                               |                                    |                                       |               |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/19 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/21 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/23 |                                               |                                    |                                       |               |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/26 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/28 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/30 |                                               |                                    |                                       |               |                                                      |                                                                       |

### Nov

| Date  | Description                                   | Assigned                           | Due                                   | Reading       | Links                                                | Video                                                                 |
|-------|-----------------------------------------------|------------------------------------|---------------------------------------|---------------|------------------------------------------------------|-----------------------------------------------------------------------|
| 11/02 | Gerrymandering                                |                                    |                                       |               |                                                      |                                                                       |
| 11/04 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 11/06 |                                               |                                    |                                       |               |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 11/09 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 11/11 | NO CLASS (Veteran's Day)                      |                                    |                                       |               |                                                      |                                                                       |
| 11/13 |                                               |                                    |                                       |               |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 11/16 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 11/18 |                                               |                                    |                                       |               |                                                      |                                                                       |
| 11/20 |                                               |                                    |                                       |               |                                                      |                                                                       |

### (Potential) Upcoming Topics:

- data types dist, similarity, LA & Stats
- Frequent itemset
- Recommender systems
- classification
- clustering
- topological data analysis
- dim reduction
- data viz
- differential privacy / ethics
- compressed sensing
- map reduce
- page rank
- approx-nearest neighbors
- core sets
- curves and surfaces
- locality sensitive hashing


## Evaluation

Your grade for this class will be determined by:

* 10% Quizzes (lowest quiz is dropped)
* 50% Homework (lowest homework is dropped)
* 15% [Group Presentation](./hw/present.md)
* 25% [Group Project](./hw/proj.md)

## Policies

### Attendance

Attendance in class with not be taken but students are responsible for all
material covered in class.  To accommodate the challenges of remote delivery,
this semester (barring technical difficulty), I will record and post lectures
after class.

### Assignments

There will be regular homework assignments (about every week or every other week
depending on the difficulty of the assignment) consisting
of written problems and coding exercises.  Homeworks will be
posted in the schedule.  If not specified, solutions should be submitted as a
PDF on Brightspace.
(The tool that I use for grading documents only works with PDFs, so any file
format other than PDF will receive a 0.)
Homework is due at 23:59 on the due date. Late homework will not be accepted.

You do NOT need to write up your solutions with LaTex, but I highly encourage
you to do so.  You can find some resources for getting started with latex (and
for making figures, and keeping all those files safe with git) in the [student
resources repo](https://github.com/compTAG/student-resources).

I encourage collaboration, see collaboration section for details.

### Discussion

Group discussions, questions, and announcements will take place on the
Brightspace message board.
is okay to send me a direct message or email if you have a question that you feel
is not appropriate to share with the class.  If, however, you send me an message
with a question for which the response would be useful to the rest of the class,
I will likely ask you to post publicly.

### Collaboration

Collaboration IS encouraged, however, all submitted individual work must be your
own and you must acknowledge your collaborators at the beginning of the
submission.

On any group project, every team member is expected to make a substantial
contribution. The distribution of the work, however, is up to the team.

A few specifics for the assignments.  You may:

* Work with anyone in the course.
* Share ideas with others in the course
* Help other teams debug their code or proofs.

You may NOT:

* Submit a proof or code that you did not write.
* Modify another's proof or code and claim it as your own.

Using resources in addition to the course materials is encouraged. But, be sure
to properly cite additional resources. Remember, it is NEVER acceptable to pass
others work off as your own.

Paraphrasing or quoting another's work without citing the source is a form of
academic misconduct. Even inadvertent or unintentional misuse or appropriation
of another's work (such as relying heavily on source material that is not
acknowledged) is considered plagiarism. If you have any questions about using
and citing sources, you are expected to ask for clarification. My rule of thumb
is if I am in doubt, I cite.

By participating in this class, you agree to abide by the [student code of
conduct](http://www.montana.edu/policy/student_conduct/).  Please review the
policy.

### Classroom Etiquette

Please, keep your mics muted, when you are not speaking.  Background noise from
your surrounds can be destructing to other learners.  Disruptions to the class
will result in you being asked to leave the lecture and will negatively impact
your grade.


### Health-Related Class Absence

Please evaluate your own health status regularly and refrain from attending
class and other on-campus events if you are ill.  MSU students who miss class
due to illness will be given opportunities to access course materials online.
You are encouraged to seek appropriate medical attention for treatment of
illness.  In the event of contagious illness, please do not come to class or to
campus to turn in work or attend class. Instead notify me by email me about your
absence as soon as practical, so that accommodations can be made.  Please note
that documentation (a Doctor's note) for medical excuses is not required.  MSU
University Health Partners - as part their commitment to maintain patient
confidentiality, to encourage more appropriate use of healthcare resources, and
to support meaningful dialogue between instructors and students - does not
provide such documentation.


### Disabilities

If you are a student with a disability and wish to use your approved
accommodations for this course, please contact me during my office hours to
discuss. Please have your Accommodation Notification or Blue Card available for
verification of accommodations.  Accommodations are approved through the Office
of Disability Services located in SUB 174. www.montana.edu/disabilityservices
