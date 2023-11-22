# InsightLabs

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Project creating steps

1. Install Node.js
2. Install Angular CLI
3. Create a Standalone TypeScript Project
4. Create a new project of ype ASP.NET Core Web Application
1. Set the startup order for the projects. Backend first, then frontend.
   1. Right click on the solution and select Properties
   1. Select Common Properties -> Startup Project
   1. Select Multiple startup projects
   1. Set the Action for the Backend project to Start
   1. Set the Action for the Frontend project to Start
   1. Click Apply and OK
1. Deactivate the browser opening when starting the backend project
   1. Right click on the Backend project and select Properties
   1. Select the Debug tab
   1. Uncheck the Launch browser checkbox
   1. Click Apply and OK
1. Set the default backend port in the frontend
   1. Open the backend file Properties/launchSettings.json
   1. Copy the port number from the applicationUrl property
   1. Open the file src/proxy.conf.js
   1. Set the port in the apiUrl property

