# Hack the North 2021
This project aims to create a healthier work environments for those that spend lots of time on their computers during the day. From reminding you take eye breaks, to making sure you are drinking enough water, Progra-fit is the tool for you.

# Install instructions
1. Make sure that Node.js is installed. To check if it is, type `npm` in your terminal. If you get an error, it's not installed. If you get a bunch of text, it is.
1. Navigate into your cloned fork of the repository and type `npm install`. This will install all of the required dependencies for React.
1. To run the project, type `npm start`.

# Contributing Instructions
In order to contribute to this project, the following steps must be done in order to do so successfully. Everything that you write has to come through me (i.e a pull request) that can then be reviewed and put into the project. If you have any questions or queries, ask before continuing. 

1. Create a fork of the project.
1. Clone your fork (your version of the repository) locally.
3. Navigate into your cloned directory. `cd hack-the-north`
4. Add the upstream (if it doesn't already exist): `git remote add upstream git@github.com:Toranian/hack-the-north.git`
5. Get the latest changes: `git pull upstream main`
6. Create a new branch with a name specific to the issue or feature or bug you will be working on: `git checkout -b yourbranchname`
7. Write code!
8. Commit your changes (you may need to `git add .` if you created any new files that need to be tracked).  If your changes resolve a specific [issue on github](https://github.com/Toranian/hack-the-north/issues), then add "Closes #123" to the commit where 123 is the issue number:  
`git commit -am "Useful description of your changes; Closes #123"`
9. Make sure your develop branch is up to date again and rebase onto any changes that have been made upstream since you started the branch: `git pull upstream main --rebase`  (this command joins several steps: updating your local develop branch, and then rebasing your current feature branch on top of the updated develop branch)
10. Push your branch to your fork of the project on github (the first time you do this, it will create the branch on github for you): `git push origin yourbranchname`
11. Go to your fork of the repository on GitHub (you should see a dropdown allowing you to select your branch)
12. Select your recently pushed branch and create a pull request (you should see a button for this)
![image](https://user-images.githubusercontent.com/10604391/125674000-d02eb7a0-b85d-4c8f-b8dd-2b144e274f7d.png)

10. Complete pull request.
11. Start work on another feature by checking out the develop branch again: `git checkout develop`
12. Start again at Step 3 and repeat!

# Contributors
1. Ryan Nicholas Permana (h4ppyturt1e)
