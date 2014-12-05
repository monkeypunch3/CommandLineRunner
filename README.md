CommandLineRunner
=================

It gives command line commands a UI dynamically. It exists to make it easier for people to run and save command line code. 

For example, if you want to overlay the AIR SDK you must select the source AIR directory and the target AIR directory. So you enter a JSON option for the source directory and target directory and then a browse for directory for source and target appear in the UI section of the program. You can then use the UI to select the source and target directories and CLUI will enter that into the command statement and place single or double quotes around it. 

To use: 
Write a command line statement as you normally would in the input text area. Where you want to provide a user interface option you type a JSON object. CLUI will then show that UI element in the form area and build the correct command line statement in the output text area. You can then copy the code to the clipboard with the copy button and paste it into Terminal or another command line program.
