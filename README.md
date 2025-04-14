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
![Project Screenshot](./image<img width="633" alt="5" src="https://github.com/user-attachments/assets/95a7346b-a0ec-426b-92a7-c12a12dd3dca" />
s/5.png)

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


git checkout main
git merge feature1 -m "Merging feature1"
 ⁠```
![Project Screenshot](./images/10.png)

