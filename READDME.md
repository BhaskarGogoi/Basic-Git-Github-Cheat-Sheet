
# Git & Github Cheatsheet

Basic information of publishing a project to github using git cli. 




## Author

 [@Bhaskarjyoti Gogoi](https://www.github.com/BhaskarGogoi)

  
## Documentation

### Publish a project to github

- git config --global user.name “your name"
Set a name that is identifiable for credit when review version history.

- git config --global user.email “your email”
Set an email address that will be associated with each history marker.

- git init
Initialize an existing directory as a Git repository

- git add .
Add file to staging area.

- git status
Show modified files in working directory, staged for your next commit.

- git commit -m “Message”
Commit your staged content as a new commit snapshot.

- git remote add origin <url>
url: the github repository that you had created for the project to publish.

- git push origin master
To push all the commits to github.

###  Removing a commit from the history of a project

- git log 
It will show all the history of commits and also a unique commit id.

- git reset <id>
Put the id that you got from the log.

