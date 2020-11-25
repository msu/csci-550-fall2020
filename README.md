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

**Office hours**: Mon 14:00-14:50 of Fri 12:00-12:50 on [webex](https://montana.webex.com/join/c54s194)

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
| 08/28 | [Data: Prob View 3](./notes/2020-08-28.pdf)   | [HW 00](./hw/00.pdf)               |                                       | DM Ch 1.4     |                                                      | [1](https://montana.box.com/s/gei46ijj8y7yyg7mdydc5phdnkhkr2tc) of 1  |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 08/31 | [Frequent Itemset 1](./notes/2020-08-31.pdf)  |                                    |                                       | DM Ch 8       | [miro](https://miro.com/app/board/o9J_kmCt3t8=/)     | [1](https://montana.box.com/s/zchmrs3cicmlyjn06f0yqfeoos54qror) of 1  |

### Sept

| Date  | Description                                   | Assigned                           | Due                                   | Reading       | Links                                                | Video                                                                 |
|-------|-----------------------------------------------|------------------------------------|---------------------------------------|---------------|------------------------------------------------------|-----------------------------------------------------------------------|
| 09/02 | [Frequent Itemset 2](./notes/2020-09-02.pdf)  |                                    |                                       | DM Ch 8       |                                                      | [1](https://montana.box.com/s/pcws63ecnqxfhtjrf5h2qrnrvr827132) of 1  |
| 09/04 | [Rule Mining](./notes/2020-09-04.pdf)         |                                    | [HW 00](./hw/00.pdf)                  | DM Ch 8       |                                                      | [1](https://montana.box.com/s/uhylk6opivczzk3boekv5slciqnh5utu) of 1  |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/07 | NO CLASS (Labor Day)                          |                                    |                                       |               |                                                      |                                                                       |
| 09/09 | [Rule Assessment](./notes/2020-09-09.pdf)     |                                    |                                       | DM Ch 8       |                                                      | [1](https://montana.box.com/s/iuo08j24lh98roc0knew9jbnbosjg68j) of 1  |
| 09/11 | [Assessment (cont)](./notes/2020-09-11.pdf)   | [HW 01](./hw/01.md)                |                                       | DM Ch 8       |                                                      | [1](https://montana.box.com/s/xh6ob9xp580l9xvbign1qq5ndcqrrkeh) of 1  |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/14 | [Recommender Systems](./notes/2020-09-14.pdf) |                                    |                                       | MoMD Ch 6     |                                                      | [1](https://montana.box.com/s/lavurxagxwz27tjh4s7j827tnnkoway8) of 1  |
| 09/16 | [Content Based](./notes/2020-09-16.pdf)       |                                    |                                       | MoMD Ch 6     |                                                      | [1](https://montana.box.com/s/zkwkfquqgun3b4cbi4pmjfi6hrkquz6f) of 1  |
| 09/18 | [Collab Filtering](./notes/2020-09-18.pdf)    |                                    |                                       | MoMD Ch 6     |                                                      | [1](https://montana.box.com/s/he3cyqath8ul9vrxf96eoc47li1byslv) of 1  |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/21 | [Rep Clust](./notes/2020-09-21.pdf)           |                                    | [HW 01](./hw/01.md)                   | DM Ch 13      |                                                      | [1](https://montana.box.com/s/3xx44y0rfq9y9uvl9e15lcwl6aok0m2j) of 1  |
| 09/23 | [_k_Means & Hier Clust](notes/2020-09-21.pdf) |                                    |                                       | DM Ch 13      |                                                      | [1](https://montana.box.com/s/6uu04b9y1kc7afpag2boq43x6wam8cip) of 1  |
| 09/25 | [Hier Clust](./notes/2020-09-25.pdf)          |                                    |                                       | DM Ch 14      |                                                      | [1](https://montana.box.com/s/c4145w0xllmt8as9bawtyrmqnqqrg6tn) of 1  |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 09/28 | [Density Clust](./notes/2020-09-28.pdf)       |                                    |                                       | DM Ch 15      |                                                      | [1](https://montana.box.com/s/stygayipigutv3pww6i0ow2u51s7lid2) of 1  |
| 09/30 | [DB Scan](./notes/2020-09-30.pdf)             |                                    |                                       | DM Ch 15      |                                                      | [1](https://montana.box.com/s/1nnzmdiayeh3rcpedcg6u9sl53p3chsu) of 1  |

### Oct

| Date  | Description                                   | Assigned                           | Due                                   | Reading       | Links                                                | Video                                                                 |
|-------|-----------------------------------------------|------------------------------------|---------------------------------------|---------------|------------------------------------------------------|-----------------------------------------------------------------------|
| 10/02 | [Cluster assess pt 1](./notes/2020-10-02.pdf) |                                    |                                       | DM Ch 17      |                                                      | [1](https://montana.box.com/s/jhzeeyeu9nyntyjdzc5o3k09z7bftxdd) of 1  |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/05 | [Cluster assess pt 2](./notes/2020-10-05.pdf) | [HW 02](./hw/02.md)                |                                       | DM Ch 17      |                                                      | [1](https://montana.box.com/s/q3y0p241uh1loc1eyy72q0lis7ym2hla) of 1  |
| 10/07 | [Classification Tasks](./notes/2020-10-07.pdf)|                                    |                                       | DM Ch 22      |                                                      | [1](https://montana.box.com/s/mache8st9hw1a4xmvg4umm5lsrr43z3d) of 1  |
| 10/09 | [Decision Trees pt 1](./notes/2020-10-09.pdf) |                                    |                                       | DM Ch 22      |                                                      | [1](https://montana.box.com/s/dmb53vg56ozmrtmlzu4xezrkdyv4rp2u) of 1  |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/12 | [Decision Trees pt 2](./notes/2020-10-12.pdf) |                                    |                                       | DM Ch 22      |                                                      | [1](https://montana.box.com/s/7m2h8a5306xdwyi5qrd3btmr09k09hvp) of 1  |
| 10/14 | [k-Nearest Neighbors](./notes/2020-10-14.pdf) |                                    |                                       | DM Ch 22      |                                                      | [1](https://montana.box.com/s/z35cznx0i5if3em0gwpkniyvmn68hoda) of 1  |
| 10/16 | [Classify assess pt 1](./notes/2020-10-16.pdf)|                                    |                                       | DM Ch 22      |                                                      | [1](https://montana.box.com/s/y3h7mpov2vrivt96gmf6ecymqdgmwkun) of 1  |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/19 | [Classify assess pt 2](./notes/2020-10-19.pdf)|                                    | [HW 02](./hw/02.md)                   | DM Ch 22      |                                                      | [1](https://montana.box.com/s/6mp8orhx68htl1ak1twf3hf3z585vmwb) of 1  |
| 10/21 | [Compare classifiers](./notes/2020-10-21.pdf) |                                    |                                       | DM Ch 22      |                                                      | [1](https://montana.box.com/s/elly0j3hzew9e8dh7395smallrpadryu) of 1  |
| 10/23 | [Dim reduction into](./notes/2020-10-23.pdf)  |                                    |                                       | DM Ch 7       |                                                      | [1](https://montana.box.com/s/2t1ekcqonncwsq4ujwub88jlyk6gecsh) of 1  |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 10/26 | NO CLASS - TECHNICAL ISSUES                   |                                    |                                       |               |                                                      |                                                                       |
| 10/28 | Proj, Presentation, Hw 3                      | [HW 03](./hw/03.md)                |                                       |               |                                                      | [1](https://montana.box.com/s/59mubqayfs4q49qjg79rihntqsy2t60z) of 1  |
| 10/30 | [Projections](./notes/2020-10-30.pdf)         |                                    | [Present](./hw/present.md)            | DM Ch 7       |                                                      | [1](https://montana.box.com/s/5lazon9ls2bmhm1tgzvyx1va0wu1ess3) of 1  |


### Nov

| Date  | Description                                   | Assigned                           | Due                                   | Reading       | Links                                                | Video                                                                 |
|-------|-----------------------------------------------|------------------------------------|---------------------------------------|---------------|------------------------------------------------------|-----------------------------------------------------------------------|
| 11/02 | [PCA Pt 1](./notes/2020-11-02.pdf)            |                                    | [Proj](./hw/proj.md)                  | DM Ch 7       |                                                      | [1](https://montana.box.com/s/fwgi3yyiah7pan3oir39oqocb9uss8b2) of 1  |
| 11/04 | [PCA Pt 2](./notes/2020-11-04.pdf)            |                                    |                                       | DM Ch 7       |                                                      | [1](https://montana.box.com/s/v024vigqpc26ayivwha9k58hjksulnq7) of 1  |
| 11/06 | [Graph Data](./notes/2020-11-06.pdf)          |                                    | [Proj](./hw/proj.md)                  | DM Ch 4       |                                                      | [1](https://montana.box.com/s/3t7idho50hmc13ses8wncndd2nso7lgu) of 1  |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 11/09 | [Centrality](./notes/2020-11-10.pdf)          |                                    | [HW 03](./hw/03.md)                   | DM Ch 4       |                                                      | [1](https://montana.box.com/s/wervutu5213zo979itqdmj2mtajcct9j) of 1  |
| 11/11 | NO CLASS (Veteran's Day)                      |                                    |                                       |               |                                                      |                                                                       |
| 11/13 | [Intrusion detection](./notes/2020-11-13a.pdf), [Fake Data Detection](./notes/2020-11-13b.pdf)                             |||             |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 11/16 | [Stan](./notes/2020-11-16a.pdf),[Regression](./notes/2020-11-16b.pdf)              |                                       |||             |                                                      |                                                                       |
| 11/18 | [Frequent Subgraph](./notes/2020-11-18a.md), [Timeseries and TDA](./notes/2020-11-18b.pdf)                                 |||             |                                                      |                                                                       |
| 11/20 | [Implementing DBScan](./notes/2020-11-20a.pdf), [Streaming with Kafka](./notes/2020-11-20b.pdf)                            |||             |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| 11/23 | Project Presentations                         |                                    | [Proj](./hw/proj.md)                  |               |                                                      |                                                                       |
| 11/25 | Project Presentations                         |                                    | [Proj](./hw/proj.md)                  |               |                                                      |                                                                       |
|       |                                               |                                    |                                       |               |                                                      |                                                                       |
| video | [Decision making](./notes/2020-11-18c.pdf)
| video | [(AWAITING CONTENT) Outlier detection](./notes/2020-11-18d.pdf)
| video | [Time series](./notes/2020-11-18e.pdf)
| video | [Subspace Clustering](./notes/2020-11-18f.pdf)
| video | [Locality Sensitive Hashing](./notes/2020-18g.pdf)
| video | [Linear Discriminant Analysis](./notes/2020-11-18h.pdf)
|

### (Potential) Upcoming Topics:

- topological data analysis
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

* ~~10% Quizzes (lowest quiz is dropped)~~ (Removed due to technical constraints)
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
