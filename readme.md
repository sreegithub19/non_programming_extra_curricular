# Contents
- [Contents](#contents)
  - [Docker\_in\_Windows](#docker_in_windows)
  - [Git\_submodules](#git_submodules)
          - [reference: https://stackoverflow.com/questions/1030169/pull-latest-changes-for-all-git-submodules](#reference-httpsstackoverflowcomquestions1030169pull-latest-changes-for-all-git-submodules)
  - [Miscellaneous\_links](#miscellaneous_links)
  - [Blood\_donation](#blood_donation)
    - [2024](#2024)
    - [2023](#2023)



## Docker_in_Windows 

Reference:
- https://www.sitepoint.com/docker-windows-10-home/
- https://blog.jayway.com/2017/04/19/running-docker-on-bash-on-windows/

- Steps to do (done so far):
 - (In Windows Powershell as admin)
    -   choco install virtualbox
    -   choco install docker-machine
 - (In Git bash)
    -   docker-machine create --driver virtualbox default (causing this error: VT-x is disabled in the BIOS for all CPU modes (VERR_VMX_MSR_ALL_VMX_DISABLED).)

################################################################################

## Git_submodules

1. To add a git repo as submodule in another repo (in that specific folder):
git submodule add https://github.com/sreegithub19/vuejs_training.git
git submodule add https://github.com/sreegithub19/vercel_flask_app.git
git submodule add https://github.com/sreegithub19/vercel_django_example.git
git submodule add https://github.com/sreegithub19/express_vercel_app.git
git submodule add https://github.com/sreegithub19/vue_project.git
git submodule add https://github.com/sreegithub19/JavaScript-Applications.git

###### reference: https://stackoverflow.com/questions/1030169/pull-latest-changes-for-all-git-submodules
2. To update all the submodules according to the latest remote repo changes:
git submodule update --init --recursive
git submodule update --recursive


3. To fetch the all the submodules according to the latest remote repo changes:
git pull --recurse-submodules


4. Most important commands: 
git submodule add <git_repo_link>   (in that specific folder - when adding the module for the first time)
git submodule update --init --force --remote   (in the main folder)
git submodule add -b <branch A> --name <name A> --url <path A> 
 -eg:  git submodule add -b main https://github.com/sreegithub19/my_angular_app.git javascript/angular_/my_angular_app_main

To remove a submodule:
 - Delete the relevant section from the .gitmodules file.
 - git add .gitmodules
 - git rm --cached <path-to-submodule>  (no trailing slash).
 - rm -rf .git/modules/<path_to_submodule>
 - git commit -m "Removed submodule <name>"
 - rm -rf <path_to_submodule>

5. Steps:
(i) git pull origin main
(ii) git submodule update --init --force --remote
(iii) git add .
(iv) git commit -m "Message"
(v) git push origin main

6. 
- Delete branch ("typescript") locally: git branch -D typescript
- Delete branch ("typescript") in remote : git push https://github.com/sreegithub19/node_server.git --delete typescript


(All in one step) :  
Mac:
git add . && git commit -m "Message" && git push origin main
git pull origin main && git submodule update --init --force --remote && git add . && git commit -m "Message" && git push origin main
Windows:
git add . ; git commit -m "Message" ; git push origin main
git pull origin main ; git submodule update --init --force --remote ; git add . ; git commit -m "Message" ; git push origin main


Windows long file name issue:
1. Execute this command in Powershell (run as Administrator):  git config --system core.longpaths true

================================================================
## Miscellaneous_links

1. Video splitter:
https://split-video.com/

================================================================

## Blood_donation

### 2024
![0-02-03-640457ff254cb920aea5d62d834c6a7ee9be22709b34bbc638b42b4fd3ee5b19_1c6dbc2f8799e7](https://github.com/sreegithub19/extra_curricular/assets/55496113/44d0a35f-623b-433f-a32d-e3304a9fb857)

### 2023
![0-02-03-b0511876d2531377a9effae4520d6c47c3f4fa38e7cae4cb0d548991d4a46949_1c6dbc2ce784cf](https://github.com/sreegithub19/extra_curricular/assets/55496113/de867cd7-52e8-4905-93d0-fb9871aa45a1)



================================================================

## Health (medicine)

### Constipation
- Dulcoflex (Tablet)
- Kayam Churna (Powder and Tablets)
- Pantoprazole (Tablet)
- Pantodac (Tablet)
- Pet Safa (Powder)
- Cremaffin (Syrup)
- Castor oil (Syrup)
- Sompraz D (Tablet)
