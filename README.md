# Orion – A Terminal Based Money Management Application
Orion is a terminal-based Application in C that will prompt the users for their current expenses and help them manage their monthly expenses. Based on the input data, it will provide personalized suggestions to reduce or increase their expenses, it allows users to create personal accounts, enter and sort expenses by priority. It utilizes basic concepts of C like file handling, file interlinking, loops, sorting and conditionals to achieve its goals of budget allocation, and to minimize overspending. It generates personalized suggestions using AI which was obtained by triggering the google Gemini API through python and executing in C using bash file. 

### Programming Concepts Used: 

1) Functions – We assigned separatre functions while performing each task, which made our code easy to use and understand. Function helped in logical breakdown of tasks like taking user input, saving data, sorting, and authentication. 
2) File handling – We used file handling for storing user data, user persistence and data tracking. 
Files were used in reading and writing mode. 
3) Structures – Concepts of structures were used to store data of user and budget. 
4) Sorting – We used the concept of sorting to give the user choice to select their expenses 
based on priority. Priority based selection sort was implemented to generate the suggestion for user based on the priority. 
5) Systems calls – Orion generates suggestions using google API (Application Programming 
Interface), which was used in python to integrate AI capabilities in our program. We then used system (“python3 orion_adivce.py”) to trigger python from within C. 
6) Inter-process communication – We used .current_user file to pass state from C to Python 
which took the user input data to python and then the suggestion was generated in python using google Api.

### Future Enhancements: 
1) Implement monthly tracking using user’s expenses history and provide suggestion along with 
comparison  
2) Use of user-friendly Graphical User Interface (GUI) to replace terminal based interaction making 
it more accessible to non-technical users. 
3) Allow users to create and name their own category rather than predefined ones.


*This is a collaborative project for CSE 1320 (Intermediate Programming).*
### Contributors
1.	**Kripa Neupane**
2.	**Madhurima Shrestha**
3.	**Dikshya Laudari**
4.	**Badrinath Dalvai**
