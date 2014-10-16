# Getting started

This scaffolding process can be used to generate the suggested structure of a typical .NET library.

## Cloning the project

This first thing to do is to clone or copy the ProjectScaffold repository to your own workspace.

## Initializing

In order to start the scaffolding process run 

    $ build.cmd // on windows
    $ build.sh  // on mono

During the init process you will be prompted for the name of your project and some other details: 

![alt text](img/init-script.png "Init script asking for project details")

The project structure will then be generated from templates.

## Build 

After initialization, you can 

- Open, edit, build and test using ``ProjectName.sln``
- Build and test release binaries using ``build.cmd`` or ``build.sh `` 
- Build and test release packages using ``build.cmd Release`` or ``build.sh Release`` 
 
## Further topics

* [Writing docs](writing-docs.html)
* [Release process](release-process.html)