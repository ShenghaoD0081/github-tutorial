# GitHub Tutorial

_by Shenghao Dong_

---
## Git vs. GitHub
> - GitHub is the site where you can put all yoru git files into.  
> - Git is where you code and get things ready   
> - GitHub can be used as back-up to restore your files in case it gets lost  

---
## Initial Setup
> - Make a account for [GitHub](https://github.com/)  
> - Then you want to set up your IDE. Here's a [tutorial](https://docs.google.com/presentation/d/1t3isDyU7pL84iU5s0UehTuGxhPMFC3Obs38xudrd49o/edit)


---
## Repository Setup
> - For your repo set-up you want to make a file first using _mkdir DirectoryName_ in your [IDE](ide.cs50.io)  
> - Then you want to make a repo over at [GitHub](github.com) with the EXACT same name   
> - Go in the directory you just made by using cd   
> - Then you can _git init_ the Directory you get made (or you can do it later)   
> - Then use _touch README.md_ to make a read me   
> - After that you can _c9 README.md_ and editied to your hearts content   
> - _git add FileName_ everytime you add anything, in this case we are editing README.md. **MAKE SURE YOU _GIT INIT_ BEFORE DOING THIS**   
> - After you add it to the staging area you want to commit it   
> - You can do this by doing _git commit -m "Insert Message"_ 
> - Use _git remote add origin git@github.com:YourUsername/repo-name.git_ to connect it to your github repo.
> - Use _git push -u origin master_ so you can start pushing
> - Bam! Your done. If you want other people to see this or have a copy saved online, you can use git push to push it to your repository on [GitHub](Github.com)   


---
## Workflow & Commands
> - _git init_: initializes the directory. You **MUST** do this before using git add. You also **MUST** be in a directory to do this.
> - _mkdir directory-name_: Makes a directory. Pretty simple right? I mean you can't do anything without a directory.
> - _cd filename_: Changes the directory you are in.
> - _touch filename_: Make a file. I mean a directory is useless without files.
> - _c9 filename_: Moves you inside a file. You do want to edit the file right?
> - _git add filename_: Adds directory and files inside it to the staging area so you can commit it.
> - _git commit -m "message"_: commits the stuff you just added to staging area after you commit it you can push it
> - _git remote add origin git@github.com:YourUsername/repo-name.git_: Adds the git repo to the directory on your IDE
> - _git push -u origin master_: Makes it so you can push your files to github aftewards
> - _git push_: Pushes the directory and the files on GitHub. MUST Use 2 commands above first


```css
The End
```