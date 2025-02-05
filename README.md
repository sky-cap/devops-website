Cody Ackerson Demonstration of deploying website to github pages.

The purpose of this repository is to practice and learn skills related to DevOps and automation of the SDLC.
The contents of this website are not as important as the background steps taken when updating and managing this site. 

This site was created locally first - followed by initializing a git repository via the shell.
After that a remote connection was made to my GitHub account and pushed up to the main branch.
Git Pages was setup to host the site for quick management.

No errors occured during the setup - smooth as butter so far!


Well Well Github Actions Workflow:
I followed the steps in the assignment and everything worked great! Then I attempted to add an on pull request to main witht he conditional of if it was merged and everything broke. I received the error that the feature branch could not deploy due to my environment. 

I then found out that when I merged into the main, the deploy ran anyways - so for the sake of this assignment it works fine. However, I would like to setup an action that stops any code from being directly pushed to the main. I am sure this is an option (as it is a common desire) and most likely available with Actions, but I am unaware of this yet. 

INSTRUCTIONS: To run this deployment, simply push code to the main branch, or create a pull request to the main branch and merge it. That is it! uto update of the webpage!
