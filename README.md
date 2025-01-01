# github-with-cmd
Use these commands after you install git in your computer to upload local files to github

On GitHub
> create a repository(don't add readme, and make it public)

On Computer
1. Go to your desired folder
2. right click
3. open command prompt
4. git init
5. git add .
6. git status (to know status of files uploaded)
7. Now paste the repository link which looks like "git remote add origin https://github.com/harshavarthanep/project.git"
8. git config --global push.autoSetupRemote true
9. git push
If 8 & 9 didn't work then do 10 & 11
10. git commit -m "TEST"
11. git push origin master


Now You have successfully imported all your local project files to GitHub!
