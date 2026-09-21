IT Help Desk Ticketing System
1. Customer Statement of Requirements
The purpose of my project is to create an IT Help Desk Ticketing System. The system will allow people to report computer or technology problems they are having. Instead of emailing the IT person or trying to find them in person, they can submit their problem through the system.
There will be two types of users. The first will be a regular user who needs IT help. The user will be able to enter their name, describe their problem, and submit a ticket. The second user will be the IT administrator. The administrator will be able to see the tickets that have been submitted and update their status.
The main goal of the system is to make it easier to report, organize, and keep track of IT problems until they are fixed.
2. Requirements Specification
Functional Requirements
A user will be able to enter their name.
A user will be able to describe their computer or technology problem.
A user will be able to submit a new ticket.
Each ticket will have its own ticket ID.
A user will be able to see the status of their ticket.
The IT administrator will be able to view submitted tickets.
The IT administrator will be able to see the information for each ticket.
The IT administrator will be able to change the status of a ticket.
A ticket can have a status of New, In Progress, or Resolved.
The system will save ticket information in a database.
Non-Functional Requirements
The system should be simple and easy to use.
The system should save ticket information correctly.
The system should load and update tickets without taking a long time.
Ticket information should still be available after the program is closed and opened again.
The program should have a simple and understandable user interface.
The code should be organized so that changes can be made later.
3. Data and Storage Blueprint
Data Input
The information will be entered manually by the user. I plan on using JavaFX to create the user interface. The user will use text boxes to enter their name and describe the problem they are having. They will then click a button to submit the ticket.
The IT administrator will also be able to select a ticket and change its status. The status can be New, In Progress, or Resolved.
Database / Storage
I plan on using SQLite for the database. SQLite will save the ticket information so that the information is not lost when the program is closed.
The database will save information such as:
Ticket ID
User's name
Problem description
Ticket status
Date the ticket was created
I will use Java for the main programming, JavaFX for the user interface, and SQLite for storing the ticket information.
2. GitHub Issues
After you save Requirements.md, go to Issues on GitHub.
You will create 7 separate Issues. Put one of these in each Issue:
Issue 1 — Submit a Ticket
As a user, I want to submit an IT help ticket so that I can report a computer or technology problem.
Issue 2 — Receive Ticket ID
As a user, I want my ticket to have an ID so that my problem can be identified and tracked.
Issue 3 — Check Ticket Status
As a user, I want to see the status of my ticket so that I know if my problem is being worked on or has been resolved.
Issue 4 — View Tickets
As an IT administrator, I want to view submitted tickets so that I can see which users need help.
Issue 5 — View Ticket Information
As an IT administrator, I want to see the user's name and problem description so that I understand the problem.
Issue 6 — Update Ticket Status
As an IT administrator, I want to change a ticket's status to New, In Progress, or Resolved so that I can keep track of the work being done.
Issue 7 — Save Tickets
As an IT administrator, I want tickets to be saved in the database so that ticket information is not lost when the program closes.
