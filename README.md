# angular-bootstrap
This repository demonstrate the use of bootstrap 4 with angular 7 

# Prequisites
- Node 10.9+
- Node Package Manager
- Angular CLI 8.0+
- Code Editor, I will be using Visual studio Code

# Steps
- Create a new angular project using following command in command prompt at a preferable location on your disk:
 `ng new <name of the project>`

- Cd into the new project directory and run the following command to open it in Visual studio code to navigate to the project location and open it in your favorite code editor
`Code .`

- Update to angular 8(if you new app is not using angular 8) by running the following command in command prompt at the same location where your angular app resides. If the following command does not work navigate to https://update.angular.io/ and fill the form form to get the necessary instruction for updating to angular 8
`ng update @angular/cli @angular/core`

- For upgrading to angular 8 you will need Node10.9+. If you get an error for node version upgrade it using following chocolatey command:
`choco upgrade nodejs`

- This will upgrade your node version to latest. Alternatively you can select nodejs LTS version using following command
`choco upgrade nodejs-lts`

- After successful installation import bootstrap.css in angular.json file present in the root folder of the project under styles node.

- Import the bootstrap css in style.css

- Now you can add a button on app.component.html file using the bootstrap classes
`<button class="btn btn-primary">Click me</button> `

- Run the application using the following command in the integrated terminal of visual studio or in the command prompt at the location where the project resides:
`ng serve`

This is serve you angular app at http://localhost:4200/. After successful compilation open a browser and navigate to http://localhost:4200/ to see a button with bootstrap classes.