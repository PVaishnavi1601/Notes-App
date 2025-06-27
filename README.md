# Notes-App
 Create a text-based notes manager with file read/write.

To demonstrate Java file handling by creating a terminal-based notes application that:
Accepts user input to write notes
Saves notes to a file (`notes.txt`)
Reads and displays all saved notes

The Java Notes App is a simple, text-based project developed to demonstrate the usage of File Input/Output (I/O) in Java. The core objective of the application is to allow users to write and read personal notes directly from the terminal. These notes are stored in a plain text file (notes.txt) and can be retrieved anytime the user wants to view their previous entries. This project uses key Java classes such as FileWriter, FileReader, BufferedReader, and Scanner to manage file writing, reading, and user input operations.

When the program is executed, it displays a menu-driven interface with three options: write a new note, read all notes, and exit. If the user chooses to write a note, the program takes the input and appends it to the notes.txt file using the FileWriter class in append mode. This ensures that existing notes are preserved while new ones are added. On selecting the read option, the program reads each line from the file using BufferedReader and displays the notes in a list format. If the file doesn't exist or is empty, it handles the situation gracefully without crashing, and appropriate messages are shown to the user.
