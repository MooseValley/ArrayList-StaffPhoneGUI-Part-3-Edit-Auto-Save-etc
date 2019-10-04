# ArrayList - StaffPhoneGUI - Part 3 - Edit (Swing Dialog), auto-save, etc


3. Write a Java program using GUI that contains a text area and a command button titled as “**Display**”. When the “Display” button is clicked, the program has to read data from an existing data file named "**staffphone.txt**" and displays all the data in the text area properly. The data in the file "staffphone.txt" has the following format:

John Pearson, 49308877
Peter London, 49446701
Amy Andersen, 45009923

In addition to the data, the text area has to display the total number of the phone entries at the end.

4. (Continued from Question 3). This time when the program starts to run, the data file is automatically loaded and all the phone entries from the data file (staffphone.txt) are displayed on the text area as shown below. The GUI has two extra buttons – one named as “Add” and the other one named as “Save”.  When the “Add” button is clicked, an input dialog is asks the user to input a name; and similar input message dialog for obtaining phone value. The newly obtained data values have to be appended to the text area. If the “Save” button is clicked, all data shown on the text area has to be stored to the data file "staffphone.txt" in a suitable format.  Hint: You may need to use file read/write. The “Clear” button can be used to clear the contents from the text area.

4A. Wait, there's more ....
* Fix validation - data valid flag, exception handling.
* Edit button
* Auto-save file on exit
* Set Title
* Set Location

4B. Mike's additions:
Exit button
Change to using Exception Handling
Add / Edit using GUI controls - no more Swing Dialogs

