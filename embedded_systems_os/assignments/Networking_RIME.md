
### Assignment Topic

Programming and Rime stack communication in Contiki

### Setup instructions

Before you begin, you need to go through an example code of unicast communication in Contiki. Then you must run the source code in Cooja and observe how Contiki works, how unicast works

### How to submit

The format of your work must be in a zip folder with the name : assignment1. There are 3 subfolders in the zip folder with names: Task1, Task2, Task3. In each task folder, there are source files and screenshoot of running application. For example:

Task3 folder has files: task3-1.c, task3-1_screenshoot.jpg, task3-2.c, task3-2_screenshoot.jpg, and task3-3, task3-3_screenshoot.jpg

Finally you need to add a text file to present your observation.

### Tasks

There are three tasks in this assignment:

**Task1:** (3 points): Simulate broadcast (Rime) in Cooja. A random node broadcasts to all nodes when both an etimer event and a button sensor event are triggered. Tips: reuse and modify an example code in example-broadcast.c file. The file example-trickle.c can be used as a reference for using buttons.

**Task2:** (3 points )Simulate multihop (Rime) in Cooja. Receiver nodes must print out receiving package i.e. your name. Note: reuse and modify an example code in example-multihop.c file.

**Task3:** (4 points) Simulate trickle (Rime) in Cooja. Modify an etimer value in the code with different values:

10 power of (-20) * CLOCK_SECOND, 10 power of (-14) * CLOCK_SECOND and 10 power of (-6) * CLOCK_SECOND for three different simulated cases. Then, give comments for your observation.

*Note: reuse and modify an example code in example-trickle.c file. Please delete unnecessary code. Note: all necessary files for this lab are located in folder: /home/user/contiki-2.7/examples/rime.*
