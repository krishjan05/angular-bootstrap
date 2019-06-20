# angular-bootstrap
This repository demonstrate the use of bootstrap 4 with angular 8 

# Environment
- Operating System: Windows 10
- Chocolatey(pakage manager for windows)

# Prequisites
- Node 10.9+
- Node Package Manager
- Angular CLI 8.0+
- Visual studio Code

# Steps
- Create a new angular project using the following command in command prompt at a preferable location on your disk. For this command to execute successfully you should have angular CLI installed on your machine:
 `ng new <name of the project>`

- Navigate into the new project directory and run the following command to open it in Visual Studio Code:
`Code .`

- If your application is created using angular 7 you can update to angular 8 by executing the following command. In case the following command does not work navigate to https://update.angular.io/ and fill the form to get the necessary instruction for updating to angular 8:
`ng update @angular/cli @angular/core`

- For upgrading to angular 8 you will need Node10.9+. If you get an error for node version, then upgrade using following chocolatey command(chocolatey should already be installed in you machine):
`choco upgrade nodejs`

- This will upgrade your node version to latest. Alternatively you can select nodejs LTS version using following command:
`choco upgrade nodejs-lts`

- For installing bootstrap from npm, use the following command:
`npm install --save bootstrap@4.3.1`

- After successful installation, import bootstrap.css in angular.json file present in the root folder of the project under styles node

- Now you can add a button on app.component.html file using the bootstrap classes
`<button class="btn btn-primary">Click me</button> `

- Run the application using ng serve command
`ng serve`

This will serve your angular application at http://localhost:4200/. After successful compilation, open a browser and navigate to http://localhost:4200/ to see a button with bootstrap classes.