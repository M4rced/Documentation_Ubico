# Requirements
___
> **Introducción:** Este documento de especificación de requerimientos de información se realiza para el proyecto UBICO
> **PURPOSE:**To create an innovative software for the reservation of classrooms and other spaces within the university campus.
___
## FUNCTIONAL REQUIREMENTS:
> **-** The system must allow authentication and authorization of users of the UBICO application; authentication is done through the registered e-mail address and a password chosen by the user. 
> **-** The system must allow to register users with the following basic data:
ID, type of ID, mail, first name, last name, password, type of person( teacher, student, administrative), cell phone, uco_id.
> **-** The system allows password updates.
> **-** The system must allow the registration of all classrooms (classrooms, auditoriums, laboratories, sports facilities) of the university (code, capacity, type of classroom, block) (administrator).
> **-** The system must allow to register all university blocks (code name, floor, total classrooms) (administrator).
> **-** The system must allow the reservation of the different classrooms that are available for a user on a specific date and time (the user can update, consult and cancel the reservation), it must allow the user to enter a justification or description of the reservation.      
> **-** The system must send via e-mail the confirmation or rejection of the reservation made by the user.
> **-** The system will allow the administrator user to consult the reservations in pending status, validate the availability and veracity of the data and accordingly accept or reject the reservation (order of arrival).
> **-** The system must be able to handle the different statuses for a reservation (pending, accepted, rejected).
___
### INFORMATION REQUIREMENTS:
> **-** The system must store user information with the following data: ID, type of ID, e-mail, first name, last name, password, type of person (teacher, student, administrative), cell phone, uco id.
(teacher, student, administrative), cellular phone, uco id).
> **-** The system must allow storing the information of the university classrooms with the following data: code, capacity, type of classroom, floor, block, etc.
> **-** The system must allow to store the information of the university blocks with the following data: code, name, floor, number of classrooms, etc.
> **-** The system must allow storing the information of the reservation made by the user with the following data: code, name, uco id, date, start time, end time, type of classroom reserved, reason for reservation, reservation status.
___
#### NON-FUNCTIONAL REQUIREMENTS:
> **-** Performance.
> **-** Availability.
> **-** Accessibility.
> **-** Adaptability.
> **-** Capacity.


















