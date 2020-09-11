# Python-for-Earth-Scientists
This repository consists of a series of Python lessons. Lessons emphasize Earth Science concepts, but are applicable to anybody looking to learn the Python programming language. These lessons assume no prior coding experience. Therefore, they are accessible to everybody!

This repository contains the materials for seven lessons. These lessons go through basic Python concepts as they relate to Earth Science applications. They are designed to give users a baseline working knowledge of Python, which they can expand upon. Each lesson consists of the a Jupyter Notebook (Python_ES_L#.ipynb). Cells within each Jupyter Notebook contain annotated instructions explaining their use and their context. Because these lessons were created in support of the NASA Student Airborne Research Program (NASA SARP), each lesson contains a lecture video. Youtube links of the lecture videos are included in this readme document. However, please keep in mind that because lecture videos may not overlap completely with Python Notebooks and notebook file names are named differently in youtube lectures than they are in this repository. This also repository includes all supporting files that are necessary to run lesson plans. Supporting files include: demo1.txt, demo2.txt, WHARFDATA_2017.csv, and WU_2017.zip.

Please know that Python is an expansive programming language with near infinite applications. Thus, these lessons are by no means an exhaustive.

Course Syllabus:

Lesson 1
Topics: types of variables, basic mathematical opperations, introduction to for-loops
Required Files: Python_ES_L1.ipynb
Lecture: https://www.youtube.com/watch?v=dhiNT-yUZ2g&feature=youtu.be
Synopsis: Lesson 1 assumes no prior experience coding in ANY PROGRAMING LANGUAGE. Here we focus on types of python variables, including variables designed for data strorage. We also examine how to format code correctly, as well as how to create a basic for-loop. Please note, this particular Python Notebook was created AFTER the first lesson. However, the notebook does follow the basic concepts presented in Lesson 1.

Lesson 2
Topics: for-loops, dictionaries, and conditional statements
Required Files: Python_ES_L2.ipynb
Lecture: https://www.youtube.com/watch?v=vQuEvcvHpKE&feature=youtu.be
Synopsis: Lesson 2 expands on the basic concepts of for-loops and variable types. Students learn how to create more complex for-loops and how to add conditional statements to for-loops (as well as the reasons for doing so). Students are also familiarized with dictionaries and how they can be used to store data efficiently.

Lesson 3
Topics: writing ascii files, user-defined functions
Required Files: Python_ES_L3.ipynb
Lecture: https://www.youtube.com/watch?v=NJmJlxPaZ6g&feature=youtu.be
Synopsis: Lesson 3 explains how data can be written into an ascii file for storage outside of the Python Environment (e.g. Jupyter Notebooks). Lesson 3 also introduces students to the concept of user-defined functions. These functions are written by users and can be called upon in multiple portions of the code. They are advantageous in that they obviate the need to write the same sequence of coding lines multiple times throughout a script.

Lesson 4
Topics: reading ascii files into dictionaries
Required Files: Python_ES_L4.ipynb
Lecture: https://www.youtube.com/watch?v=X1hgekvoJLM&feature=youtu.be
Synopsis: Lesson 4 goes over techniques for reading ascii files into the Python Environment (as dictionaries). The lesson gives advice on creating user-defined functions that can be used repeatedly, hence obviating the need for repeating code.

Lesson 5
Topics: Reading multiple ascii files using a for-loop, Data Quality Assurance/Quality Control (QA/QC), basic plotting
Required Files: Python_ES_L5.ipynb, WU_2017.zip (Recommended: unzip prior to commencing Lesson 5)
Lecture: https://www.youtube.com/watch?v=Gcsc7ub3GLA&feature=youtu.be
Synopsis: Now that students understand how to read an ascii file, as well as how to write a for-loop, this lesson comblines those skills. Students will write a for-loop that will read 366 ascii files into a dictionary (one file at a time). Students will then examine techniques for eliminating erroneous data points; they will also be introduced to plotting, which can be used as a visual aid for locating problematic data points.

Lesson 6
Topics: Basic statistics
Required Files: Python_ES_L6.ipynb, WHARFDATA_2017.csv
Lecture: https://www.youtube.com/watch?v=6AI5sbos0fQ&feature=youtu.be
Synopsis: Lesson 6 demonstrates how to perform basic data analysis: least-squares, linear regression, as well as calculating mean, median, and standard deviation.

Lesson 7
Topics: Debugging your code
Required Files: Python_ES_L7.ipynb, WHARFDATA_2017.csv
Lecture:
    Part 1: https://www.youtube.com/watch?v=dlFF1F2lbQU&feature=youtu.be
    Part 2: https://www.youtube.com/watch?v=FDleqRH_my4&feature=youtu.be
    Part 3: https://www.youtube.com/watch?v=cTbGYHLgiwo&feature=youtu.be
Synopsis: Lesson 7 lays forth some techniques for locating and correcting coding errors. Students are prompted to run several scripts that contain errors and to then identify and correct these errors. The final assignment is a user-defined function that is riddled with programming errors. Students will run the code and fix these errors one by one. Keep in mind however, that not all coding errors prevent a script from running. In fact, the most dangerous kind of coding errors are those that do not prevent the code from running, but instead change the nature of the program without the user realizing it! 
