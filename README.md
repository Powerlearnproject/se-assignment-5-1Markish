[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15321469&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   Step 1: First make sure your system meets the least requirements to install and run visual studio code.
   Step 2: ![Open Microsoft Store and search Visual Studio Code and click install.](./images/img1.png)
   Step 3: Launch the app and agree to the licenses. Give the software the necessary permissions.
   Step 4: Run the software and install the necessary extensions


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   Personally for me, I started with setting the auto save feature. It really helps to automatically update your code after saving. Number 2, I then download afew extentions like live server that displays your html file in your browser. ![live server](./images/img2.png). There are also so many other extentions that you can install like prettier for formatting code, deppending on your preferences


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   1. Activity Bar: It is located on the left side of the window. Provides access to different views and major functions.![activity bar](./images/img3.png) By default, it includes icons for:
      Explorer: For file navigation and management.
      Search: For searching across files.
      Source Control: For version control integration (e.g., Git).
      Run and Debug: For running and debugging applications.
      Extensions: For managing extensions.
      GitHub: To access your github classrooms, pull requests and issues
      Live share: To collaboratively edit and debug with others real-time
    
   2. Side Bar: it is located right next to the Activity Bar. Displays the contents related to the selected view in the Activity Bar. Depending on the selected activity, it can show:
        File Explorer: Lists files and directories in your workspace.
        Search Results: Displays search results when using the search function.
        Source Control Information: Shows Git status, changes, and commit history.
        Debug Information: Provides controls and information for running and debugging code.
        Extension Information: Lists installed extensions and those available for installation.

   3. Editor Group:It is located in the central area of the window. The main workspace where you edit your files. It can be divided into multiple groups:
        Tabs: Each open file is represented by a tab at the top of the editor group.
        Split Editors: You can split the editor horizontally or vertically to view and edit multiple files side-by-side.
        Features: Syntax highlighting, code completion, error checking, and more.

   4. Status Bar:It is located at the bottom of the window.Provides information about the current state of the editor and workspace. It includes:
        Current File Information: Displays details like the current line and column number.
        Language Mode: Shows the language mode of the file being edited and allows changing it.
        Git Information: Displays the current branch and changes if Git is being used.
        Notifications: Shows notifications and alerts related to extensions, errors, and more.
        Customization: You can customize what is shown on the status bar through settings and extensions.


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   The command palette is a tool that provides quick access to various commands and features without needing to navigate through menus or remember complex keyboard shortcuts.


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Extensions play a crucial role in Visual Studio Code by enhancing its functionality and customizing the editor to fit specific development needs. They can add support for new programming languages, debuggers, and tools, as well as integrate with external services and improve overall productivity.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   The integrated terminal in Visual Studio Code (VS Code) allows you to run command-line tools directly within the editor, providing a seamless development experience. It is aware of the workspace context, meaning it opens in the root directory of your project. You can access it by using the command ctrl + shift + `


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   Creating Files and Folders

    Using the File Explorer
        Open File Explorer: Click the Explorer icon in the Activity Bar or press Ctrl+Shift+E (Windows/Linux) or Cmd+Shift+E (macOS).
        Create a New File: Right-click in the Explorer pane and select New File, or use the New File icon at the top of the Explorer pane. You can also use the keyboard shortcut Ctrl+N (Windows/Linux) or Cmd+N (macOS) to create a new untitled file.
        Create a New Folder: Right-click in the Explorer pane and select New Folder, or use the New Folder icon at the top of the Explorer pane.

    Using the Command Palette
        Create a New File: Open the Command Palette with Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (macOS), type File: New File, and press Enter.
        Create a New Folder: Open the Command Palette, type File: New Folder, and press Enter.

Opening Files and Folders

    Using the File Explorer
        Open a File: Double-click on a file in the Explorer pane.
        Open a Folder: Click the Open Folder button in the Explorer pane or use File > Open Folder from the menu.

    Using the Command Palette
        Open a File: Open the Command Palette, type File: Open File, and press Enter.
        Open a Folder: Open the Command Palette, type File: Open Folder, and press Enter.

    Using Drag and Drop
        Drag and drop files or folders from your file system into the VS Code window to open them.

Managing Files and Folders

    Rename Files and Folders
        Right-click on a file or folder in the Explorer pane and select Rename, or use the keyboard shortcut F2.

    Move Files and Folders
        Drag and drop files or folders within the Explorer pane to move them. You can also cut (Ctrl+X or Cmd+X) and paste (Ctrl+V or Cmd+V) files and folders.

    Delete Files and Folders
        Right-click on a file or folder in the Explorer pane and select Delete, or use the keyboard shortcut Delete.

Navigating Between Files and Directories Efficiently

    Quick Open
        Press Ctrl+P (Windows/Linux) or Cmd+P (macOS) to open the Quick Open dialog. Type the name of the file you want to open and press Enter.

    Go to Symbol
        Press Ctrl+Shift+O (Windows/Linux) or Cmd+Shift+O (macOS) to quickly navigate to a symbol in the current file.

    Go to Definition
        Right-click on a symbol and select Go to Definition, or press F12 to jump to the definition of a symbol.

    Breadcrumb Navigation
        Use the breadcrumbs at the top of the editor to navigate through the file hierarchy and symbols within the file.

    Explorer Shortcuts
        Press Ctrl+Shift+E (Windows/Linux) or Cmd+Shift+E (macOS) to focus the Explorer pane and use the arrow keys to navigate through the file tree.
        Press Alt+Left Arrow to navigate backward and Alt+Right Arrow to navigate forward in your file history.

    Side-by-Side Editing
        Split the editor by right-clicking on a file tab and selecting Split Right or Split Down. You can also use the keyboard shortcut Ctrl+\ (Windows/Linux) or Cmd+\ (macOS) to split the editor.

    Explorer Search
        Use the search functionality in the Explorer pane to find files and folders by name.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   
   In the settings click on view where you can access the customization settings


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

   you can create a new ssh ky and link it with github


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

