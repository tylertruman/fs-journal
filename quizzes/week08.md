# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The package.json file is used for holding various metadata. It talks to npm that allows it to handle the projects dependencies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
The package.json should be in the root directory so that it can interact with all necessary files.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
env files
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
console.log and logger.log
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Clone your GitHub repo, make changes & commit them, login to Heroku account, set remote for your project, and push to Heroku master to deploy your updates.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching allows you and your teammates to work on code at the same time, without duplication. It saves time, screw ups, and is more efficient.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
After checks, but before merging code to the main branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging
```