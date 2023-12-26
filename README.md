# Diary_Management_System
Here , we have made a 'Personal Diary Management System' using C language. 
This simple diary management system allows users to add, view, and delete personal diary entries. Below are instructions on how to use the system and a brief overview of the source code.

## Instructions:

1. **Compile and Run:**
   - Compile the source code using a C compiler (e.g., GCC).
   - Run the compiled executable.

2. **Main Menu:**
   - Press `1` to add a new diary entry.
   - Press `2` to view existing diary entries.
   - Press `3` to delete a diary entry.
   - Press `4` to exit the system.

3. **Adding a Record:**
   - Enter the date (dd/mm/yyyy), time (hh:mm am/pm), location, and message when prompted.
   - The entry will be saved to the "Diary.dat" file.

4. **Viewing Records:**
   - Choose a record number to view details.
   - The system displays the selected diary entry's date, time, location, and message.

5. **Deleting a Record:**
   - Choose a record number to delete.
   - The selected entry will be removed from the diary.

6. **Exiting:**
   - Pressing `4` exits the system.

## Source Code Overview:

- The program uses a simple file-based approach to store diary entries in a binary file named "Diary.dat."

- Three main functions handle different aspects:
  1. `addRecord()`: Adds a new diary entry to the file.
  2. `viewRecord()`: Displays existing diary entries and allows the user to view details of a specific entry.
  3. `deleteRecord()`: Removes a selected diary entry.
