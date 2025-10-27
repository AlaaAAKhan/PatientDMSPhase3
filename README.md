/*
 * Alaa Khan
 * CEN 3024C - 13950 - Software Development 1
 * */

This project is a Data Management System (DMS). The data that is being managed is Patient information. Each Patient object is stored in an ArrayList 
with the attributes of a unique 7-digit ID, a name, address, attending doctor, Insurance provider, and the day they attend for sessions. Users can perform
the CRUD operations of Adding, Removing, Updating, and displaying all the patients. Additionally, I have created a custom function that counts the total number
of patients that attend on a certain day. This day is given by the user, and the system outputs the total number of patients attending for that day. 

This version of the code contains a GUI class. By running it, all the abovementioned operations and interactions will be done through the GUI. The functions will be 
on the left side of the screen while the patients will be displayed on the right. Additionally, each of the functions is separated into its own tab at the top of the left
side of the screen.

To create a new patient to add to the system, users can either add in bulk by uploading a file (that meets the format criteria) or manually adding a single patient
by filling out their attribute information. 
Removing a patient can be done by entering the patient that needs to be removed. 
Updating a patient's attribute works similarly, in that the patient's ID is required before the user chooses which attribute to change from a drop down menu, and the new
information to replace it with.
Displaying the patients simply displays the list of the patients. Since they are already updating and being shown as functions are operated, it is more of a refresh button. 
To count the total number of patients attending on a specified day, simply enter the day you would like to see the attendance of, and the result will be automatically shown.

The program is structured so wrong input does not break it at any point. 
