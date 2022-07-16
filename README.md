# CMSC388J: Building Secure Web Applications with Python and Flask (Fall 2022)

![](https://raw.githubusercontent.com/UMD-CS-STICs/CMSC388J-f20/master/flask-logo.png)

This course is an introduction to building secure, full-stack web applications with Python and Flask.
We'll start with Python and Flask, and then subsequent weeks will cover how to add Flask extensions
to your applications to implement common web app functionalities, how to protect your website from bad actors,
and more! At the end of the course, you'll be able to deploy your app for the world to see.

*Disclaimer: The syllabus is subject to change throughout the course of the semester.*

## Course Details
- **Lecture Time**: Fridays @ 11:00-11:50 AM
- **Location**: CSI 2107
- **Textbook**: No textbook, all materials are provided and documentation is online

## Staff
- **Course Facilitators**:
    - Alexander Liu (aliu4131@terpmail.umd.edu)
    - Pace Ockerman (pace@terpmail)
    - Shrikar Vasisht (svasisht@terpmail)
- **Faculty Advisor**:
    - Michael Marsh

### Contact
Email and Discord contact information are listed on ELMS.

Please use [Discord](https://discord.com/) as your primary communication with us; we'll get back to you the
fastest there. Invite links to the class server will be sent out to each student the beginning of the semester.

If you are unable to use Discord, then email us; if you are
emailing one of the facilitators, make sure to CC the others. Additionally, please include
`[CMSC 388J]` at the start of your subject line so we don't accidentally ignore your email.

## Office hours
[TO BE DETERMINED]

## Topics Covered [TO BE REVIEWED]
- Python
  - Variables, expressions, operators
  - Iterations, conditionals, collections
  - Functions
    - As first-class objects
    - Decorators
  - "Main" function
  - Built-in functions
- Web Application Security
  - Cross-site scripting (XSS)
  - Cross-site request forgery (CSRF)
  - SQL injections
  - Man-in-the-Middle attacks (MitM)
  - Token & Two-factor authentication
- Flask
  - Routing your web app
  - Templating
  - Adding extensions for more features
    - WTForms
    - Talisman
    - Login
    - Creating your own
  - Logging
  - User Management
  - Blueprints
- HTML/CSS/JS
  - Bootstrap
  - Integrating other frameworks
  - Custom CSS/JS configuration
- Databases
  - MongoDB
- Payments Integration
  - Stripe (possibly others, we're open to suggestions)
- App Deployment
  - Heroku
  - Python Anywhere
  - *Possibly*: Google App Engine, AWS
- Version Control
  - Git

## Schedule [TO BE REVIEWED]
| Week | Date  | Topic                                           | Assignment                                      |
| ---- | ----- | ---------------------------------------------- | ----------------------------------------------- |
| 1    | 9/2   | Intro to Python                                | P1 assigned                                     |
| 2    | 9/9   | Flask Intro                                    | P1 due, P2 assigned, Quiz 1 assigned: weeks 1-2 |
| 3    | 9/16  | Forms, CSRF                                    | Quiz 1 due                                      |
| 4    | 9/23  | Databases, Injection Attacks                   | P2 due, P3 assigned, Quiz 2 assigned: weeks 3-4 |
| 5    | 9/30  | User Management                                | Quiz 2 due                                      |
| 6    | 10/7  | Bootstrap & more                               | P3 due, P4 assigned, Quiz 3 assigned: weeks 5-6 |
| 7    | 10/14 | In-depth CSS & JS*                             | Quiz 3 due                                      |
| 8    | 10/21 | None - break week                              | P4 due                                          |
| 9    | 10/28 | Extensions, Logging, App Factories, Blueprints | P5 assigned                                     |
| 10   | 11/4  | HTTP Headers & Talisman                        | Quiz 4 assigned, weeks 7-10                     |
| 11   | 11/11 | Two-Factor Authentication                      | P5 due, Quiz 4 due, Final Project assigned      |
| 12   | 11/18 | Some Useful Python Packages                    | Proposal due, Quiz 5 assigned, weeks 11-12      |
| 13   | 11/25 | THANKSGIVING BREAK                             |                                                 |
| 14   | 12/2  | Deploying your app                             | Quiz 5 due                                      |
| 15   | 12/9  | Payments with Stripe*                          |                                                 |
| 16   | 12/?? | None - finals week                             | Final Project due                               |

* See **Flexible Schedule** section below

### Flexible Schedule [TO BE REVIEWED]
Weeks 7 and 14 will have a main topic of discussion, but during these weeks, we'll also try
to teach topics requested by the students. So if you guys feel like you need more info about
a certain topic or just want to learn a new idea altogether, let us know, and we'll try to add it in.

We'll send out information on how you can let us know; surveys will probably be conducted anonymously on ELMS.

## Lectures
Lectures will be recorded and posted on ELMS along with the lecture slides. Attendance is encouraged but not mandatory.

## Quizzes
We will be assigning quizzes on ELMS to make sure you are keeping up with the material you need
in order to complete the projects. They will be assigned after their topics are covered in class
and due the following **Thursday at 11:59 PM** unless stated otherwise.

You will get only **one** attempt per quiz, but there is no time limit.

## Projects
Projects are due at **11:59 PM** on their due date, barring any extensions. Not all of
the projects will have tests; they may be graded according to a rubric 
which will be provided in advance. All projects must be submitted online via ELMS.

### Final project
The final project will use everything you have learned in class before and will require you
to build a Flask web application from scratch and deploy
the app on a hosting platform. Requirements for the final project will come out
towards the end of the semester.

## Grading [TO BE REVIEWED]
Grades will be maintained on ELMS. Your final course grade will be determined according to the following
percentages:

| Percentage | Title         | Additional Info                   |
| ---------- | ------------- | --------------------------------- |
| 10%        | Quizzes       | All quizzes are weighted equally. |
| 55%        | Projects      | [INSERT BREAKDOWN BY PROJECT]     |
| 35%        | Final Project |                                   |

Any regrade requests must be submitted
no more than **one week** after the grade is posted. No requests will be considered afterwards.

### Robustness
If we perform any typical user actions on the website (e.g., clicking on links, navigating to
different parts of the website using links, navigating to different parts of the website with direct URLs)
and this causes a crash (a Flask error shows up on screen or the app crashes),
then you may lose **up to 50%** of your final score for the project, depending on the severity of the error.

An example of a small error: syntax error in a Jinja template. 

An example of a large error: a view function not being configured properly.

### Late Policy
Projects and Quizzes may be submitted up to **3 days** late for **10%** off your earned grade 
**per day** (for a total of 30% off). After this, you will receive a **0%**. There are no exceptions
unless you've talked with us beforehand or provide a valid excuse.

For each project, the highest score you get on it, counting **all** late and on-time submissions,
will be your grade for that project.

## University Policies
### COVID-19 Guidance

[TO BE DETERMINED]

### Excused Absence and Academic Accommodations
See the section titled "Attendance, Absences, or Missed Assignments" available at
[Course Related Policies](http://www.ugst.umd.edu/courserelatedpolicies.html).

### Disability Support Accommodations
See the section titled "Accessibility" available at
[Course Related Policies](http://www.ugst.umd.edu/courserelatedpolicies.html).

### Academic Integrity
Note that academic dishonesty includes not only cheating, fabrication, and
plagiarism, but also includes helping other students commit acts of academic
dishonesty by allowing them to obtain copies of your work. In short, all
submitted work must be your own. Cases of academic dishonesty will be pursued to
the fullest extent possible as stipulated by the
[Office of Student Conduct](http://osc.umd.edu/OSC/Default.aspx).

It is very important for you to be aware of the consequences of cheating,
fabrication, facilitation, and plagiarism. For more information on the Code of
Academic Integrity or the Student Honor Council, please visit
http://www.shc.umd.edu.

# Course Evaluations
If you have a suggestion for improving this class, don't hesitate to tell the
instructor or facilitators during the semester. At the end of the semester, please don't
forget to provide your feedback using the campus-wide CourseEvalUM system. Your
comments will help make this class better.
