Labriola InnoHub RFID Scanner Project

Goal: Design and build a system in which students can swipe their ID cards, then have a database pull and display information on what machines they have and have not been trained to use.



The problem:

- Students come into spaces like the woodshop and don’t know what tools they’re trained to use
- Sometimes they start using machines that they are not trained on or don’t know required training to use
- TAs don’t have a quick way to check student trainings
- We currently work on an informal honor system for if students are trained
- TAs typically only check trainings docs if we notice someone who says they are trained on a machine using it very unsafely


What we want:

- Student walks into shop/space -> scans blastercard on RFID scanner
- Computer grabs their data based on CWID -> screen displays list of what machines student is/is not trained on

The GUI that display the info must be simple!!! All it should take is a card scan, and maybe a button press. There should not be a need to run any commands or queries to access what a student/TA needs.
**The GUI will probably need to have some sort of functionality to allow TAs to manually fetch and update the information in the database.
