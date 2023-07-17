**Angular Introduction**

Angular is a popular open-source framework for building web applications. It was developed by Google and is widely used by developers around the world. Angular allows developers to create dynamic, single-page applications (SPAs) that provide a smooth and responsive user experience.

Angular is based on TypeScript, a statically typed superset of JavaScript, which brings additional features and capabilities to JavaScript. It follows the component-based architecture, where the application is divided into reusable and modular components. These components encapsulate the HTML, CSS, and TypeScript code required for specific functionalities and can be easily reused across different parts of the application.

One of the key features of Angular is its powerful data binding capabilities, which enable the synchronization of data between the application's components and the underlying data model. It supports both one-way and two-way data binding, allowing for efficient handling of user input and automatic updates of the user interface.

Angular also provides a rich set of tools and features for handling common web development tasks, such as routing, form validation, and dependency injection. It includes a comprehensive command-line interface (CLI) that helps streamline the development process by automating various tasks, such as project setup, code generation, and testing.

Overall, Angular is a robust framework that promotes efficient development practices, code reusability, and maintainability. It has a large and active community, which contributes to its continuous improvement and provides a vast ecosystem of third-party libraries and extensions.

**Electron Introduction**

Electron is an open-source framework that allows developers to build cross-platform desktop applications using web technologies such as HTML, CSS, and JavaScript. It was developed by GitHub and is based on Node.js and Chromium.

With Electron, developers can create desktop applications using familiar web development technologies, eliminating the need to learn platform-specific languages or frameworks. This enables developers to leverage their existing web development skills to build powerful and feature-rich desktop applications.

Electron works by combining a web browser (based on Chromium) with Node.js, providing access to both browser APIs and Node.js APIs. This allows developers to use web technologies to create the user interface of the application and access operating system functionalities through Node.js. It essentially packages web applications into standalone executable files that can run on various operating systems such as Windows, macOS, and Linux.

One of the advantages of Electron is its ability to create cross-platform applications. Developers can write code once and deploy it on multiple operating systems without the need for significant modifications. This greatly simplifies the development and maintenance process for desktop applications.

Electron has gained popularity because of its flexibility, ease of use, and the ability to create visually appealing desktop applications using web technologies. Many popular applications, including Visual Studio Code, Slack, and Discord, are built using Electron.

**Angular CLI Installtion Guideline**
To install the Angular CLI (Command Line Interface), you can follow these steps:

Ensure that you have Node.js installed on your system. Angular CLI requires Node.js version 12.14 or later. You can download Node.js from the official website (https://nodejs.org) and follow the installation instructions for your operating system.

Once Node.js is installed, open a command prompt or terminal window.

Install the Angular CLI globally by running the following command:

npm install -g @angular/cli
The -g flag ensures that the Angular CLI is installed globally on your system, allowing you to use it from any directory.

Wait for the installation to complete. This process may take a few minutes, depending on your internet connection.

After the installation is finished, you can verify if the Angular CLI is installed correctly by running the following command:

ng version

This command will display the installed version of Angular CLI, along with the version of Angular and other related packages.

If the installation and verification steps are successful, you have successfully installed the Angular CLI on your system. You can now use the CLI to create new Angular projects, generate components, services, and more, as well as build and serve your Angular applications.

**Steps to Install and Configure application..**
Prerequisites :
1. Need to have mongodb installed
2. We can have editor for data management(i have used mongo management studio)
3. Angular cli to be installed
4. Latest version of nodejs required (8+)

Steps to configure connection string :
1. Open mongo management studio and copy the url (default will be )

Steps to run the project :
1 - Open the project using the editor (i have used VS CODE)
2 - then run command (npm install)
3 - Install additional package by using command (npm install -g electron)
4 - Open three different terminal window from the code editor
	(A) - type command (ng serve)
	(B) - type command (electron .)
	(C) - go to server directory by using command (cd src) and (cd server) and type command (node server.js) which is used to run the nodejs app

	
After running above two commands, it will automatically open the electron desktop app.

View our Case Studies here https://bit.ly/44JIa9i
Contact us for Angular Electron App Development. https://www.epistic.net/contactus 

