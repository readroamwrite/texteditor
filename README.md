# Text-Edit
This is an interactive text editor that would enable a user to use all basic functionality to edit their code and text, in addition to certain advanced features such as word finding and spelling error checking. 

Some key features that have been implemented are:

- Creating a new file: Starting a new empty file
- Viewing the current file read only: Viewing without options to manipulate/delete the file
- Edit the current read only file: The editor can take in a single command-line argument giving the name of the file to edit. 
- Saving the file: If the user types Ctrl+S, the editor should save the current contents of the document back to the file.
- Specifying a name (i.e save as) for the file and deletion of the file.
- Cut and paste operations: Ctrl+C, Ctrl+V and Ctrl+X would work with their usual copy, paste and cut functionality.
- Backspace and delete: if the user types the Backspace key, the editor must delete the character immediately before the cursor (unless there is a selection; see below). The Delete key should delete the character at the cursor location.
- Undo and redo operations (Ctrl Z, Ctrl Y): A single undo erases the last change made to the doc. Redo restores the most recent undo operation.
- Traversal through the file: The four arrow keys move the insertion cursor up, down, left, and right by one character.
- Spell check functionality: Underlines the spelling mistakes in red.
- Word finding feature: Feature by which the application predicts the rest of a word a user is typing using the Trie data structure.  

