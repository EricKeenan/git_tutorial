# git_tutorial
Git and GitHub are tools that enable efficient collaborative software development. In this tutorial, we will cover a few fundamental tools, namely:
- Issues
- Commits
- Forking
- Pull Requests

The focus of this tutorial  will be farmiliarizing yourself with git, not writing code. To do this I have written a very simple python3 script, `main.py`. In order to run `main.py` from the command line, simply execute the following:
```
python3 main.py
```

# Instructions

### Before the tutorial
Please make sure you
1. Install git on your computer
2. Create a [GitHub](https://github.com) account
3. Install python3 on your computer (not strickly necessary, but very illustrative).
 
### Farmiliarize yourself with the issue we will collaboratively solve
You can read the issue [here](https://github.com/EricKeenan/git_tutorial/issues/2). At the begining of the tutorial I will assign you are group number which will indicate exactly what change you should make. 

### Creating a fork
1. Log into GitHub
2. Create a fork of this repository into your own GitHub account
3. Navigate to your fork and clone to your local machine via a terminal window, e.g.
```
git clone https://github.com/eric-fork/git_tutorial.git
git remote add git_tutorial https://github.com/eric-fork/git_tutorial
```
But make sure to update the URL above to your own fork! 

### Make local changes
Make your assigned change to `main.py` as indicated in the [issue](https://github.com/EricKeenan/git_tutorial/issues/2). Save `main.py` and then commit and push to GitHub. Make sure to provide a descriptive commit message, e.g.
```
git add main.py
git commit -m "Uncommenting group 1 print statement" 
git push origin master
```

### Share your changes with the world by opening a pull request in the original GitHub repoistory
Create a new pull request in the orignal GitHub repository [here](https://github.com/EricKeenan/git_tutorial/pulls). Click the green "New Pull Request" button and then the "compare accross forks" link. Define the base (where you want to send your changes) and head (where your changes are coming from) repositories. Then click the green "Create pull request button" and provide a description of your changes, example [here](https://github.com/EricKeenan/git_tutorial/pull/1).
