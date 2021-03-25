# am-docs
A user guide for the Integrity and Assurance Module

To update this user guide you need to install Python and mkdocs

For more info on how to install mkdocs you can check their official guide:
https://www.mkdocs.org/#installation

## Updating the User Guide
The docs folder contains the user guide as sections distributed across md files, to update a section you need to update it's corresponding md file, you can refer to the mkdocs on how to write in markdown:
https://www.mkdocs.org/user-guide/writing-your-docs/


## Creating new section

To create a new section you need to add a new md file in the docs folder and add a new entry for it in the pages section in the mkdocs.yml file

## Run Locally

To check your changes locally before pushing them you need to build and run your docs by execute the folllowing commands:

    mkdocs build
    mkdocs serve

## Deploy

To deploy the docs you need to execute the following command:
     
    mkdocs gh-deploy
    
for more details you can refer to the official mkdocs: https://www.mkdocs.org/user-guide/deploying-your-docs/
