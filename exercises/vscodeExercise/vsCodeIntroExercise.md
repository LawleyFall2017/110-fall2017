# Using Visual Studio Code with the HTML Essential Training Tutorial

The HTML Essentials tutorial that you'll be completing for next week uses an HTML editor called Brackets. Brackets is free, cross-platform, and available on the lab computers, so if you'd like to use that as your editor you can. 

Another free and cross-platform option available to you is Visual Studio Code (VS Code). All of the IGM lab computers have VS Code installed, and you can download it for your own Mac or PC from https://code.visualstudio.com/ . Because VS Code is my preferred HTML editor, it's the tool I'll use when demoing HTML and CSS in class, as well as what I'll use in any in-class exercises. In this exercise, you'll get a little bit of practice in how to use it.  

## Retrieving the Exercise Files From Lynda.com
Go to the main page for the Lynda.com tutorial for next week, [HTML Essential Training](https://www.lynda.com/Web-Development-tutorials/HTML-Essential-Training/170427-2.html?org=rit.edu). Click on the tab for "Exercise Files", download `Ex_Files_HTML_EssT.zip` to a local drive, and unzip the archive.

## Using VS Code to Open a Folder
While you can use VS Code to open and edit a single file, it works best if you start by pointing it to the folder you'll be working in. Launch VS Code, and then choose "Open Folder..." from the Welcome page or from the File menu. Select the Exercise_files folder from the unzipped archive, and choose Open. You should see something like this: 

![VS Code with Exercise Files](vscode-exercisefiles.png)

From here, you'll be able to access and edit any of the files referenced in the HTML Essential Training tutorial. 

## Using VS Code to Create a New HTML File
If you want to create a new file in the folder, you can choose File-->New File, press Ctrl-N, which will create a new file called Untitled-1. You can also hover over the folder name in the sidebar and click the New File icon, which will prompt you for a new file name. If you're planning to create an HTML or CSS file, you should immediately name it with an .html or .css file extension, so that the editor knows what syntax rules to use. 

Try it now: create a new file in the Exercise_files directory called test.html.  

One nice trick built into VS Code is the utility Emmet, which allows you to add HTML code using shortcuts. By far the most useful of those shortcuts for you right now will be the one that adds a basic HTML document structure for you. 

At the top of your blank document, type `html:5` and then press the tab key. (Do not add any spaces or new lines before pressing tab). Emmet should replace the text you typed with an HTML 5 document structure, like this: 

![VS Code HTML 5 Document](vscode-html5.png)

## Getting Credit for This Exercise
Before leaving class, grab a screenshot of the VS Code window with the new HTML file in it (like the one I posted above), and post it to the [Week 3/4 exercise dropbox folder in myCourses](https://mycourses.rit.edu/d2l/lms/dropbox/user/folder_submit_files.d2l?db=1461831&grpid=0&isprv=0&bp=0&ou=658493). (Windows 10 has a built-in program called "Snipping Tool" that makes it easy to grab just part of your screen, or you can use Ctrl-PrtScrn to get the whole screen.)

## Optional: Live Previewing Your HTML
VS Code does not have the ability to preview your HTML file built in by default. To see how your files look while you're working on the exercises, you will need to save the file to disk, and then use File-->Open in your browser of choice to preview your HTML files. 

However, there is an extension that you can install to enable live previewing in VS Code. Click on the extensions icon in the left pane, and type in `Preview on Web Server` to search for it. Click the Install button, and then the reload button. Now you should be able to type Ctrl-Shift-P to bring up a live preview of your code, or Ctrl-Shift-L to open it in your default browser. 
