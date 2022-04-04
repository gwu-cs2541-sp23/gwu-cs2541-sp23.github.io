---
layout: page
title: Project Details
permalink: /project/
---

## Project Specs

Project Module Specifications:
 - [Registration System](/project/REGS-2022.docx)
 - [Advising System](/project/ADS-2022.docx)
 - [Application System](/project/APPS-2022.docx)


## Phase 1 


**Timeline**
 - March 9: Project / Teams assigned
 - March 23: Mentor Check In
 - March 30: Phase 1 initial demo
 - April 6: Phase 1 DUE in class
 - April 11: Phase 1 Report due 11:59PM

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
 
Your report must be committed and pushed to your repository by 11:59PM on Monday April 11th. It should be in a file named `Readme.md` or `Readme.pdf` in the `main` branch. 


## Phase 2 Project Types

You will be working on **one** of these two types of projects:

Type 1 Builder:
 - Implement REGS or APPS component (whichever you were assigned)
   - APPS: No PhD apps or Sys Admin role required
   - REGS: No user creation, no PhD students, no Sys Admin required
   - If the spec for your component talks about extra features to add in phase 2 (such as more reports for REGS), you *do not* need to complete them.

Type 2 Integration:
 - Combine the components implemented by your teammates in phase 1 (do not build any new components from scratch)
 - Check the spec for your component and include any extra features specified there (such as more reports for REGS)
 - 2 person integration teams are not required to support PhD students, but otherwise should support the full specs of the components they are combining

**Both Types:**
 - We expect you to create a better looking and more usable website compared to phase 1
 - A portion of your grade will be based on any "extra features" you complete that go beyond the spec
 - The most impressive projects will be added to this website's [Hall of Fame](/hall). Check [last year's](https://cs2541-21s.github.io/hall/) for some inspiration.

{% comment %}

### Project Report
You must submit a short written report about your project containing the following sections:

  - **Project Pitch**: ~2 paragraphs describing your overall project to someone who knows nothing about it. Include a representative screenshot (or animated gif) of your site.
  - **Special Features**: ~2 sentences describing each extra feature you added beyond the spec
  - **DB Schema**: Show schema for 2-3 tables and justify your design. You should focus on the most important/interesting aspects (2-3 paragraphs)
  - **Work Breakdown**: List teammates and specify the aspects of the project they worked on

Your report should be submitted as a file named  `report.md` in your repository.

Your report is due by 3pm Tuesday May 11th (earlier if possible!). If you submit your report *after* you do your demo, you must create an issue and tag `@twood02` to notify us for grading.

### Phase 2 Grading
Each team will need to schedule a grading appointment between May 4 - May 11th. *Not all teams will be able to delay until the 11th!*

During your appointment we will walk through a script to test your application similar to phase 1. We will also be asking you deeper questions about your project's design and implementation. After we test your basic functionality you will have a chance to show off any extra features you added.

You will also need to submit a short report about your project's design. Details will be added here soon.

**Approximate Grading Rubric:** This is not the final grading rubric, but it gives you an idea what to expect:
  - 30% - Evidence that you are making progress each week and contributing your share of the project (see below)
  - 10% - Project report
  - 40% - Complete functionality
  - 10% - Overall usability / look and feel
  - 10% - Extra features of your choice (judged based on difficulty and innovativeness)

Note that not all teammates are guaranteed to get the same grade. Your grade will be adjusted based on your contribution to the project as measured by git commits, mentor status checks, team member surveys, and your ability to answer questions about your project.
{% endcomment %}

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