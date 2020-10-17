# Mohammad-ansariSchool-Management-system-with-GUI-in-C-object-oriented-programming
School Management system with GUI in C# object-oriented programming
I. ABOUT THIS FILE

All description of application is provided in specifications .docx file,
this file contains technical instructions on running and any limitations.

II. BUILDING AND RUNNING 

.zip folder with project must be extracted and then, when opening Visual Studio
(We used 2019 version) "open local folder" option should be chosen, then 
.sln file inside the extracted folder launched.
Then Ctrl+F5 (or Debug->Run without debug) can be chosen.

III. INPUT/OUTPUT DATA

Input data used for the program are in datafiles subfolder.
There are such files:
- users.csv (contains information for students, admins, teachers, format is
  described in header line)
- courses.csv (for courses) 
- marks.csv (for marks)

The program reads all files, but if no (or they have only header line) it will
just work with empty dictionaries.

All data is updated during program operation, and after quitting it
.csv files will be also updated.

BUT!!! Intentionally for easy test: if the program is closed by clicking cross "X"
as usually in win apps, then .csv files are not written (all updates are lost).
To update files you need to click "logout->quit" (from any window).

IV. LIMITATIONS

The only limitation -- any field (name etc.) cannot have commas inside (,) as
they are separators in .csv files. The program checks that and warns the user
if he does error (while in registration or while updating personal info or 
while adding new course by admin),
but if you user.csv files updates by hand, has to remember this.
If the datafiles (In Excel Format) are opened in taskbar then it might give 
user an error. So it is better to open the datfiles in notepad format.

V. CONCLUSION

All requirements of the task are satisfied to the dot
we treid to used whatever we discussed during the lecture.
Such as 
1) winforms
2) LINQ (extensively, almost everywhere)
3) inheritance
4) polymorphism
5) extension method (for GUI)
6) delegates (once)
7) structs
8) enums
9) collections
10) also file operations
11) validation of forms input ( if user Enter wrong ID or password, Display the meesage" UserID or Password Incorrect ). 
