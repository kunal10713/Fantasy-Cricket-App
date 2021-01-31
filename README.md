# Fantasy-Cricket-App
### 1. INTRODUCTION TO PYTHON

#### 1.1.Python Language Introduction:

Python is a widely used general-purpose, high level programming language. It was initially designed
by Guido van Rossum in 1991 and developed by Python Software Foundation. It was mainly
developed for emphasis on code readability, and its syntax allows programmers to express concepts
in fewer lines of code.

Python is a programming language that lets you work quickly and integrate systems more efficiently.

Python is a high-level, interpreted, interactive and object-oriented scripting language. Python is
designed to be highly readable. It uses English keywords frequently where as other languages use
punctuation, and it has fewer syntactical constructions than other languages.

  #### a) Python is Interpreted:
  Python is processed at runtime by the interpreter. You do not need to
compile your program before executing it. This is similar to PERL and PHP.
  #### b) Python is Interactive:
You can actually sit at a Python prompt and interact with the interpreter
directly to write your programs.
  #### c) Python is Object-Oriented: 
Python supports Object-Oriented style or technique of programming
that encapsulates code within objects.
  #### d) Python is a Beginner's Language:
Python is a great language for the beginner-level programmers
and supports the development of a wide range of applications from simple text processing to WWW
browsers to games.

#### 1.2.History of Python:

 Python was developed by Guido van Rossum in the late eighties and early nineties at the National
Research Institute for Mathematics and Computer Science in the Netherlands.
Python is derived from many other languages, including ABC, Modula-3, C, C++, Algol-68,
SmallTalk, and Unix shell and other scripting languages.
Python is copyrighted. Like Perl, Python source code is now available under the GNU General Public
License (GPL).

Python is now maintained by a core development team at the institute, although Guido van Rossum
still holds a vital role in directing its progress.

### 2. PYTHON FEATURES:
Python's features include −

  #### 1. Easy-to-learn − 
Python has few keywords, simple structure, and a clearly defined syntax.
This allows the student to pick up the language quickly.

  #### 2. Easy-to-read − 
Python code is more clearly defined and visible to the eyes.

  #### 3. Easy-to-maintain − 
Python's source code is fairly easy-to-maintain.

  #### 4. A broad standard library − 
Python's bulk of the library is very portable and cross-platform
compatible on UNIX, Windows, and Macintosh.

  #### 5. Interactive Mode − 
Python has support for an interactive mode which allows interactive
testing and debugging of snippets of code.

  #### 6. Portable − 
Python can run on a wide variety of hardware platforms and has the same interface
on all platforms.

  #### 7. Extendable − 
You can add low-level modules to the Python interpreter. These modules
enable programmers to add to or customize their tools to be more efficient.

  #### 8. Databases − 
Python provides interfaces to all major commercial databases.

  #### 9. GUI Programming − 
Python supports GUI applications that can be created and ported to
many system calls, libraries and windows systems, such as Windows MFC, Macintosh, and
the X Window system of Unix.

  #### 10. Scalable − 
Python provides a better structure and support for large programs than shell
scripting.

      a. Apart from the above-mentioned features, Python has a big list of good features,
few are listed below −

      b. It supports functional and structured programming methods as well as OOP.

      c. It can be used as a scripting language or can be compiled to byte-code for building
large applications.
       d. It provides very high-level dynamic data types and supports dynamic type
checking.
       e. IT supports automatic garbage collection.
       f. It can be easily integrated with C, C++, COM, ActiveX, CORBA, and Java.
      
### 3. TRAINING CONTENTS:

  #### 3.1. Introduction to Python
Learn how to install Python, distinguish between important data types and use basic features of the
Python interpreter, IDLE.
  #### 3.2.Using Variables in Python
Learn about numeric, string, sequence and dictionary data types and relevant operations while
practicing Python syntax.
  #### 3.3.Basics of Programming in Python
Learn how to write programs using conditionals, loops, iterators and generators, functions and
modules and packages.
  #### 3.4.Principles of Object-oriented Programming (OOP)
Learn about the important features of Object-oriented Programming while using Classes and
Objects, two main aspects of the OOP paradigm.
  #### 3.5. Connecting to SQLite Database
Learn about relational databases while learning how to store and retrieve data from an SQLite
database through Python.
  #### 3.6.Developing a GUI with PyQT
Learn how to install PyQt5 toolkit, Qt Designer and create a graphical user interface using common
widgets and menu systems.
  #### 3.7.Application of Python in Various Disciplines
Learn about various resources to extend your learning for the Python programming language.

### 4. PROFILE OF THE PROBLEM
Create a Fantasy Cricket game in Python. The game should have all the features displayed in
the mock-up screens in the scenario. To calculate the points for each player, we can use
rules similar to the sample rules displayed below.
Sample of Rules:
#### Batting:
  ● 1 point for 2 runs scored

  ● Additional 5 points for half century

  ● Additional 10 points for century

  ● 2 points for strike rate (runs/balls faced) of 80-100

  ● Additional 4 points for strike rate>100

  ● 1 point for hitting a boundary (four) and 2 points for over boundary (six)

#### Bowling:
  ● 10 points for each wicket

  ● Additional 5 points for three wickets per innings

  ● Additional 10 points for 5 wickets or more in innings

  ● 4 points for economy rate (runs given per over) between 3.5 and 4.5

  ● 7 points for economy rate between 2 and 3.5

  ● 10 points for economy rate less than 2

#### Fielding
  ● 10 points each for catch/stumping/run out

### 5. DATABASE DESIGN
For the database, we are required to use three tables – match, stats and teams.
#### 5.1. Match1
*Run Out
#### 5.2. Team
name players
#### 5.3. Stats
player
matches
runs 
100s
50s 
value
ctg


### 6. Testing and Deployment:
1. Opening screen of the application. You can see the players of each category by selecting the
category. To begin with, the selection is disabled until a new team is created from the Manage
Teams menu. A pop up asking the name of the team appears.
2. The toolbar menu options which allow you to create a new team, open an existing team, save
your team and finally evaluate the score of a saved team.
3. After clicking New Team, the left box is populated with player names. As you select a different
category, the corresponding list of players is displayed.
4. On double-clicking each player name, the right box gets populated. Points available and used
are displayed accordingly.
5. Message if the game logic is not followed
6. Upon opening the second file to evaluate the scores. You can select your team here and the
match for which the players' performance is compared.
7. The final score for your fantasy team based on the match selected.
6.4.Gantt Chart
6.5.Problem Analysis
#### PRODUCT DEFINATION: 
It is a game where you create a team of real cricket players and score
points depending on how your chosen players perform in real life matches. To win a tournament,
you must try and get the maximum points and the No. 1 rank amongst other participants.

#### FEASIBILITY ANALYSIS: 
I am building a software for gaming purposes using an specific
technology named python. It is a game software where you can create virtual team according to
your choice and score points to win a tournament.
This software is created for motivating street cricket and adding more fun and entertainment to
cricket. The components that are used in this demo can be integrated to a high extent to provide
statics to different components of cricket. This project helps in providing real time on field actions
there by helping its user of the current actions happening on field.



### 8. RESULT
• The final score for your fantasy team based on the match selected will be displayed.
• An interactive GUI was created for better user experience
### 9. FUTURE SCOPE
Python programming language, to be the most promising career in technologies, industry.
Opportunities in the career of python are increasing tremendously in the world. Since Python has
simple codes, faster readability capacity, significant companies are in demand in python language.
Python to be an excellent tool in designing progressive ideas. Candidates interested in python
increases every day. In future more development can be done for this application with making the
interface more attractive and by deploying the app on online plateforms.
