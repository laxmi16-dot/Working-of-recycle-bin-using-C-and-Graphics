This project is a graphical simulation of a simple desktop environment that allows users to interact with file icons and a Recycle Bin using mouse events. The program is developed in C using the graphics library and handles keyboard and mouse inputs to simulate basic file operations like dragging files to the Recycle Bin and restoring them.

Key Features:

1. Recycle Bin and File Icons:
The interface includes a Recycle Bin represented as a graphical object, along with four file icons labeled "Folder1", "Folder2", "Folder3", and "Folder4".
Each file icon is drawn as a small rectangle with a slanted top, resembling a file or folder.

2. File Dragging:
Users can drag and drop file icons into the Recycle Bin using the mouse. When a file is dropped inside the Recycle Bin, a message confirms that the file has been moved there.

3. Restoring Files:
If the user double-clicks on the Recycle Bin, a new window opens showing all the files currently in the bin.
Users can double-click on any file in the bin to restore it to its original position on the desktop, and a message is displayed confirming the restoration.

4. Mouse and Keyboard Interaction:
The program uses mouse clicks and double-clicks to interact with the files and the Recycle Bin.
The ESC key can be used to exit the main program or return from the Recycle Bin window to the main window.

5. Graphics Handling:
The program uses graphical functions to draw shapes, lines, and text on the screen.
Flood-fill techniques are used to fill shapes with color.
The program handles double-buffering by using cleardevice() and delay() to create a smooth user experience without flickering.

How it Works:
*The program initializes the graphics mode and enters a loop where it continuously checks for user inputs.
*Mouse clicks are processed to detect interactions with the file icons or Recycle Bin.
*Dragging functionality is implemented by tracking the mouse position when a file icon is being dragged.
*Double-clicking on the Recycle Bin opens a secondary window, allowing the user to restore files.
*After restoring, the main window is reopened with the updated positions of the restored files.

Potential Enhancements:
The program could be expanded to include more file icons or different types of icons.
Additional features such as creating new files, deleting files permanently, or adding more complex interactions could be implemented.
The visual design could be enhanced with more sophisticated graphics and animations.





