
Creating Your First Jenkins Job Integrated Into a Github project

Run the jenkins server, and go to http://localhost:8080.
After the login you need to create a job, and then name it.
The project should be in freestyle mode.
Enter the project details in the General tab, including the name and description of the project that needs to be tested.
Under Source Code Management(SCM) tab,Select Git as a repository source and enter your Git Repository URL.
Go to the Build section and click on the Add build step.
Then, “Execute Shell” and add the commands you want to execute during the build process.
When you have entered all the data,Click Apply then Save the project.
On the left-hand side panel, click the Build Now button to build the source code
Click on the Build on the history, and it takes you to another page. On that page click console output to see you results.

![Screenshot from 2022-06-21 21-55-44](https://user-images.githubusercontent.com/33745365/174879589-ee94b478-5ce6-4a30-89f8-c556fe16b13b.png)

![Screenshot from 2022-06-21 21-55-30](https://user-images.githubusercontent.com/33745365/174879672-d197e7bf-8b89-45af-900e-2d5e1318862a.png)

