      ___           ___           ___     
     /\__\         /\  \         /\  \    
    /:/  /        /::\  \       /::\  \   
   /:/__/        /:/\:\  \     /:/\:\  \  
  /::\  \ ___   /::\~\:\  \   /:/  \:\  \ 
 /:/\:\  /\__\ /:/\:\ \:\__\ /:/__/ \:\__\
 \/__\:\/:/  / \/__\:\/:/  / \:\  \  \/__/
      \::/  /       \::/  /   \:\  \      
      /:/  /        /:/  /     \:\  \     
     /:/  /        /:/  /       \:\__\    
     \/__/         \/__/         \/__/    

Welcome to the Home Automation Console (H.A.C.)

This app will show you a console of available houses with each house owners name.
By clicking on now of the names you will be taken to a new page via Angular routing where you will see all the rooms that exist in the household. Each room has it’s own temperature and humidity that is asynchrony updated with a 2 second interval.

A back button will take you back to the last visited.


INSTALL:
In order to run this app you must have npm installed.
You can check if node/npm is installed by typing the following in the terminal:

node -v
npm -v

If you get a version response then you have these installed. If not then do the following
procedure in the terminal:

npm install npm@latest -g


Then install Angular by typing the following:

npm install -g @angular/cli


The app as a lodash lib swell, but this is locally installed in the app dir and therefore you don’t have to do anything.


RUN:
To run the app go to the app dir and type in the terminal:

ng serve

Then type the following URL in the browser: localhost:4200




# HomeAutomationApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
