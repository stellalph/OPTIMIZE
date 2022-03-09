1) TASK

This homework assignment is to refactor an exisiting site to make it more accessible for a marketing agency.  Web accessibility is an important consideration for business to ensure that people with disabilities can access a website using assistive technologies like video caption, screen readers, and braille keyboards.  The purpose of this task to check that the links are functioning properly and the code meets the acceptance criteria. Therefore, I give my repository a name "Optimization". 


2) DEPLOYMENT

GitHub is a free cloud drive that allows to store all our projects and codes.  In case, someone accidentally deleted the work while I decided to go for a break.  Hitting undo is no longer an option.  This software allows us to go back in time.  This free cloud drive is a life-saver!  

There are two ways to create a repository:-

   i)  Create the remote repository on GitHub first and then clone it to my local machine, that is, click on the green icon NEW on the top right corner of the GitHub screen, give a name to new repository and add a README file and create repository.  Copy the CODE of the SSH key and I will do the git clone "my URL" command, and then making sure that I am in the project directory and the commands required, that is git add ., git command, and git push.
   
   ii) I choose the second option as I already have the files for deployment to GitHub.  The steps taken:
   a.  Navigate to my project directory using Git Bash as I have learned in class:-
           - git init (turning the directory into a Git repository)
           - git status (to check that status of my files)
           - git add . (adding my files)
           - git commit -m "initial commit"
          
      Log on to the GitHub (my account) and create the new repository as for step (i)
      Copy the code and making sure not to click on the README file since I am importing the files.

               git remote add origin < SSH URL> (as I have a SSH key)
               git branch - M main
               git push -u origin main


    b.  As I worked through the files with changes to my code and README file, the commands to use would be git push origin main (when changes are made in the local repository or git pull origin main (when changes are made in the remote repository)
    

    iii) The URL of the GitHub repository is https://github.com/stellalph/OPTIMIZE.git and 
         my URL of the deployed application is https://stellalph.github.io/OPTIMIZE/


  3) CODE REFRACTOR

The following steps I have taken to refactor the code (improving it without changing what it does) are:-


        - structure according to the HTML, making sure that there are identifiable HTML elements and they flow in a sequential order, that is,
          header, content or section, aside and footer
        - to ensure that the links are functioning correctly
        - simplify the links removing the extra folder
        - re-link to the images for the header
        - adding commentary to the title, header, contents or section
        - adding alt attributes to define a text alternative to the image being displayed.  This alt attribute is a great impact on both search 
          engines and users with text-only browsers. An example would be the people that use text-to speech software due to vision impairment.
          only browsers.  This targets at this accessbility as the theme of this homework assignment.
        - short commentary added to the CSS file to know where the CSS selectors are located.
        - making sure that the CSS file is in sequential order as the HTML file
        - Consolidating the CSS selectors in the style.css file.

       