---
layout: page
title: Project Details
permalink: /project/
---

## Project Specs

Project Module Specifications:
 - [Registration System](/project/REGS-2023.docx)
 - [Advising System](/project/ADS-2023.docx)
 - [Application System](/project/APPS-2023.docx)


## Phase 1 


**Timeline**
 - March 22: Project / Teams assigned
 - March 25: Stakeholder Questions due (max 5)
 - March 29: Mentor check-in
 - April 5: Phase 1 initial demo
 - April 12: Phase 1 DUE in class
 - April 17: Phase 1 Report due 11:59PM

**Mentor Status Checks**
  - At each status check we will check your progress and check your progress so far, the clarify of your plan for next steps, and how well your team is working together.

**Approximate Phase 1 Grading Rubric:** This is not the final grading rubric, but it gives you an idea what to expect:
  - 30% - Evidence that you are making progress each week and contributing your share of the project (based on weekly checkins, trello board, and git log)
  - 10% - Project report including ER or Schema Diagram
  - 55% - Complete functionality
  - 5% - Overall usability / look and feel (this will have higher weight in phase 2)

**Phase 1 Demo:** Full details of the Demo [are listed here](/project/phase-1)

**Phase 1 Project Report:** Your phase 1 report should include:
  - An ER or SQL Table Diagram updated to reflect your final design
  - An explanation for what normal form you believe your tables meet
  - A short justification of your key design choices (0.5 - 1 page)
  - A list of assumptions made for your design
  - A list of missing functionality from your final implementation
  - A work breakdown describing the key responsibilities of each team member
 
Your report must be committed and pushed to your repository by 11:59PM on Monday April 17th. It should be in a file named `Readme.md` or `Readme.pdf` in the `main` branch. 


## Phase 2 

You will be working on **one** of these two types of projects:

Type 1 Builder:
 - Implement a simplified version of the REGS component
   - You are not required to implement the Sys Admin or Grad Secretary roles described in the REGS spec. Instead of the Grad Secretary, you should allow Faculty users to change grades multiple times. 
   - If the spec for your component talks about extra features to add in phase 2 (such as more reports or PhD students), you *do not* need to complete them.
   - You are still expected to add something "extra" to your project - a new feature, a nicer UI, or some technical extra. However, this will be a smaller part of your grade compared to the Integration projects.

Type 2 Integration:
 - Combine the components implemented by your teammates in phase 1 (do not build any new components from scratch)
 - Check the spec for your component and include any extra features specified there (such as more reports for REGS)
 - 2 person integration teams are not required to support PhD students, but otherwise should support the full specs of the components they are combining

**Both Types:**
 - We expect you to create a better looking and more usable website compared to phase 1
 - A portion of your grade will be based on any "extra features" you complete that go beyond the spec
 - The most impressive projects will be added to this website's [Hall of Fame](/hall). Check [last year's](https://cs2541-21s.github.io/hall/) for some inspiration.

### Phase 2 Demo
Details of the [phase 2 demo are here](/project/phase-2).

### Phase 2 Project Report
You must submit a short written report about your project containing the following sections:
  - **DB Design:** An ER or SQL Table Diagram updated to reflect your final design and an explanation for what normal form you believe your tables meet
  - **Visual Overview:** Include screenshots, an animated gif, or short video showing a feature from each component included in your project (eg APPs, REGs, ADV). It does not need to be an exhaustive video of your functionality, just enough to remind us of how it works/looks.
  - **Design Justification:** For Integration projects this should focus on how you connected your components together. For Builder projects it should justify your key design decisions. (0.5 - 1 page)
  - **Special Features**: ~2 sentences describing each extra feature you added beyond the spec
  - **Work Breakdown**: List teammates and specify the aspects of the project they worked on


Your report should be submitted as a file named  `final-report.md` or `final-report.pdf` in your repository.

Your report is due by 11:59pm Friday May 5th (earlier if possible!). If you submit your report *after* you do your demo, please create an issue and tag `@semajrolyat` to notify us for grading.

### Phase 2 Grading
Each team will need to schedule a grading appointment on May 4th or May 5th. 

During your appointment we will walk through a script to test your application similar to phase 1. We will also be asking you deeper questions about your project's design and implementation. After we test your basic functionality you will have a chance to show off any extra features you added.

**Approximate Grading Rubric:** This may not be the final grading rubric, but it gives you an idea what to expect:
  - 30% - Evidence that you are making progress each week and contributing your share of the project (see below)
  - 10% - Project report
  - 40% - Complete functionality
  - 15% - Overall usability / look and feel
  - 5% - Extra features of your choice (judged based on difficulty and innovativeness). Truly amazing extra features may earn additional bonus points.

Note that not all teammates are guaranteed to get the same grade. Your grade will be adjusted based on your contribution to the project as measured by git commits, mentor status checks, team member surveys, and your ability to answer questions about your project.


---
## AWS / Python / SQL Tips
---

### Help Using AWS / VS Code
My videos:
 - [AWS RDS: How to setup MySQL](https://youtu.be/cL8u9mMCJsQ)
 - [VS Code: MySQL extension](https://youtu.be/1FSHAsP20cg)
 - [Python Virtual Environments / Installing libraries](https://youtu.be/7CGtFr0XYE8)
 - [Python + MySQL](https://youtu.be/53ToK78EsmU)
 - [MySQL vs SQLite](https://youtu.be/dYzSWSMD3Tk) and [sample code git repo](https://github.com/cs2541-22s/flask-sample-mysql)

Docs:
 - [VS Code Guide](https://docs.google.com/document/d/1tKK1miWh-AS9Q-j2JwAACkYMEsM8eGICDMhSWYCwQ4o/edit?usp=sharing)
 - [VS Code's Flask Tutorial](https://code.visualstudio.com/docs/python/tutorial-flask) - Great info on using flask, the VS Code debugger, etc.

### Feeling Behind in Python / Flask / SQL?
Watch these videos to catch up.  You will need to log into LinkedIn using your GW account to get access. The videos are quite well done and a pretty efficient way to learn these technolgoies.
  - [Python Essential Training](https://www.linkedin.com/learning-login/share?account=74651410&forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fpython-essential-training-2%3Ftrk%3Dshare_ent_url%26shareId%3DckSZUbeWRW6TasHVFkr3Eg%253D%253D) - overview of core python concepts and syntax
  - [Flask Essential Training](https://www.linkedin.com/learning-login/share?account=74651410&forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fflask-essential-training%3Ftrk%3Dshare_ent_url%26shareId%3Dr5AlZEacSFy5yqntXYf54Q%253D%253D) - covers routes, forms, and templates
  - [Programming Foundations: Databases](https://www.linkedin.com/learning-login/share?account=74651410&forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fprogramming-foundations-databases-2%3Ftrk%3Dshare_ent_url%26shareId%3Dz9N5keEoQy2IR25xhNCn6g%253D%253D) - this is mainly on principles of databases, but Chap 5 overviews SQL

### Flask / SQL Examples

Here are some python examples to help with features in Python, Flask, and SQL.

  - [Flask sessions](https://repl.it/@twood02/SessionTest#main.py)
  - [How to pass data between pages in Flask](https://replit.com/@twood02/flaskdata)
  - [Processing multiple forms with one route](https://repl.it/@twood02/MultipleFormExample#main.py) - by Ryan Hudson
  - [Flask Static files, templates, and inheritance](https://replit.com/@twood02/Multiple-Templates-Static-Files-Inherited-Templates) - by Sam Fritz
  - [Using Autogenerated IDs](https://replit.com/@twood02/Flask-SQLite-autoincrement-example) - by Julia Showl

TODO: (Submit a link in #engage to your solution. Solutions should not be directly related to the HW/project)
  - Multi-file Flask app - show how to break a flask web app  with routes stored in different files. The app should show how to share some app configuration data so it can be accessed from routes in both files
  - SQLite create table example - submit a sqlite Repl with a script to 1) create two tables which include foreign keys, 2) insert some data, 3) select some data using a join
  - If you have an idea for a useful example that would help current and future students (without giving away solutions), then message me to suggest it.
