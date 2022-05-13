:warning: Everything between << >> needs to be replaced (remove << >> after replacing)
# CS110 Project Proposal
# 3D Renderer
## CS 110 Final Project
### Spring 2022
### [Assignment Description](https://docs.google.com/document/d/1H4R6yLL7som1lglyXWZ04RvTp_RvRFCCBn6sqv-82ps/edit#)

https://replit.com/join/xbxbvxomvy-thierry-jj

<< [link to demo presentation slides](#) >>

### Team: in dog beers weve only had one
#### Thierry Martineau, Luke Zink, Nhat Dinh Nguyen

***

## Project Description *(Software Lead)*

This is a 3D Renderer written in python using pygame. When the user runs the program, they are presented with a few objects they can render. When the user clicks on the object they want to render, that object is rendered on screen. There is also a FOV slider on screen that the user can slide left or right, left decreasing the FOV and right increasing the F0V.

This renderer reads .obj files in the asset folder, and uses the data from a file to create a list of projected triangles onto 2D space. This is then displayed on screen.

***    

## User Interface Design *(Front End Specialist)*

* << A wireframe or drawing of the user interface concept along with a short description of the interface. You should have one for each screen in your program. >>
    * For example, if your program has a start screen, game screen, and game over screen, you should include a wireframe / screenshot / drawing of each one and a short description of the components
* << You should also have a screenshot of each screen for your final GUI >>

*  ![Interface](concept.png)

***        

## Program Design *(Backend Specialist)*

* Non-Standard libraries
    * << You should have a list of any additional libraries or modules used (pygame, request) beyond non-standard python. >>
    * For each additional module you should include
        * url for the module documentation
        * a short description of the module
* Class Interface Design
    * << A simple drawing that shows the class relationships in your code (see below for an example). >>
        * ![class diagram](wip.png)
    * This does not need to be overly detailed, but should show how your code fits into the Model/View/Controller paradigm.
* Classes
    * << You should have a list of each of your classes with a description. >>

## Project Structure *(Software Lead)*

The Project is broken down into the following file structure:

* main.py
* src
    * <all of your python files should go here>
* assets
    * <all of your media, i.e. images, font files, etc, should go here)
* etc
    * <This is a catch all folder for things that are not part of your project, but you want to keep with your project. Your demo video should go here.>

***

## Tasks and Responsibilities *(Software Lead)*

   * You must outline the team member roles and who was responsible for each class/method, both individual and collaborative.
   
### Software Lead - Thierry Martineau

   Responsible for overall project direction and assisted in the programing of both the Graphical User Interface and the Renderer.

### Front End Specialist - Luke Zink

   Responsible for the creation of the Graphical User Interface, including buttons and the FOV slider.

### Back End Specialist - Nhat-Dinh Nguyen

   Responsible for the theory, mathematics, and programming of the 3D Renderer.

## Testing *(Software Lead)*

* << Describe your testing strategy for your project. >>
    * << Example >>

## ATP

| Step                  | Procedure     | Expected Results  | Actual Results |
| ----------------------|:-------------:| -----------------:| -------------- |
|  1  | Click on Run button in Replit  | Program starts and a window appears with a menu, there are buttons that coorespond to a scene or object that can be rendered  |            |
|  2  | Click on  object to render | The  object is rendered in the window, with a set of buttons and controls that can alter the scene |                  |
|  3  | Move FOV slider | The FOV of the camera is changed according to the slider | |
etc...
