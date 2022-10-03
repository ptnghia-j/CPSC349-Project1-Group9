# CPSC349-Project1-Group9

Fork CPSC349-Project1-Group9 repository and clone it to your local machine so we can collaborate on the project

This set up already used the command ```npm install``` which installs all modules listed as dependencies in package.json (defined in professors's package.json file from the origin repo). I believe we don't need to run this again

Run ```npm start```, will run predefined command specified in the "start" property of a package's "scripts" object (also in package.json file). I think we will run this when we make change to templates and/or need to re-run eleventy (it invokes the eleventy and also the npm test as defined in script), it will open the newly generated site.

To validate the generated HTML:

```shell-session
npm test
```

Some of the hyperlink in the original readme linking to the documented websites (for reference only): <br>
https://www.11ty.dev/ <br>
http://localhost:8080/ <br>
https://validator.nu/ <br>



