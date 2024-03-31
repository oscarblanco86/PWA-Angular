# PWA-Angular
This is just a test project for creating a PWA in Angular

I will use this as a template for building a couple of projects that i need to be installable, special thanks to FEWV, her video helped a lot to understand a couple of details I was missing.

As any project in github, go and take a look at the package.json and make sure about the dependencies. For this project I'm using Angular 17.3.2

I only have added @angular/pwa for enabling it.

I modified the icons settings in manifes.webmanifest.

And then package.json added the following line that build the project and enable a local server for testing, 

"start-pwa": "ng build --configuration production  && http-server -p 8080 -c-1 dist/pwa-angular/browser"

In case it works yo can use the files in dist/pwa-angular/browser/ to drop it into a site like replit, and test in your phone as a PWA.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.2.

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

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
