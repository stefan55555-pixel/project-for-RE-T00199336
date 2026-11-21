# project-for-RE-T00199336
** stefan krstic - t00199336**

*college student support appointment system*

*project overview*

make a system that can be used bye students to book  appointments with staff and more.



*problem,stackeholders and goals*

problem 
- how many books a day
- what time slots are there
- how many staff will be involed
- who is run the up keep of it
- will there be double booking
  


| Stakeholder | Role |
| ---------|-----------|
| Student | Books and manages appointments.|
| Staff | Provides support and manages appointments|
| Superiors | Oversees the system and staff.|
| Maintenance | Maintains and fixes the system.|
| College | Owns and uses the system.|


*Stakeholder  Needs and Concerns*

Student Needs:
- view available appointment time.
- book appointments with staff.
- cancel or change appointments.

Student Concerns:
- double bookings.
- incorrect appointment information.
- difficulty using the system.

Staff Needs:
- view their appointment schedules.
- manage availble time slots.
- see student appointment details.

Staff Concerns:
- overlapping appointment.
- incorrect booking information.
- too many appointments in one day.


goals
- Allow students to view available and occupied time slots.
- Allow students to book appointments.
- Prevent double bookings.
- Show staff availability.
- Allow staff to manage appointments.
- Make the system easy to use.
- Identify who is responsible for maintaining the system.

 **Requirements**
  
 |Functional | Requirement |
 |--------|---------|
 |FR-1|The system shall allow students to view available appointment time slots |
 |FR-2|The system shall allow students to book an appointment with staff |
 |FR-3|The system shall prevent double bookings for the same staff member and time slot|
 |FR-4|The system should allow students to cancel appointments|
 |FR-5|The system shall confirm successful appointment bookings|
     

 |Non-Functional | Requirements |
 |--------|---------|
 |NFR-1|The system should be easy to use and understand |
 |NFR-2|The system should load pages within 3 seconds under normal operating conditions. |
 |NFR-3|The system should be available during college operating hours.|
 |NFR-4|The system should provide accurate appointment information.|


*requirements Modelling**

*students use case*
- log in.
- view available /upcoming appointments.
- book and Cancel  appointmemets.

*staff use case*
- view and manage appointmemets scheduled.
- update availabiliy.

*IT managment*
- manage staff and user accounts.
- oversee the system.

 
( page 2 needed for 2 UMLs)

*Booking Process*
1.Students logs into the system.
2.Students selects a staff memnber
3.Students views available appointment times.
4.If available, the appointment is confirmed.
5.Student receives a booking confirmation.

 
*prototype*
1.Login 
- student or staff login.
- username and passwrod.

2.student side
- view upcoming appointments.
- book a new appointment.
- cancel an appointment.

3.appointment booking
- select staff member
- select date and time slots.
- confirm booking.

4.staff side
- view appointments.
- view student booking informantion.
- manage system informantion.

*quality requirements*

|Quality | Description |
|-----|-----|
|Usabiliy| The system should be easy for students and staff to use.|
|Security| Student information should only be accessible to authorised user.|
|Relibility| The system should save appointments correctly.|
|Aavailability| The system should be accessible during college operating hours.|


*prioritisation and change*

MoSCoW Prioritisation

|Priority | Requirement |
|-----|-----|
|Must Have| Students can book appintments.|
|Should Have| Students can cancel appointments. |
|Could Have| Students receive appointment reminders.|
|Wont Have | Mobile application separate from the website.|

Managing Changes
- Adding mew appointments tyeps.
- Changing appointment durations.
- Adding more staff members.
- Improving the booking process.


*Agile Requirements*

|Sprint | Tasks|
|----|----|
|Sprint1| Identify stakeholders and collect requirements.|
|Sprint2| Design the login page and student dashboard.|
|Sprint3| Develop the appointment booking system.|
|Sprint4| Develop staff and administrator features.|
|Sprint5| Test the system and fix porblems.|

User Stories

Student:

As a student, I want to view my appointment schedule so that I can choose a suitable time.

Staff:

As a staff member, I want to view my appointment schedule so that I can organise my working day.

Administrator:

As an administrator, I want to manage staff accounts so that the system contains correct staff information.

*traceability and validation*
|Requirement ID|Stakeholder|Verification|
|-----|-----|-----|
|FR-01|Student| Check that available time slots are displayed correctly.|
|FR-02|Student| Test booking an appointment.|
|FR-03|Student / Staff| Attempt to book an already occupied time slot.|
|FR-04|Staff| Check that staff availability.|
|FR-05|Staff| Test updating staff availabiliy.|
|FR-06|Administrator| Check that authorised administrators can mange.|

*Validation*
- Testing appointment bookings.
- Checking that double booking are prevented.
- Checking that appointment cancellations work.
- Checking that staff can update their availabiliy.
- Making sure student information is proteced.
- Gathering feedback from from students and staff.  

*Conclusion*
The College Student Support Appointment System aims to make booking appointments easier for students and staff.
The system will allow students to view available times, book appointments and manage their bookings. Staff will be able to manage their schedules and administrators will oversee the system.
The main priorities are preventing double bookings, protecting student information and making the system easy to use.
By following Requirements Engineering methods, the project can be planned, modelled, tested and improved to meet the needs of the college.
