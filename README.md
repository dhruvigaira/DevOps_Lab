# DevOps_Lab
# devops_lab
# DEVOPS LAB
## LAB-1 GIT COMMANDS

### 1. Clone the repository:
⁠ ```sh
git clone https://github.com/shlokiii/devops_lab.git
 ⁠⁠ ```
![Project Screenshot](./images/1.png)


### 2. Adding image:
⁠⁠ ``` sh 
git add .
git commit -m "my first commit with image"
git push
 ⁠⁠ ```
![Project Screenshot](./images/2.png)


### 3. Git status and Diff Commands:
⁠⁠ ``` sh 
git staus
 ⁠⁠ ```
![Project Screenshot](./images/3.png)
⁠ ```
⁠ sh
git diff
 ⁠⁠ ```
![Project Screenshot](./images/4.png)

## LAB-2 GIT COMMANDS
### 1. Checking the logs
### version1:
```⁠ sh
git add hello.txt
git commit -m "v1"      
 ```
![Project Screenshot](./images/5.png)

### version2:
```⁠ sh
git add hello.txt
git commit -m "v2"      
 ⁠```
![Project Screenshot](./images/6.png)

### version3:
```⁠ sh
git add hello.txt
git commit -m "v3"      
 ⁠```
![Project Screenshot](./images/7.png)

⁠ ```sh
git log
 ⁠```
![Project Screenshot](./images/8.png)


### 2. Creating branch and merging with Main
```⁠ sh
git branch feature1
git add .
git commit -m "feature commit 1"
git push origin feature1
 ⁠```
![Project Screenshot](./images/9.png)

### Merged with Main
⁠ ```sh
git add README.md
git commit -m "Updated README before merging"
<img width="628" alt="10" src="https://github.com/user-attachments/assets/a00e3755-241c-4282-a2f2-9dba729a9853" />


git checkout main
git merge feature1 -m "Merging feature1"
 ⁠```
![Project Screenshot](./images/10.png)



##  LAB-3 SUBVERSION
### Installation of Subversion (SVN) using Homebrew:
⁠  sh
brew install subversion
 ⁠


### Creating repo:
⁠ sh
mkdir -p ~/svn-repos/myrepo
svnadmin create ~/svn-repos/myrepo
 ⁠

### Configure svnserve:
⁠ sh
nano ~/svn-repos/myrepo/conf/svnserve.conf
 ⁠

### Start svnserve:
⁠ sh
svnserve -d -r ~/svn-repos
 ⁠
### setting up password:


### starting server and verifying:

