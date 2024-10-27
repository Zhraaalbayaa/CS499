[Home](readme.md "Home") [Software Design and Engineering](CS320.md "Software Design") [Algorithms and Data Structures](cs300.md "Algorithms") [Databases](cs340.md "Databases") [Code Review](codereview.md "Code Review") 

---

## Refinement Plan and Code Review

---

Code review has been conducted on the three selected artifacts one for each category of Software Design and Engineering, Algorithm and Data structures, and Databases.   One video for each of these code reviews has been screen-captured with live commentary to explain the step-by-step code review. Code review covers the identification of bugs and errors in the current code base, improvements introduced in these artifacts, and enhancements performed to improve these artifacts. 

I am going to use Visual Code as an IDE to carry out coding, compiling, and running this code review project. For recording, I am going to use Camtasia 2022 Software which is a sophisticated Screen Recording software. I will create my video using the screen recording option while doing the code review and code the project to recreate and enhance it. To add commentary, I’ll use the narration option and compile the video after adding my voice through this narration. 

### Steps

- Existing functionality has been thoroughly explained along with any bugs and errors spotted during the walk-through.

- The code has been analyzed and explained for any bugs and possible improvements and enhancements that can improve the quality of existing artifacts. 

- Step by Step explanation has been provided while improving the code using Code Review methodology.

### Artifact 1: Software Design and Engineering

[Video: Software Design and Engineering](https://youtu.be/XUoHQTiA3uY "Video: Software Design and Engineering")

The artifact selected for this software design and engineering category is related to a Project completed during a course taken at (Southern New Hampshire University) CS320. This project was related to creating a Java-based Contact class along with a repository class to provide crude operations to manage the in-memory contact repository and service. The project also involved creating unit tests for both these classes Contact.java and ContactService.java. The application intends to manage contacts and uses Java HashMap for an efficient in-memory data repository and provides robust unit tests to validate the data input and intended functionality to improve the quality assurance of the artifact. To create this application, java’s JDK version 18 was used in combination with a famous Eclipse IDE. The Junit Test version 5 is used to test the boundary conditions, functionality, and data input validations. The Entity classes is used following the best coding standards using data encapsulation, constants, and robust functions to create and use Contact objects. The repository class used HashMap which is one of Java’s fastest collection frameworks with efficient insertion, retrieval, and deletion procedure runtimes. 

### Artifact 2: Algorithms and Data Structures

[Video: Algorithms and Data Structures](https://youtu.be/6BihOaUT4Kg "Video: Algorithms and Data Structures")

This artifact has been selected for the Algorithms and Data Structure Category from CS300 Data Structures and Algorithms: Analysis and Design. The application demonstrates reading datasets from a CSV File related to Bids loaded the data set into a Vector. The Vector is then sorted using two different sorting algorithms Selection Sort and Quick Sort. This application is developed using C++ programming language and Visual Studio Code is used as an IDE with g++ GNU Compiler to compile the source code on Windows operating system. 

### Artifact 3: Databases

[Video: Databases](https://youtu.be/GLtaDTCYxEg "Video: Databases")

The selected Artifact is chosen from a project completed for the Course CS340 Client and Server Application Development. The application involves creating a document-based MongoDB NoSQL Database from a given Dataset comprising Animal data for a given Animal Shelter. The CS340 Client and Server Application Development course teaches how to plan, design, and develop client/server applications. The selected artifact is based on the creation of a NoSQL database from the given dataset. The suggested enhancement to this database application is related to creating Simple and Complex indexes to enhance the database search routines. MongoDB database systems help optimize and improve the execution of data selection or projection queries by incorporating indexes. Indexes support the efficient execution of the select queries to retrieve and filter the query-based data for its efficient and improved performance. Without indexes, the queries usually become sluggish, especially in the case of larger datasets. Incorporating indexes not only improves the database performance but also decreases the runtime of the query execution significantly. In the absence of Indexes, MongoDB scans every document present within the database which is like a brute force operation taking a lot of time and sluggish in preparing an output result. By introducing indexes, MongoDB limits the document related to that particular index and reduces the time complexity improving the runtime and database performance that helps develop robust and efficient systems that may produce results in real time without lagging the system. The indexes in MongoDB database System work by storing the specific field value or set of field values by the order of that particular simple or complex index. These ordered indexes match the query parameters and produce quality results filtered quickly as they are comprised of smaller datasets based on the indexes instead of every document in the database resulting in faster query output. The following screenshot shows the database created with 10k records/documents each representing data on a certain animal within the AnimalShelter and 4 indexes were created to enhance the query execution and search functionality within the database. 
