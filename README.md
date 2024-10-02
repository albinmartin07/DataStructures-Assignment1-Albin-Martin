Name : Albin Martin 
ID : C0903277 
Group : 2


1. The Array Artifact :
In this task, I created the ArtifactVault class, which uses a fixed-size array to store artifacts. The vault allows for adding new artifacts to the first available empty slot and removing artifacts by setting their position in the array to null once found. To search for artifacts, I implemented two different methods: one that performs a linear search through the array and another that assumes the array is sorted and performs a binary search. I handled null entries by filtering them out before sorting for the binary search. The program operates through a menu system, enabling users to add, remove, search for, and display the stored artifacts.

2. The Linked List Labyrinth:
For the labyrinth path problem, I developed a LabyrinthPath class using a singly linked list to represent the path traveled. The class can add new locations to the path, remove the most recently visited location, and check for traps or loops using Floyd's cycle detection algorithm. Additionally, there’s a feature to print the entire path from the start to the current location. This design assumes locations are added one after the other and that loops in the path can be detected and handled.

3. The Stack of Ancient Texts:
To manage ancient scrolls, I implemented the ScrollStack class, which operates like a stack (Last In, First Out). The class includes methods to add new scrolls to the top of the stack, remove the top scroll, view the top scroll without removing it, and search for a particular scroll within the stack. The stack is dynamically managed and follows standard stack operations. The approach was designed to handle adding and removing scrolls efficiently, with the stack growing as more scrolls are added.

4. The Queue of Explorers:
In this challenge, I created the ExplorerQueue class using a circular queue to manage a line of explorers waiting to enter a temple. The queue allows explorers to be added to the end and removed from the front, with the structure wrapping around when the end of the array is reached. There is also a method to view the next explorer in line without removing them, and checks for whether the queue is full or empty. This design ensures efficient space utilization in the queue by making use of circular logic, while keeping the first-in, first-out (FIFO) order intact.

5. The Binary Tree of Clues :
For the binary tree problem, I developed a ClueTree class to represent a collection of clues organized in a binary search tree. The class allows for inserting new clues into the correct position based on their value. It also includes methods to traverse the tree in in-order, pre-order, and post-order sequences. Additionally, there are functions to search for a specific clue and to count the total number of clues in the tree. This design leverages the binary tree structure to allow efficient searching, insertion, and traversal of clues.

All 5 programs are menu driven so it is very easy to operate after running the code by following the menu which is listed
