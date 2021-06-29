# ****Revisions In The Cloud***


## WHAT IT MEANS

- Once one clones a repo to their local drive, they can work on their code in a code
editor like VS Code. What's really cool is once it's locally stored, you can make changes
and then upload your repo with changes to the cloud later on. This saves you from having to 
constantly grab something from the server (cloud) and work can be completed while offline. 
All this is done through version control,  which takes small snapshots as you work called 
commits.

This system ensures there is redundancy built into the process. Because you are not relying
solely on the server for version control and storage of your repo, if the server goes down
your code is stored locally on your machine. You are good to go. 

This whole workflow allows developers to work on different parts of the project and upload
them to a shared space like GitHub. There the code can be accessed by everyone. A very
good thing!

## HOW THE CHANGES GET TO THE CLOUD

- In a nutshell, the process can be summed up in the ACP process:

### ADD

#### COMMIT

### PUSH

What you are doing in this process is staging your code, committing the changes, and then
pushing it to a chosen branch in the cloud. Below you will see the actual code:

' git add .'  < Adds everything that was changed to staging.

'commit -m "Adding a strike-through"'  < Commits the code and adds a note for the change.

' git push origin main'  <  Pushes the code with committed changes to the branch in the cloud.










