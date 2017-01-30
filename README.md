## CS 440: Introduction to Artificial Intelligence

##### Topics:

The class will introduce fundamental ideas that have emerged over the past fifty years of AI research. It will also provide a useful toolbox of AI algorithms. The main unifying theme is the idea of an intelligent agent: autonomous computational systems that receive percepts from the environment and perform actions or take decisions. The objective of the class is to (a) teach students how to identify the appropriate technique for designing such intelligent agents for different types of problems and (b) provide them experience in implementing such solutions on representative AI challenges.

The class will be split into three modules. Each module will focus on a different set of challenges and the corresponding techniques:

Part 1 - Deterministic Reasoning: Heuristic Search, Local Search, Adversarial Search, Constraint Satisfaction Problems, Logic-based Reasoning, Classical Planning, Motion Planning  
Part 2 - Reasoning under Uncertainty: Bayesian Networks, Hidden Markov Models, Kalman and Particle Filters, (Partially Observable) Markov Decision Processes  
Part 3 - Introduction to Machine Learning: Decision Trees, Expectation Maximization, Neural Networks, Support Vector Machines, Principles of Reinforcement Learning

Below follows a more detailed description of the above modules:

Part 1: Initially the focus will be on autonomous decision-making in deterministic environments. Search techniques (including dynamic programming algorithms, informed techniques like A* and local search methods, such as hill climbing and simulated annealing) will be presented. These methods reason over several steps into the future. The class will then discuss ways to represent knowledge about the world through logic and how to reason logically with that knowledge, especially for problems with constraints. The first part of the class will close with path planning algorithms in continuous spaces and action planning.

Part 2: This part will introduce a significant challenge, that of uncertainty. In this section, the intelligent agents do not have perfect knowledge of the world. They depend on probabilistic tools, such as the Bayes law, in order to reason about their state, the world and take decisions. For example Bayesian networks will be presented that provide a systematic way of representing independence and conditional independence relationships in order to simplify probabilistic representations of the world. They can be used in order to achieve inference under uncertainty. Building on these tools, we will present filtering variants of Hidden Markov Models (e.g. Kalman filter, particle filters) that are able to reason under uncertainty when the environment changes over time. Then through the tool of Markov Decision Processes we will show how it is possible to not only infer the world’s state under the presence of uncertainty but also to make decisions under uncertainty so as to maximize an expected utility function.

Part 3: The final part of the class involves even more challenging problems, where the environment is not just uncertain but unknown. In order for agents to be able to cope with such problems they depend on learning techniques that generate the knowledge required for decision-making. Inductive learning techniques use observations to create simple theories about the world. Statistical learning methods learn probabilistic models of the world when there is uncertainty in the measurements. Neural networks are biologically inspired and provide a way of inferring a world model. Finally, reinforcement learning techniques show how intelligent agents can learn from success and failure, from reward and punishment.

The class will conclude with the future prospects of AI.

##### Tentative Calendar

Check [Rutgers' Academic Calendar](https://scheduling.rutgers.edu/scheduling/academic-calendar).

- Lecture 1 - Jan. 17: Introduction [Chapters 1.1-1.2-1.3-1.4-1.5-2.1-2.2-2.3-2.4-2.5]
- Lecture 2 - Jan. 19: Uninformed Search [Chapters 3.1-3.2-3.3-3.4]
- Lecture 3 - Jan. 24: Heuristic Search [Chapters 3.5 - 3.6]
- Lecture 4 - Jan. 26: Adversarial Search [Chapters 5.1-5.2-5.3-5.4-5.5]
- Recitation 1: Properties of Search Algorithms
- Lecture 5 - Jan. 31: Local Search [Chapters 4.1-4.2-4.5]
- Lecture 6 - Feb. 2: Constraint Satisfaction Problems [Chapters 6.1-6.2-6.3-6.4]
- Recitation 2: Local Search and Adversarial Search Examples
- Lecture 7 - Feb. 7: Logic-based Inference [Chapters 7.2-7.4-7.5-7.6]
- Lecture 8 - Feb. 9: Binary Satisfiability [Chapters 7.2-7.4-7.5-7.6]
- Recitation 3: Logic Primer
- Lecture 9 - Feb. 14: Classical Planning [Chapters 10.1-10.2]
- Lecture 10 - Feb. 16: Probabilistic Reasoning [Chapters 13.2-13.3-13.4-13.5-13.6]
- Recitation 5: Probabilities Primer
- Lecture 11 - Feb. 21: Bayesian Networks [Chapters 14.1-14.2-14.3]
- Lecture 12 - Feb. 23: Bayesian Inference [Chapters 14.4-14.5]
- Recitation 6: Bayesian Networks Examples
- Lecture 13 - Feb. 28: Temporal Models [Chapters 15.1-15.2]
- Lecture 14 - Mar. 2: HMMs: Smoothing, Most Likely Explanation [Chapters 15.3-15.4-15.5]
- Recitation 7: Midterm review
- _Midterm_ - Mar. 7
- Lecture 15 - Mar. 9: Kalman and Particle Filters - Intro to Utility Theory [Chapters 15.3-15.4-16.2-16.3-16.4]
- Recitation 8: Gaussian Distributions
- Lecture 16 - Mar. 21: Decision Networks - Intro to Markov Decision Processes [Chapters 16.5-16.6 - Chapter 17.1]
- Lecture 17 - Mar. 23: Value & Policy Iteration [Chapters 17.2-17.3]
- Recitation 9: Decision Network Examples
- Lecture 18 - Mar. 28: Partially Observable Markov Decision Processes [Chapters 17.4]
- Lecture 19 - Mar. 30: Review of MDPs and POMPDs Markov Decision Processes [Chapter 17]
- Recitation 10: MDPs and POMDPs
- Lecture 20 - Apr. 4: Supervised Learning and Decision Trees [Chapters 18.1-18.2-18.3-18.4]
- Lecture 21 - Apr. 6: Decision Trees [Chapters 18.1-18.2-18.3-18.4]
- Recitation 11: Basic Principles of Machine Learning
- Lecture 22 - Apr. 11: Neural Networks [Chapters 18.7]
- Lecture 23 - Apr. 13: Non-parametric Models and Support Vector Machines [Chapters 18.8-18.9-18.10]
- Recitation 12: Principles of Supervised Learning
- Lecture 24 - Apr. 18: Review of Supervised Learning: Regression and Classification [Chapter 18]
- Lecture 25 - Apr. 20: Statistical Learning [Chapters 20.1-20.2]
- Recitation 13: Principles of Statistical Learning
- Lecture 26 - Apr. 25: Statistical Learning / Expectation-Maximization [Chapters 20.1-20.2]
- Lecture 27 - Apr. 27: Future Prospects of AI and Application Domains [Chapters 20.3]
- Recitation 14: Preparation for Final Exam 

[**Final Exam Schedule**](https://finalexams.rutgers.edu/)

##### Prerequisites

Courses:

- CS 205 Introduction to Discrete Structures I 

##### Reading Material

The class will primarily draw upon material from the following book:

- "Artificial Intelligence: A Modern Approach" by Stuart Russell and Peter Norvig (Third Edition), Prentice Hall Series in Artificial Intelligence

The slides presented during the lectures will cover a limited part of the material discussed in the classroom. The majority of the mathematical notions will be presented on the whiteboard. Students are expected to take notes during the presentation of the material in the classroom and the recitations. Homeworks, programming assignments and exams will be based on the presented material.

##### Exams

There will be 2 exams: one midterm and one final. The first exam will cover the material of the first half of the course (approx. first 14 lectures), and the final will cover the last 2/3rds of the course (there will be some overlap with the midterm). Check the tentative schedule for the date of the midterm. Both exams are in-class exams.

A missed exam draws zero credit. Emergencies will be considered upon submitting a University-issued written verification to the corresponding Instructor; for assistance contact your Dean's Office. Also, check the definition of [Final Exam Conflicts](http://sasundergrad.rutgers.edu/forms/final-exam-conflict) by SAS.

##### Assignments

There will be multiple assignments (either 4 or 5). You will be informed in advance when an assignment is due. Typically, each assignment will include opportunities for extra credit.

The assignments include practice questions which are intended to assist the student in mastering the course content. They will also involve programming AI algorithms and testing their efficiency. Typically you will be asked to submit an electronic version of your code, test runs, a typeset report and demo your project to the teaching assistants.

Assignments should be completed by teams of students - two at most. No additional credit will be given for students that complete a homework individually. Please inform the TAs about the members of your team. Students can switch teams between assignments but they are not required to. When the composition of a team changes, the students need to inform the TA.

Students will receive 10% extra credit if they typeset (in LaTeX) or 5% extra credit if they typewrite their answers (e.g., if a pair was to receive a score of 62/100 and they provide a typeset homework, then their score will be 68/100, i.e,. +10% of 62 points). Resources on how to use LaTeX are available on the course's  
website.

##### Submission Rules

No late submission is allowed. If you don't submit an assignment on time, you get 0 points for that homework/project. Students can submit their assignments electronically via Sakai. Programming results must be demonstrated during pre-scheduled demo appointments. The project report must be forwarded in advance of the demo.

##### Grading System

The final grade will be computed according to the following rule **(this is tentative and can change)**:

- Assignments: 50 points total (approx. 8 to 12 points each depending on difficulty)
- Midterm and Exam: 50 points (25 points each)
- Participation: up to 5 points (this is up to the discretion of the instructors and the TAs)

By default your participation grade is 0, i.e., if you frequently come to the lectures/recitations but you rarely answer questions during the lectures or the recitations, your participation grade will be 0. Positive participation grades will be given to students that actively participate in lectures and recitations. 

The mapping of scores to letter grades will be determined at the end of the semester. As a **rough** guide, the following rule may be used for the final grade **(it will be adapted close to the end of the semester)**:

- A: &gt; 89 
- B+: 80-89
- B: 70-79
- C+: 60-69
- C: 50-59
- D: 40-49
- F: less than 40

Students interested in a recommendation letter by the instructor will be offered one only if they achieve a score above 95 after the completion of the course.

##### Questions about Grading

If you have a question or complaint regarding the points you received on specific parts of an assignment, or an exam, submit a request to the TA, stating specifically but very briefly what parts of that assignment you wish to be reviewed. Please refrain from verbal arguments about grades with the instructor or with any of the TAs. We will try to get back to you soon. The deadline for submitting such requests is the last lecture.

##### Academic Standards

Exams are to be treated as individual efforts. Homeworks and projects are not to be treated as collective efforts beyond the participation of the team members! Discussions are not allowed on how to solve specific questions in homeworks between teams. Do not discuss assignments with students that are not currently taking the class.

A severe penalty will be given to any assignment which indicates collusion or cheating. The usual penalty for cheating on an assignment or an exam is failure in the course. At a minimum your grade in the corresponding exam/assignment will be reduced. Stealing another person's listing or having another person "ghost write" an assignment will be considered cheating.

Turning in work without properly citing the sources of the content included in your work is plagiarism. All kinds of sources are included in this definition, even those downloaded from the web, in which case an operable link must be cited. Plagiarism from the web or other sources is considered cheating and has similar effects to those mentioned above. Even with a reference, submitting an answer to a homework question, verbatim from any source and without any contribution on your part, draws zero credit.

You should carefully study the website of Rutgers University on [Academic Integrity](http://academicintegrity.rutgers.edu/), as well as the corresponding [policy](https://www.cs.rutgers.edu/academic-integrity/introduction) from the department of Computer Science. Your continued enrollment in this course implies that you have read these policies, and that you subscribe to the principles stated therein.

#### Latex Resources

General info on what you can do with LaTeX:  
[Getting Started with Latex](http://www.maths.tcd.ie/~dwilkins/LaTeXPrimer/)  
[The Not So Short Introduction to Latex](https://tobi.oetiker.ch/lshort/lshort.pdf)  
[Comprehensive List of Latex Symbols](http://tug.ctan.org/info/symbols/comprehensive/symbols-a4.pdf)  
[Latex for Logicians](http://www.logicmatters.net/latex-for-logicians/)

Mac  
[Tex on Mac OS X](http://ii2.sourceforge.net/tex-index.html)  
[MacTex](http://www.tug.org/mactex/)

The first link describes many alternatives that are available for installing Tex on a Mac. The second link forwards to the MacTex package, one of the alternatives mentioned in the first website. MaxTex provides everything that you need to use Latex on Mac except from a text editor. It is, however, compatible with a wide variety of popular editors (e.g., Alpha, BBEdit, Emacs, VIM, iTeXMac, TeXShop). Note that MaxTex is a large package.

Carbon Emacs has been succesfully tested with MacTex. After installing MacTex, it is possible to directly compile and view *.tex files from Carbon Emacs's UI.

Note for Mac users: You will probably have problems previewing your PDF output when using the postscript images provided by the instructor for developing the notes. Nevertheless, the PDF file can be printed properly. Prepare your document without the images and then add them. You will probably still be able to preview the intermediate .dvi output file with the "xdvi" program.

Linux (Ubuntu)  
[Latex on Ubuntu](https://help.ubuntu.com/community/LaTeX)  
[Tex Live](http://www.tug.org/texlive/)

You just have to download and install the proper packages described above (e.g., through apt-get), use your favorite editor (e.g., emacs) to prepare a *.tex file and then you compile (run at least two times: "latex filename.tex") to get the *.dvi output. You can go from dvi to postscript with the command "dvips" and you can convert postscript to pdf with the command "ps2pdf".

Windows  
[Latex for Windows help](http://faculty.smu.edu/barr/latex/)  
[MikTex (Latex for Windows)](http://miktex.org/)

If you follow the instructions on the first link you should be able to get it working on a Windows system.

You can find online Windows executables for the following programs (follow the order when installing): MiKTeX - Ghostscript - Ghostview - WinEdt.