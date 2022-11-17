Cheatsheet for GIT - NOV17

GIT is an open source version control system responsible for managing GitHub related contributions done locally on your computer. This cheatsheet summarizes what I learned to do with it until now.

Overview of Git characteristics:

GitDoodle.jpg

Installing GIT on Ubuntu:

    1.Open Terminal and type:

        $ sudo apt-get update
        $ sudo apt-get install git
    2.Verify if the installation is correct by typing:
        $ git --version

Configure Git username and email with following commands. Replace "Name Example" and email with your own.

    $ git config --global user.name "Name Example"

    $ git config --global user.email "nexample@atlassian.com

Forking a repository

As a way of proposing changes to GitHub repository, you can fork it with the following steps:

    1.On GitHub.com, navigate to the octocat/Spoon-Knife repository.
    
    2.In the top-right corner of the page, click Fork. Fork button
    
    3.Select an owner for the forked repository. 
     
    4.By default, forks are named the same as their parent repositories. You can change the name of the fork to 
    distinguish it further.
    
    5.Optionally, add a description of your fork.
    
    6.Choose whether to copy only the default branch or all branches to the new fork. For many forking scenarios, such as contributing to open-source projects, you only need to copy the default branch. By default, only the default branch is copied.
    
    7.Click Create fork.


