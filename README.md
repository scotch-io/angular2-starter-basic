# Angular 2 Starter

The simplest starter kit you can find. Not trying to overcomplicate things, just get up and running with Angular 2. 

All the essentials. None of the extras. Takes a lot of cues from the Angular [quickstart](https://angular.io/docs/ts/latest/quickstart.html).

> This is a great starter for getting straight to the Angular 2 and not dealing with any of the setup.

## About

- **Transpiling ES6**: TypeScript compiled via npm script
    + Compiled from the `app/` folder to the `dist/` folder
- **Loading Imports**: SystemJS is the loader 
- **Serving**: [lite-server](https://github.com/johnpapa/lite-server) serves our dev server

## Requirements

- [node and npm](https://nodejs.org)

## Installation

- Clone the repo: `git clone git@github.com:scotch-io/angular2-starter-basic`
- Choose the new directory: `cd angular2-starter-basic`
- Install dependencies: `npm install`
- Start the app: `npm start`
- View the app: <http://localhost:3000>

## Usage

- The Angular application is found in the `app/` directory

## Caveats

- This is a very basic starter. If you want to use this in production, you're going to need to build out a lot more parts. Parts like:
- Templates are referenced absolutely, which doesn't scale well.
    + You'd want to have your build system help with referencing templates relatively. Better to not absolutely reference them as they could get lost in build systems in larger apps.

## More Production Ready Setup

- Use the [Angular CLI](https://cli.angular.io/)