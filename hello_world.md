## Hello world!

Teftelka is pretty cute cat! :)

Yep, that's absolutely correct !!! :)
Good Luck with your github !

# Instructions how to download repository from [GitHub.com](http://GitHub.com) to your local folder to work with

1. Need to create an account on [GitHub.com](http://github.com/) if we don’t have.
2. Find and open required repository which we are going to copy  and click on the green button to copy the github-link for instance: 
[`https://github.com/ilnar-geekbrains/version_control_lection_3.git`](https://github.com/ilnar-geekbrains/version_control_lection_3.git)
3. Create or choose a folder on your computer to create local repository. 
4. We need to open selected folder in Visual Studio Code (VSC) terminal. Firstly make sure that is not a repository with the command  `git status` . If we see the fatal error that it is OK, otherwise the directory is already a repository and we should chose other place or delete .git folder to remove repository.
5.  After that we need to copy repo from GitHub to your local folder with command in VSC terminal  
`git clone https://github.com/ilnar-geekbrains/version_control_lection_3.git`
6. Git will download the selected repository on gitHub to our folder as a folder with the same name.
7. In the VSC terminal, we need to change the directory and enter the selected repository, which we recently downloaded using the command 
`cd version_control_lection_3.git` and that it we can to start to work with files.


# Instructions how to
1.  Connect local and remote repositories (repositories). When creating a repository on GitHub, you will be given some instructions on how to do this. 
2.  Once connected Run `git push` via VSC terminal - push latest changes from local repository to remote GitHub repository. 
3.  After making any changes to the created remote repository directly through GitHub or being uploaded to the repository from another computer on GitHub, you will need to download the current current version using `git pull`.
   
