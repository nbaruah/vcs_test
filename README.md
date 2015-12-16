############### git configuration  #######################

git has 3 levels of configuration
1) Individual repositories
	<repo>/.git/config
 e.g git config user.name <name>

2) users specific
	~/.gitconfig
 e.g - git config --global user.name "John Smith"

3) Entire system wide settings
	/etc/gitconfig
 e.g - git config --system core.editor <editor>

############### working directory, staging area, git local repo, git central repo ####################

git staging area ==> Think of it as a buffer between current working directory and the repo
git local repo ==> Think of it as a buffer between my contribution and central repo
HEAD ==> HEAD always refers to the current commit, be it a branch or a specific commit

############### Creating a repository ####################

1) <git init> on the current directory to make it a repository
2) <git init (directory name)> to create a new non existing git repo
3) To create a new repo in www.github.com look for create new repository button
4) README.md file explains to other peoples what the project does
5) .gitignore file tells git what files should not be under version control
6) <git clone> to copy a repo to my local system 

############### Why version control system ####################

The whole idea behind any version control system is to store “safe” copies of a project so that you never have to worry about irreparably
breaking your code base.

############### Need of git checkout to load older version of a file ####################

Once you have built up a project history, git checkout is an easy way to load any of these saved snapshots onto your development machine.
