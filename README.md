# TekProjekt3
Technical thesis on RSS 

This is a cool project, but it might feel like slavery.

To "compile" the LaTeX files, you can upload your files to Overleaf or install a free [LaTeX distribution](https://www.latex-project.org)

To make things easier for you here is a small list of instructions for team members. 
You should recognize most of them. You can try with one of your friends first before trying with all the group.



## First time:

In GitHub:

- Go to: [https://github.com/SebastianPaling/TekProjekt3](https://github.com/SebastianPaling/TekProjekt3) and select "Fork" at the top right. It will make a copy on your own account.
- Go to the project in your own account and select the green button (Clone or Download) and copy the URL (little icon with a clipboard and an arrow).

On your computer

- Go to the git command window or terminal and navigate to the directory where you want to have the folder (cd, change directory; use the Tab key to autocomplete the directory name). 
- Type: ```git clone ``` and paste the URL that is in the clipboard).
- Change directory to TekProjekt3 and you should see your files there.
- Type: ```git remote add upstream https://github.com/SebastianPaling/TekProjekt3```

__________________________________________________________
## Working weekly workflow:

- Modify the files that are yours (not other people's files even if you have them).
- ```git status``` to see which files had been modified.
- ```git add *``` to add all the modified files to the stage area.
- ```git status``` to see the stage files.
- ```git commit``` to commit the staged files to the local repository.
	- ```i``` to enter insert mode. Type your short text.
	- ESC
	- ```:wq``` to write or save the comment and quit.
- ```git push origin master```
Go to GitHub and make a Pull Request on Fridays. Do not work during the weekend (except Sebastian)

On Mondays,

- ```git fetch upstream master``` to get the complete updated report.
- ```git merge``` to merge the report with your files.

