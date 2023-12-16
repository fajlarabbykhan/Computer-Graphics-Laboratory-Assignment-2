# Computer-Graphics-Laboratory-Assignment-2
Welcome to the Set 1: Cricket Player Animation repository! This 3D Animation written in C++ using the GLUT library.



## To Run This Project
* Install CodeBlocks Application. (**Download Code::Blocks**) - http://www.sci.brooklyn.cuny.edu/~goetz/codeblocks/
* Download the GLUT bin file.(**Download file**) -https://user.xmission.com/~nate/glut.html
* Copy the glut.h file and paste it into the directory - "C:\ProgramFiles(x86)\CodeBlocks\MinGW\include\GL"
* Copy glut32.lib file and paste it into the directory - "C:\Program Files(x86)\CodeBlocks\MinGW\lib"
* Copy the glut32.dll and paste it into the directory - "C:\Windows\System"
* These are default locations, your paths may be different. But basically, you place the .lib and .h
files in the location of your compiler (in this case mingw). The .dll file goes in the windows
system directory.
* Now you are ready to start Code::Blocks and make a new project.
* Open up Code::Blocks. Start a new Project by going to File, New, Project.
* Select to make a new GLUT project and press Go to continue.
* Press Next at this menu
* Give a project title, and a location where to create the project and then press Next.
* Let Code::Blocks know where you stored your GL files, then press Next.
* Leave these unchanged, and press Finish.
* In the manager window (viewable by pressing Shift-F2), open up the sample source file by double
clicking on it. To make your program work, you will need to add at line 14:#include <windows.h>
* You will need to make a small change to the project's Build Options. Go to Project, Build Options.
* Select the Linker tab and press Add in the Link Libraries area.
* Press on the ... button to select a library to add. You need to add the glut32.lib library. Locate this from the directory you placed it in before.
* After you add the library, it will ask if you want to keep the path relative. Select No.
* Press OK to select the library.
* Press OK to close the Project's Build Options.
* Press F9 to do a Build & Run of your project.

## Here's an overview of the main components and functionalities:
* **Player Model:** - The drawPlayer function is responsible for rendering the 3D model of the cricket player. It includes a head, body, arms, legs, and a bat in hand.
* **Ball Model:** - The drawBall function renders a 3D sphere representing the cricket ball.
* **Throwing the Ball:** - The throwBall function is called when the spacebar key is pressed, initiating the ball-throwing animation.
* **Animation:** -  The animate function updates the animation state, including the rotation of the player's bat and the trajectory of the thrown ball.
* **Camera Control:** -  The keyboard_action function allows the user to control the camera's position using the number keys (1-6). The spacebar is used to throw the ball.
* **Initialization:** -  The init function sets up the initial OpenGL configurations.
* **Main Function** -  The main function initializes GLUT and sets up the main rendering loop. The program responds to display, idle, and keyboard events.
* **Main Function** -  The main function initializes GLUT and sets up the main rendering loop. The program responds to display, idle, and keyboard events.
* The code includes the necessary OpenGL and GLUT headers (windows.h, GL/glut.h) and defines various geometric shapes drawing functions (drawAxes, drawGrid, drawCylinder, drawCone, 
  drawSphere).
