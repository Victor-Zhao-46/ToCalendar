# ToCalendar
*ToCalendar is currently in operation at idatacloud.org/tocalendar*
Imports event calendars in word/excel tables into calendar applications such as Outlook and Google Calendar.
Currently focuses on importing homework calendars from schools to help students keep track of homework better, but can be expanded to include general event calendars.
The instructions for using the .ics files generated by the code is in the instruction pdf file.

Files: core-transformation-php.py: core code that interprets homework calendars by analyzing keywords, meant to be executed from the upload.php script in the webpage folder.

webpage/:folder containing all the website components. index.html is the webpage itself, and upload.php is the script that is called upon selection of a docx file to save the file and run the Python script. The images folder and css.css contain styling for the website.

Dependencies: This project uses python docx from https://python-docx.readthedocs.io/en/latest/ and icalendar for python from https://pypi.python.org/pypi/icalendar.
