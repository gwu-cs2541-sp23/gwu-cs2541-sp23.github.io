---
layout: page
title: Phase 1 Submission Details
permalink: /project/phase-1
---

Please follow the instructions below carefully. Failure to follow these instructions may result in your project not being graded completely. **Your system must be populated with "starting state data" specified at the end of this document – this is a requirement for the project.**

On the Phase 1 due date by the start of class you will need to submit (1) your source code on Github (2) a GitHub Issue to be referred to during the demo that provides the following information (which we will need to conduct our testing): 
  - Specify the roles of the team members – i.e.,  specify who did what (which modules were implemented by whom etc.). 
  - Start one copy of your fully functional project. 
  - Provide us with the usernames and passwords for the different users in the system defined below (i.e., the Grad Sec –GS  role, faculty reviewer, CAC, sys admin, applicants).  
  - **YOU MAY NOT MAKE ANY EDITS TO YOUR CODE AFTER CLASS STARTS!**

## Schedule and Evaluation of Demos
The demos will be conducted during the Wednesday Lecture session from 12:45pm—3:25pm. 
  <!-- - Each team will be assigned a time slot (and an evaluator)– your team must be ready with your main webpage open and running. You should join the class Zoom and enter your group's breakout room 10 minutes before your start time. IF the previous team demo is running significantly beyond its scheduled time, we will notify you on slack and/or email. -->
  - ALL team members have to be present for the demo -- questions will be asked of all team members. Failure to attend the demo without prior approval will result in a grade of zero for your Phase 1 -- no exceptions.
  - The project testing/demo will require you to go through the entire workflow of your system, and we will be testing it for correctness and completeness. We will take you through specific steps and you are required to follow our directions. (This implies that you cannot come up with your own "script" for demo-ing your system.)
  - Your system must work correctly, and must meet all the workflow requirements that were specified. So make sure you get the system working correctly and make sure you do a lot of error checking and testing.
  - Bells and whistles are not required at this point in the project. So focus on getting the basic applications working for now, and if time permits you can work on improving the visuals or style. 

## Design Questions
After we test the functionality of your application, we will ask you a few questions about your design. Since we want all team members to have basic knowledge of all aspects of the project, questions will be directed to a specific team member, and others should not answer (even if they were the person who wrote that code). You should be able to give a clear answer, and point us to relevant code as needed.

Some example questions are:

REGS
  - What errors do you check for when students register for classes? How do you check for those errors?
  - When a user logs in, what do you store in your session and why?

{% comment %}
  - When a graduate student ultimately graduates, could you foresee an easy way to change a parameter in your database that identifies such change?
  - How do you store a user's permissions/roles in your database, and where are some of the places where it is important to identify their permissions?
  - How are student's grades handled? How do you convert letter grades into an official GPA for your transcript
  - How do you format a student's schedule of courses? Is this a long-term solution? Could this algorithm apply to classes that have a non-standard time block. How do you store a student's schedule in your database?
  - On login, what information did you find important to store within session variables?
{% endcomment %}

ADS
 - How did you choose to store different users in your database and why? (i.e. are “students”, “faculty”, etc. their own tables?)
 - When a user logs in, what do you store in your session and why?

{% comment %}
 - How did you choose to store advisor-advisee relationships in your database and why?
 - How did you choose to perform the Form 1 audit?
 - Are you storing a student’s GPA in your database or do you re-calculate every time you want to display it?

{% endcomment %}

APPS
 - How did you choose to store application data in your database and why? Will any of your logic have to change for phase 2 to support multiple recommenders?
 - When a user logs in, what do you store in your session and why?

{% comment %}
 - How did you choose to store reviews in your database? Will your logic have to change for phase 2 with multiple reviewers?
 - How did you store the status of an applicant’s application items (i.e. transcript, recommendation letter, and decision status)?
 - What kind of error checking did you do for a student’s application?
{% endcomment %}

## Incomplete Projects
If your project does not contain the full Phase 1 functionality, it may be considered incomplete. This will affect what you are assigned to do in Phase 2. You will still need to demo whatever functionality you have working at the Phase 1 deadline.

## Requirements on testing data and start state of database
Your main page should have a “RESET” button **OR** you must have a script handy that you can use to reset the database. The reset will bring your database to a starting state (i.e., erase all the data and populate it with the data specified below and any other test data that you wish to add). The reset is nothing but a bunch of delete statements followed by insert statements.

Listed below is the state that you must get to after a Reset operation. If you have other data that you wish to populate the database with, then feel free to include that but let us know what the data is.

**Note**: If you are using a different format for IDs than listed below (such as an Int starting at 1) or are using email addresses instead of user names, that is also acceptable, but make a note of this in your issue.


### REGS Starting State

  - Course schedule must be exactly what is specified in the project description.
  - Students:  There must be two *MS*  graduate students entered into the system with the student numbers and other data as specified below:
    - Holiday, Billie with ID 88888888 and registered for CSCI 6461 and CSCI 6212. Provide us with their system login info (so we can test their registration transactions).
    - Krall, Diana with ID 99999999 and no courses registered.  Provide us with their system login info (so we can test their registration transactions).  
  - Create the GS account (name of your choice), plus two faculty instructors: Narahari and Choi.  Provide their system login info in your Git Issue.  (You can have additional instructors.)
    - Narahari is instructor for CSCI 6461 and Choi is instructor for CSCI 6212

### APPS Starting State

  - Unused IDs: Make sure the following names and IDs are **not** used in your database start state/data. (The names are listed as Last name, First name and the ID)
    - Coltrane, John  with SSN 111-22-3333 and Univ ID  11111111
    - Davis, Miles  with SSN 222-22-3333 and univ ID 22222222
    - Monk, Thelonious with SSN 333-22-3333 and univ ID 33333333
    - Getz, Stan  with SSN 444-22-3333 and ID 44444444
  - Applicants:  There must be two applicants entered into the system with the student numbers and other data as specified below:
    - John Lennon, SSN 111-11-1111, (and univ ID 12312312) and application is complete but no reviews. Provide us with their system login info (so they can check on their status).
    - Ringo Starr, SSN 222-11-1111 (and univ ID 66666666), application is incomplete. Provide us with their system login info (so they can check on their status).
  - Users: Create GS, CAC, and at least one faculty reviewer Narahari. Provide their system login info in your Git Issue.  (Additional faculty reviewers should be Wood, Heller.)

### ADS Starting State

  - Course schedule must be exactly what is specified in the project description.
  - Students:  These two **MS** graduate students and one PhD student (if supported by your code) must entered into the system with the student numbers and other data as specified below but they have NOT submitted their Form 1:
    - McCartney, Paul with ID 55555555. Provide us with their system login info (so we can test their registration transactions). Has registered for and completed CSCI 6221,6212,6461,6232,6233 with all A's. Has registered and completed CSCI6241, 6246, 6262, 6283, 6242 with all B's.
    - Harrison, George with ID 66666666  -- provide us with their system login info.  He has registered for and completed ECE6242 with a C grade, and CSCI 6221, 6461,6212, 6232, 6233, 6241,6242, 6283, 6284 with all B's on the CSCI courses.
    - A PhD student named Ringo Starr, with ID of your choice. Ringo student should have completed 12 CS classes with all As. The advisor should not yet have approved their thesis defense. (You can leave this user out if you did not complete PhD graduation audits)
  - Alumni: There must be at least one alumni below entered into the system
    - Clapton, Eric with ID 77777777. Provide us with his login info. Clapton has completed CSCI 6221, 6212, 6461, 6232, 6233, 6241, 6242 and got B's on these courses; and has completed CSCI 6283, 6284, 6286 and got A's on these three courses. He graduated in 2014 with a MS degree.
  - Users: Create the GS account (name of your choice), plus two faculty advisors: Narahari and Parmer.  Provide their system login info in your Git Issue.  (You can have additional instructors.)
    - Narahari is advisor for McCartney and Parmer is the advisor for Harrison and Ringo Starr (if you support PhD students).
