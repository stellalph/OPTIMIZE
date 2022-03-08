1) TASK

This homework assignment is to refactor an exisiting site to make it more accessible for a marketing agency.  Web accessibility is an important consideration for business to ensure that people with disabilities can access a website using assistive technologies like video caption, screen readers, and braille keyboards.  The existing code must include this feature which the layout is to be designed to include some of the elements for resolution smaller than 768px and responsive for the web application being optimised for any screen size.  Therefore, I give my repository a name "Optimization". 

2) DEPLOYMENT

GitHub is a free cloud drive that allows to store all our projects and codes.  In case, someone accidentally deleted our work while I decided to go for a break.  Hitting undo is no longer an option.  This software allows us to go back in time.  A life-saver!  

There are two ways to create a repository:-
   i)  Create the remote repository on GitHub first and then clone it to my local machine, that is, the green icon NEW on the top right corner of the GitHub screen, give the name to repository and add a README file and create repository.  Copy the CODE of the SSH key and I will do the git clone "my URL", and then making sure that I am in the project directory and the commands required, that is git add, git command, and git push.
   ii) I choose the second option as I already have the files for deployment to GitHub.  The steps taken:
       a.  Navigate to my project directory using Git Bash as I have learned in class:-
           > git init (turning the directory into a Git repository)
           > git status (to check that status of my files)
           > git add . (adding my files)
           > git commit -m "initial commit"
          Log on to the GitHub (my account) and create the new repository as for step (i)
           Copy the code and making sure not to click on the README file since I am importing the file.
           ie  git remote add origin < SSH URL> (as I have a SSH key)
               git branch - M main
               git push -u origin main
       b.  As I worked through the files with changes to my code and README file, the commands to use would be git push origin main or git pull origin main.