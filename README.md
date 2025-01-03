java cDepartment of Electrical Engineering and Electronics
  ELEC362
Project DataViz version 0.4
   Module
  ELEC362
  Coursework name
  Software Development Project
  Component weight
  50%
  Semester
  1
  HE Level
  5
  Lab location
   personal computers/laptops, university remote computer
  Work
 Individual
  *Estimated time to finish
   40 hours (coding and testing)
  Assessment method
 Individually
  Submission format
   Online via VITAL
  Submission deadline
 23:59 on the 5th of January
  Late submission
   Standard university penalty applies
  Resit opportunity
 None except for extenuating circumstance
  Marking policy
  Marked and moderated independently
  Anonymous marking
  No
  Feedback
  via CANVAS
  Expected release of marks date
   15 business days from the deadline
  Learning outcomes
  LO2: Using C++ to implement GUI-based software. LO3: Using online documentation for self-learning.
 *Note: This estimate may vary based on the need to debug your application. Make sure you start working on the project as soon as possible.
Page 1 of 5

The concept:
The long term aim of the project is to develop a fully functional software, known as DataViz, for plotting and processing datasets, which will be eventually deployed and released for all students in the department to use in their reports, data processing, and as a show case of an authentic experience of software development for the students of ELEC362. The development is planned over 5 years, which started in 2022. Each year the cohort of ELEC362 will be asked to make a major upgrade to the software (will be referred to as the control version in this report).
Each header file of every class in the control version (source files) of the project contains a comment explaining what the purpose of the class is. The features currently available in the app can be found under “Help” menu.
Upgrades required for this year:
For this year you are asked to implement the following upgrades to DataViz 0.2 (the control version) to end up with DataViz 0.4:
Bugs to be fixed:
- Prevent the function feature from plotting a dataset that does not exist.
- Modify the code so when the name of a dataset is changed, the change in the name is
recognisable by the rest of the software.*
- Modify the code such that datasets generated by the function feature are treated similarly to
those generated by reading the dataset from a file.*
Note: A video will be published on CANVAS to show you how to induce these bugs. Features to be added:
  - - -
-
After -
-
If the user input a description of the dataset, that must be saved so that the next time they check it, it is still there. The description of the dataset must be saved.
Add new features to allow the user to set the label of the x-axis, the y-axis and their limits in a graph (only applicable to the XY plot only).
Create an entry “Interpolation” under the menu “Analysis”, which should allow the user to interpolate a dataset based on the x values of another dataset. Use the GSL function for this purpose.*
Add a feature to the app that allows exporting the graphs as an output of the app so that they can be used by the user in their work. For this purpose look at QCustomPlot documentation.
you are done with the upgrade; make sure that:
All the features you add are working well.
You updated the help window in the app to include instructions on how to use the app after the features you added.
You handled a range of potential errors/bugs that may be experienced in the updated app. Even if these errors/bugs are caused by a previous version of the app.
   -
 Page 2 of 5

It is an expectation from everyone to consult Qt documentation to find any functions or classes that might be useful for the implementation of the project. Finally, you should make the programme as professional as possible. Imagine this project as a real-life project given to you, and that in the next years, it will be developed further by other students.
Note for Mac OS users: You can develop the application based on Mac version of the app. The application will be tested and marked on a Windows machine. You should verify that your app works as it should on one of the computers in the lab before submission, to avoid any potential cross- platform issue, if you have any problems, please let me know.
Suggested approach to be followed:
Start by implementing the simplest tasks. For more advanced tasks, a good idea is to learn how to implement these features in an empty app. Once that works, you can adapt the code from the empty project into the control version. Note that is merely a suggestion and it has no impact on your mark whether you followed it or not.
Adding new features is simpler than addressing bugs, therefore it is a good idea to start with that.
If you are unsure contact the module coordinator for any assistance.
The deliverables
Every submission should consist of the project’s files in a zip file + the code written by you copied- pasted in a PDF file+ a filled assistant sheet form. The name of the zip file as well as the report must be your name (MohammadHasan.zip and MohammadHasan.pdf). The PDF file and the assistant sheet must not be zipped.
Industrial Relevance
Data visualisation and processing applications are essential tool in all fields of industry and academia, which apply to a代 写ELEC362、 C++
代做程序编程语言ll fields of science from physics, chemistry and engineering to social sciences. The tasks given in this project are essential part of famous software including:
    Note: The mark will be based on how your application behaves on a computer in the lab. Check your app on one of the computers in the lab to make sure it works as you expect before submitting your work. Make sure compiling your app is straightforward and does not need any special compilation instructions.
            Page 3 of 5

Questions and Answers:
Q: Should I learn the entire code in the control version?
A: No, you should be able using the material taught in this module to find the relevant part of the code where you need to edit, get familiar with that part to update it. You are not expected to know how everything works from the previous year.
Q: The control version has a lot of codes from elsewhere such as GSL, QCustomPlot, and ATMSP. Should I learn all of that?
A: No, you need to only know the bits that you need.
Q: What if I have a better idea than the control version? Or if I want to modify it?
A: Any improvement is welcome subject to the module’s coordinator approval. Please consult me before you start working on it. Note that this will not affect your marks as it will be only based on the features requested in this document.
Q: How will the markers know how my design works if there is no report?
A: By referring to the updated help window in the app. You should make sure that it is updated in such a way that reflects how the upgraded app should be used.
Q: What if I only did some of the features requested? Will my mark in the three marking criteria be affected?
A: Meeting all the requirements will primarily affect MC1. Some the requirements require more work than others, which were labelled with an asterisk *. Not doing these may impact other MC as well. If you want to prioritise a task, make sure you do the ones with asterisk first.
Q: For a higher mark, is it better do focus on doing few tasks excellently or to do all the task with some flaws?
A: You would get into a higher range of marks if you did many of the task excellently, rather than doing all the tasks with major flaws, as indicated in MC1. This reflects real life where an app with limited capabilities that works every time is better than an app that has a lot of features and keeps crashing. However, to get the highest possible mark do all the tasks to the best of your ability. The time planned for this, and the support available to you can help you achieve that.
Q: If I have a question on marking and assessment that is not addressed here or in the lectures, what should I do?
A: Please contact me, I am happy to address any enquiry.
Page 4 of 5

                       *Marking Criteria
  Criteria (weight %)
   What does it mean?
   Indicative characteristics
  Adequate / pass
(40%)
   Very good/Excellent
    Algorithm and design of the programme (40%)
  Are all the requested features met? Is the upgrade consistent with the previous design or is it completely different? Does the application handle memory efficiently?
    • The programme does what it designed to do with clear shortcoming.
• The use of memory is completely inefficient but is working.
• Many requested features are missing.
• The features added are very different from the style of the rest of the app.
 • The programme does what it designed to do without any flaws an in an efficient way
• The memory management is very efficient.
• Allrequestedfeatureswere added, and listed bugs were fixed.
• The design of the added features is so well integrated with the software, making upgrades for future release of the software straightforward.
      Code and GUI implementation (30%)
 Is the code well organised? Are the variables named properly? Is the code well commented? Does the code make good use of Object- Oriented Programming style? Is the GUI user friendly?
   • It is difficult to understand what the code does.
• Poorly commented code.
• Thecoding /commenting style is different from the original code.
• Layout of the GUI is not set.
• Classes are poorly used or not used at all.
• The added features work but not consideration was given to the user experience.
  • The code is written in very organised way that is easy to follow.
• The code is very well documented.
• The coding/style of the added feature is very similar to the original code.
• The GUI is very easy to work with.
• The data structure used are the most appropriate for the purpose they are used for.
• The code is structured in terms of classes and uses multiple aspects of OOP paradigm.
• Proper consideration for the user experience is given.
    Verification and Error-Handling (30%)
   Has the application been validated and verified? What does the programme do if there is a run-time error?
     • Theapplicationwas tested for one case only.
• Theapplication contains minimal error handling.
• Error messages are not helpful.
   • The application has been thoroughly tested.
• Error handling has been done professionally for at least 3 potential run-time errors/bugs.
• Error messages are meaningful.
 *If you have a feedback query after the marks are released, make sure you contact me within a week, after that the marks are finalised and sent to the Student Support Office.
Page 5 of 5

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
