# PhysicianAssistant

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.11.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.


## Run application as a docker container

1. **Install Docker Engine**:
   For instructions on how to install Docker Engine on your machine, see: https://docs.docker.com/engine/install/


2. **Build the image**:
    ```sh
    docker build -t physician-assistant .
    ```

3. **Run the Application**:
    ```sh
    docker run -d --name physician-assistant-ui -p 4200:4200 physician-assistant 
    `
# HELIO-Smart-physician
