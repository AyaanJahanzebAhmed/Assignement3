MVC Model-Views-Controller The application and its development are divided into three interconnected parts.

Model: Model represents the structure of data, the format and the constraints with which it is stored.
It maintains the data of the application. Essentially, it is the database part of the application.

View: View is what is presented to the user.
Views utilize the Model and present data in a form in which the user wants.
A user can also be allowed to make changes to the data presented to the user.
They consist of static and dynamic pages which are rendered or sent to the user when the user requests them.

Controller: Controller controls the requests of the user and then generates appropriate response which is fed to the viewer.
Typically, the user interacts with the View, which in turn generates the appropriate request, this request will be handled by a controller.
The controller renders the appropriate view with the model data as a response.

Advantages:
Faster Development Process Ability To Provide Multiple Views
Support For Asynchronous Technique Modification
Does Not Affect The Entire Model
MVC Model Returns The Data Without Formatting
SEO Friendly Development Platform



You can debug Node.js application using various tools including following:

Core Node.js debugger
Node Inspector
Built-in debugger in IDEs

Core Node.js Debugger:
Node.js provides built-in non-graphic debugging tool that can be used on all platforms. It provides different commands for debugging Node.js application.
The command [ node debug app.js] starts the debugger. 
