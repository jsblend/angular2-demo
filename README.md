A Fully Functional Angular 2 Demo Application
===========================================================

Slides: [https://luixaviles.github.io/angular2-demo/](https://luixaviles.github.io/angular2-demo/)

## Description

This demo is based on [puppy-love](https://github.com/kara/puppy-love) project.
The features of this project includes:

* A Service definition, so that HTTP calls can be performed to display initial data.
* A custom model definition, to allow map used data.
* Dependency Injection.
* Two way data binding(Using `[(ngModel)]`).
* Use of `*ngIf` and `*ngFor` into provided form.
* Events triggering after click on a button. `(click)`
* Use of Material Design components for Angular 2

## Updates
**NOTE**: Project updated to latest `Angular` version: `6.1.9`

The app uses [Random user Generator](https://randomuser.me) to show initial data.
This demo was presented in `Google I/O Extended` event in Cochabamba, Bolivia(July, 2016).

## Screenshots
![](/screenshots/main-page.png?raw=true)
![](/screenshots/registration-form.png?raw=true)
![](/screenshots/new-input.png?raw=true)

## Prerequisites

First, ensure you have the following installed:

1. NodeJS - Download and Install [NodeJS](http://http://nodejs.org)
2. Git - Download and Install [Git](http://git-scm.com)

After that, use `Git bash` to run all commands if you are on Windows platform.

## Install dependencies

Install `angular-cli`:

```
npm install -g @angular/cli
```

For more details about `Angular CLI`, please refer to: [https://cli.angular.io/](https://cli.angular.io/)

## Run the project

To run the demo project locally, just install dependencies and run the application in development mode:

```bash
$ npm install
$ ng serve -o
```

Now you can open your browser and load [http://localhost:4200](http://localhost:4200)

Try the code, verify the current behavior. Update the code and configurations and test again!

Please feel free to contact me if you have any question.

## License

MIT
