# TutorialsMaster
Application implemented in C++ for tutorials management\
# Admin mode
- Add a new tutorial in the database
- Delete a tutorial
- Update the information of a tutorial
- See all the tutorials in the database\
Each **Tutorial** has a `title`, a `presenter` (name of the presenter person), a `duration` (minutes and seconds), a number of `likes` and a `link` towards the online resource containing the tutorial.

# User mode
A user can create a `watch list` with the tutorials that he/she wants to watch. The application allows the user to:
- See the tutorials in the database having a given presenter (if the presenter name is empty, see all the tutorials), one by one. When the user chooses this option, the data of the first tutorial (title, presenter, duration, number of likes) is displayed and the tutorial is played in the browser.
- If the user likes the tutorial, he/she can choose to add it to his/her tutorial watch list.
- If the tutorial seems uninteresting, the user can choose not to add it to the watch list and continue to the next. In this case, the information corresponding to the next tutorial is shown and the user is again offered the possibility to add it to the watch list. This can continue as long as the user wants, as when arriving to the end of the list of tutorials with the given presenter, if the user chooses next, the application will again show the first tutorial.
- Delete a tutorial from the watch list, after the user watched the tutorial. When deleting a tutorial from the watch list, the user can also rate the tutorial (with a like), and in this case, the number of likes for the tutorial will be increased.
- See the watch list in the chosen format (`CSV` or `HTML`)

# Used Concepts
- Layered Architecture
- OOP Principles
- Qt for GUI
- CSV, HTML database storage

# Demo
![image](https://github.com/georgianapetricele/Tutorials-Management-Application/assets/115110913/398d3661-c40a-4e3b-ba2b-2f2cb1c2bd6b)
![Screenshot (22)](https://github.com/georgianapetricele/Tutorials-Management-Application/assets/115110913/cb02f56d-cfc7-4c72-8f1f-16c6763b2920)
![Screenshot (23)](https://github.com/georgianapetricele/Tutorials-Management-Application/assets/115110913/c2631b05-3818-488b-a7ba-e92b1ca96298)
![Screenshot (24)](https://github.com/georgianapetricele/Tutorials-Management-Application/assets/115110913/28f54d86-2506-4a54-8dd8-b0132528b188)
