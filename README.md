# Course Planner

## Introduction
The Course Planner is a program designed to help users plan their academic schedules by providing information about courses, including their titles and prerequisites. The program allows users to load course data from a file, view a list of available courses, and obtain detailed information about specific courses.

## Program Structure
The program consists of several components, including data structures for storing course information, functions for loading and sorting course data, and a menu-driven interface for user interaction. Here's an overview of the main components:

### Data Structure
- **Course**: A structure representing a single course, containing fields for the course number, title, and prerequisites.

### Functions
- **loadDataStructure**: Reads course data from a file and populates a vector of Course objects.
- **quickSort**: Implements the quicksort algorithm to sort the vector of courses based on course numbers.
- **printCourseList**: Prints a list of all available courses, sorted by course number.
- **binarySearch**: Performs a binary search to find the index of a course in the sorted vector of courses.
- **printCourseInfo**: Prints detailed information about a specific course, including its title and prerequisites.

### Main Function
- **Menu**: Displays a menu with options for loading data, printing course lists, printing course information, and exiting the program. Based on user input, the program performs the corresponding actions.

## User Interaction
The program provides a user-friendly interface through a command-line menu. Users can choose from various options to perform different tasks, such as loading course data, viewing course lists, and obtaining information about specific courses.

## Error Handling
The program includes error handling mechanisms to handle cases where file input/output operations fail or user inputs invalid options. Error messages are displayed to inform users about issues encountered during program execution.

## Conclusion
The Course Planner program offers a convenient way for users to manage and explore course information, facilitating the planning of academic schedules. With its intuitive interface and efficient data management, the program provides valuable assistance to students and academic advisors alike.