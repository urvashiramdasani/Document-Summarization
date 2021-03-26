## Contribution Steps

This documentation contains a set of guidelines to help you during the contribution process. Follow the below steps to contribute to this project.

1. Fork this project. This will create a Local Copy of this Repository on your Github Profile.
2. Enter below commands in your command prompt. Make sure you have git installed in your system.
```
$ git clone https://github.com/<your-username>/<repo-name>
$ cd Mined-Hackathon
$ git remote add upstream https://www.github.com/urvashiramdasani/Document-Summarization.git
```

3. Create a branch of your name
```
$ git checkout -b branch_name
```
4. Make changes to your local repository.
```
$ git add .
$ git commit -m "Commit-message"
$ git push -u origin Branch_Name
```
5. After pushing the changes to your local repository, create a pull request with title and description. Your changes will be pushed to the main project after review by all the members.

Note: If you have already forked the project, update your copy before working.
```
$ git remote update  
$ git checkout <branch-name>  
$ git rebase upstream/<branch-name>
```
