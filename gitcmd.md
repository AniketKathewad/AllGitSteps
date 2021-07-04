git commands

1. login to github website

2. create a new repository and add readme.md file in repository

3. open gitbash from laptop and swith to desktop using command (cd Desktop)

4. create a new directory for practice using below command
mkdir directory-name

5. Goto this created directory using below command
cd directory-name

6. check your current location using below pwd command (present working directory) 
pwd 

7.generate ssh keys (private and public keys) using below command and press enter until it creates keys

ssh-keygen

8. Check the public key (.pub) ssh key path after executing above command and open the .pub file in notepad and copy it

9. Goto Github website settings (top right side) -> ssh & GPG Keys -> add SSH Key that you copied in step 8

10. clone git repository from gitbash using below command by copying repository ssh url from code option of github website

git clone  github_repo_ssh_url 

11. check the changes using ls command and go to this repository folder using cd command

ls
cd repo_folder

12. Add file and update file content using below commands. 

touch filename
vi filename

13. Execute below command to add all files in git staging area
git add -A

14. Execute below command to commit changes 
git commit -m "message"

15. Execute below command to push changes to Github remote repository
git push
  





