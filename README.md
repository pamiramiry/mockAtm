# mockAtm
Create a replica of a wireframe for a Atm
Read Me

This project was created using Java SDK 17 and Spring Boot, along with additional technologies such as HTML, CSS, Bootstrap, ThymeLeaf, and Intellij as the code editor. The H2 database, which is an in-memory database, was used too. To fill the database manually, you will need to uncomment the code in the first method.

To run the project, follow these simple steps:

Unzip the file.
Open the project in your preferred Java IDE, preferably Intellij.
Ensure that all necessary libraries and dependencies are imported.
Navigate to the Main file, "MockatmApplication.java".
Uncomment the method call shown below on line 65, only for the first iteration. After the first iteration, comment on it again. This is necessary because H2 is an in-memory database, which means that the database must be filled each time a new machine is used. This method takes the JSON file with the data and puts it in the database.
Run the main method in that class.
Open your browser and search for "localhost:8080" to view the wireframe.

The purpose of uncommenting this method, as shown below, is to enable the program to retrieve the JSON file and populate the H2 database. Once the database has been populated, you will not have to repeat this process for the same machine, and you can then comment the method again.



Given that this is a Mock ATM program, I decided to limit the number of data points for the sake of convenience. When collecting the data, I used the /um/test/api/jr/txn/txnlist/{atmid}/{datetime}/v1 query as it closely mirrored the data depicted in the wireframe. However, due to the required parameters, it was difficult to obtain all of the data, so I had to make do with a smaller sample. Most of the search and filter functions are functional, with the exception of the ATMId and EMV chip. I did encounter some challenges when attempting to convert the date format to the calendar format, which resulted in discrepancies between the display and the wireframe.





All other requirements listed in the project description have been checked off on the wireframe. If you encounter any issues or have further questions regarding the program's functionality, please don't hesitate to reach out to me.

Pamir Amiry
pamiramiry10@gmail.com
6479164090
