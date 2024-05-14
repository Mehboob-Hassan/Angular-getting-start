
## ANGULAR FOR BEGINNERS
# Project Title
Angular First Project "The Todo List"


## Introduction

AngularJS for beginners is a popular JavaScript framework trusted by developers worldwide for creating robust and powerful MVC-based web applications. With AngularJS, you can divide the presentation layer, the data layer, and the layer containing the business logic. It extends its syntax to create different application components using HTML as a template language. The features of data binding and dependency injection also aid in reducing the amount of code.

## Requirments 
Node JS
NPM

## Angular CLI
The Angular CLI is a command-line interface tool that you use to initialize, develop, scaffold, and maintain Angular applications directly from a command shell.

## Start Devloping Angular App
## Installation

Install Angular CLI with npm

```bash
  npm install -g @angular/cli
  
```

Create A New Basic Angular App

```bash
  ng new my-first-project

```

? Would you like to add Angular routing?
(Type y and enter) 

Select CSS and Enter

```bash
  cd my-first-project
```

After installation get successfull, you get Folder named my-first-project, Open it in VS Code.

Run The Newely Created App
```bash
  ng serve
```

You will see the Angular JS Welcome Page. This page serve as the defaul Page for newely created Angular App.


## File Structure
src/index.html is Enrty Point of the project.

+ In index.html there is component 
  
  <app-root></app-root>
Which is Actually Coming from  src/App/app.component.html

### src/App contains important files
  + app.component.html
    
    ~ Contains Html of the Component
  + app.component.css
    
    ~ Contains CSS of the Component
  + app.component.ts
    
    ~ Typescript file of the component and Contains the business logic of the Component. (It is Important of all)

  + app.component.spec.ts
    
    ~ Contains Testing Stuff of the Component
  + app.module.ts

    ~ Entry Point of the component
## Installing Bootstrap and JQuery in the App

: In Terminal

```bash
  npm install bootstrap
  npm install jquery
```

### Open Angular.json File
(In architect : {
    build: {

        styles : {
            "src/styles.css"
            "./node_modules/bootstrap/dist/css/bootstrap.min.css"
        }
        scripts : {
            "./node_modules/bootstrap/dist/js/bootstrap.min.js"
            "./node_modules/jquery/dist/jquery.js"
        }
    }
})

Now Restart the App by running ``` ng serve ``` command

## Creating New Component

run the command 

```bash
    ng generate component MyComponents/todos 
```

This will create a new folder: src/MyComponents/todos
