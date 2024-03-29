This project is a command line Java application that simulates demand paging algorithms for a virtual memory system. This application consists of four classes: Simulator.java, Frame.java, Memory.java, and RefString.java.

Simulator.java contains the main method for the application and constructs the selection menu for taking user input. A switch statement controls the logic flow of the application based on user selection. This class also contains methods for reading user-generated reference strings and generating random reference strings used by the application. Error handling is also present in these methods.

Frame.java is a helper class that creates and defines objects used to represent page frames used in the paging algorithms. This class contains getter and setter methods, as well as tracks when each frame was last used and how many times it was used in the algorithms.

Memory.java defines the logic for the four paging algorithms used (FIFO, OPT, LFU, LRU) and simulates the virtual memory system. Methods for generating the memory system, calling the paging algorithms, printing the state of the physical memory after each string call, and constructor methods are included.

RefString.java creates and defines the reference string that is used in the simulator. Constructor, getter, and setter methods are included.

To compile it on your device clone the repo and delete all the class files and *compile* it using javac _*_.java
