# vcs_test
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

############### Creating a repository ####################

1) <git init> on the current directory to make it a repository
2) <git init (directory name)> to create a new non existing git repo
3) To create a new repo in www.github.com look for create new repository button
4) README.md file explains to other peoples what the project does
5) .gitignore file tells git what files should not be under version control 
