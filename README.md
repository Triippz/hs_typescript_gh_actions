# getting-started-project-template

This project is an example how to use Typescript with HubSpot Projects. This uses rimraf and copyfiles to
move all non-ts/js files to the dist directory. When compiling the TS files, it will move the compiled js files and any existing JS files to their appropriate directories.
The dist directory is a 1:1 match of what is in /project with the exception of the ts files.



Place your portal id and personal access key in your secrets -> actions

````
HUBSPOT_PERSONAL_ACCESS_KEY

HUBSPOT_PORTAL_ID
````
