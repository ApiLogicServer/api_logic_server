# Welcome to API Logic Server

You are currently in an empty project, pre-configured for the [ApiLogicServer](https://github.com/valhuber/ApiLogicServer/blob/main/README.md) Docker container
(note the `.devcontainer` and `Dockerfile`).

&nbsp;

## Create

To create your project:
1. Open a terminal window
2. Enter the following command:

```
ApiLogicServer create --project_name=.  # include the period - it designates the current directory
```

You will then be asked to supply the `db_url`
* Press RETURN to use the sample project

The project will be created in your current directory (e.g, `api_logic_server`).
* You will see this readme replaced with the created projects' readme - the tutorial.  This will show how to run and customize the created project.

### Using your own database
After you have explored the sample, try it with your own database by specifying an appropriate `db_url`.   For examples, enter the Terminal command: 
```
ApiLogicServer examples
```
&nbsp;

## Run
To run your project, use the created launch configurations to start the API or the Basic Web App.

> If you are using your own database, you will need to [configure the Web App](https://github.com/valhuber/ApiLogicServer/wiki/Working-with-Flask-AppBuilder).



&nbsp;&nbsp;
# Overview

ApiLogicServer creates database api projects:

* Created projects are instantly executable, providing a database API and a web app

* Customize the projects in an IDE such as VS Code

   * In particular, use VS Code to create logic using spreadsheet-like rules

* Created projects utilize Python from the container, eliminating the need to install Python

Usage is described in the video, below:

[![Using VS Code](https://github.com/valhuber/ApiLogicServer/blob/main/images/creates-and-runs-video-vsc.png?raw=true?raw=true)](https://youtu.be/-C5O453Q-Mc "Using VS Code with the ApiLogicServer container")
