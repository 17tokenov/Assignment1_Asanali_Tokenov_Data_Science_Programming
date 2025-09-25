# Assignment1_Asanali_Tokenov_Data_Science_Programming
This is a completed assignment from the Programming for Data Science course, the purpose of which is to demonstrate an understanding of basic libraries for working with directories and files.


All Requirements of Assignment 1
Task 1: (25b) Working with folders and files
1. Creating a project structure
• Write a script that creates a project directory with subfolders:
o data
o results
2. Working with CSV files
• In the data folder, save the students.csv file with data about students (full
name, group, grades).
• Read data from students. csv and calculate the average score for each
student.
3. Save results
• Save aggregated results in JSON format (results/report.json).
• Check: if the file already exists, display a warning and ask for confirmation
for overwriting.
4. Archiving
• Automatically create an archive results.zip, where the results folder is saved.
5. Working with pathlib
• Implement a check to see if report.json exists. If yes, print its size and last
modification date.
Task 2: (25b) Search for a word in a text file
Generate 5 text files (name_.txt_.txt), put them in the same folder. The files
contain any text. Write a program that accepts a search query and outputs the names
of text files containing the desired substring.
Input format
String containing the search query. It can be either a single word or a phrase
combination. For example: mathematics, probability theory.
Output format
A list of text files containing the substring entered by the user. Or a message that the
search query is missing in these files.

Task 3: (25b) File Information о файле
There is a file available file.txt (the file is attached to the task). Write a
program that outputs the following text statistics:
• the number of letters of the Latin alphabet.
• number of words.
• number of lines.

Task 4: (25b) Forchanging words
There are two files words.txt.txt and forbidden_words.txt_
words.txt (the
files are attached to the task). In the filewords.txt.txt contains text. In a text file
forbidden_words.txt forbidden words are stored separated by a space character.
Write a program that replaces in the filewords.txt.txt all forbidden words
from the file forbidden_words.txt_
words.txt asterisks * (the number of asterisks
is equal to the number of letters in the word).
The program must replace all forbidden words wherever they occur, even in
the middle of another word. Case-insensitive substitution is performed: if the file
forbidden_words.txt If it contains the forbidden word exam, then the words exam,
Exam, ExaM, EXAM and exAm should be replaced with ****.
Output format
Text edited according to the task condition.
