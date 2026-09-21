# Hospital-Management-System

A Software Engineering group project that models a Hospital Management System (HMS) using UML diagrams and data-flow modeling. This repository contains the complete design documentation created as part of our coursework.

Project Overview

The Hospital Management System is designed to streamline core hospital operations including patient registration, appointment scheduling, billing, medical record management, and staff administration.

Actors
Actor	Role
Patient	Registers, books/cancels appointments, makes payments
Receptionist	Registers patients, schedules appointments, generates bills
Doctor	Views medical records, writes prescriptions, updates diagnosis
Admin	Manages staff accounts, generates reports
Diagrams
#	Diagram	Description	Files
1	Use Case Diagram	Actors and their interactions with the system, including an <<include>> relationship	HMS_UseCase_Diagram.drawio, HMS_UseCase_Diagram.png
2	Class Diagram	System classes, attributes, methods, and relationships with multiplicity	HMS_Class_Diagram.drawio, HMS_Class_Diagram.png
3	ER Diagram	Database entities with primary keys (PK), foreign keys (FK), and crow's-foot relationships	HMS_ER_Diagram.drawio, HMS_ER_Diagram.png
4	Sequence Diagram	Step-by-step message flow for the "Book Appointment" process	HMS_Sequence_Diagram.drawio, HMS_Sequence_Diagram.png
5	Activity Diagram	Appointment booking process flow with a decision point (slot availability)	HMS_Activity_Diagram.drawio, HMS_Activity_Diagram.png
6	State Chart	Appointment status lifecycle: Requested → Confirmed → In Progress → Completed/Cancelled	HMS_State_Chart.drawio, HMS_State_Chart.png
7	DFD (Level 0 & 1)	Context diagram and detailed process/data-store breakdown	HMS_DFD.drawio, HMS_DFD_Level0.png, HMS_DFD_Level1.png
Tools Used
draw.io — UML and DFD diagramming
GitHub — version control and documentation hosting
How to View the Diagrams
Click any .png file above to preview it directly on GitHub.
To edit a diagram, download the corresponding .drawio file and open it at app.diagrams.net via File → Open From → Device.
HMS_DFD.drawio contains two pages (Level 0 and Level 1) — switch between them using the page tabs at the bottom of the draw.io editor.
Project Status

✅ Complete — Use Case, Class, ER, Sequence, Activity, State Chart, and DFD diagrams are all finished.

🚧 Optional next steps: SRS document (functional and non-functional requirements), test case documentation.
