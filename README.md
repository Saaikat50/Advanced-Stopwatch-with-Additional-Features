Description :
A graphical advanced stopwatch application built with Java Swing that provides Start, Stop, and Reset 
controls. It also adds additional features like time calculation from one time to another time and time freezing option. The elapsed time is displayed in HOUR: MINUITE : SECOND format and updates every second using a 
timer. The application demonstrates event-driven programming and GUI component design in a 
straightforward, visually intuitive layout. 

Architecture :
The GUI is constructed using Java Swing components: a JFrame as the window, a JLabel for the 
time display, and JButtons for control. A javax.swing.Timer fires an ActionEvent every 1000 
milliseconds to increment the elapsed-second counter. The ActionListener callback updates the 
label text after converting total seconds into hours, minutes, and seconds. State (running/stopped) 
is tracked with a boolean flag.

Outcome :
Students learn event-driven GUI programming, Java Swing component hierarchy, timer-based 
updates, and state management. The project clearly illustrates how user actions trigger code 
through the listener pattern, which is a foundational concept in modern application development.
