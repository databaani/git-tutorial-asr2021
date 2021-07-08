# git-tutorial-asr2021

Git is a distributed version control system. It facilates merging of different source codes from different developers. And codes are distributed among developers. Make a copy of the repository in your local machine and work offline, and then push your changes to the server.

Install Git in your PC
- Linux
  - sudo apt-get update
  - sudo apt-get install git
  - git --version (for checking Git version)

- Windows
  - Download Git installer from following link and install
  - https://gitforwindows.org/

Set-up Git in your PC
- git config --global user.name "username" 
- git config --global user.email "youremail@domain.com" 
- git config --list
	user.name=username
	user.email=youremail@domain.com

You can see all the configuration done for your git account from the .gitconfig from you Home directory
gedit .gitconfig

Other commands 
- git clone (url)
- git add (file names) 
- git status
- git commit -m "(committed message) 
- git push -u origin master 
- git remote add origin master (url) 

