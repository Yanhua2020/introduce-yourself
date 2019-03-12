# introduce-yourself
### Follow the below steps :   
  1. Go to https://github.com/dsc-lnct/introduce-yourself.git  
  2. Fork the project by clicking on fork button available on top-right corner  
  3. Open the repository and copy the URL of repository
  4. write the following command in your terminal/git bash and press enter:  
  ```  
  git clone https://github.com/dsc-lnct/introduce-yourself.git    
  ```  
  5. move to the introduce-yourself directory by writing the following command and press enter:  
  ```  
  cd introduce-yourself  
  ```    
  6. Now go to the place where you have downloaded the repository and open the file **introduce.txt**  
  7. Add your name and email in the desired format (**Don't change the format**)
  8. Save the file and again come to the terminal  
  9. write the following command and press enter to add your changes to git:  
  ```  
  git add introduce.txt  
  ```  
  10. Then to commit your change with message as your name write the command below and press enter:  
  ```  
  git commit -m "<Your name> added"  
  ```  
  11. If you are commiting for the first time then you will encounter with the following error:  
  ```  
  *** Please tell me who you are.  
  Run  
    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"  
    to set your account's default identity.  
    Omit --global to set the identity only in this repository.  
    fatal: unable to auto-detect email address (got 'mishr@DESKTOP-TAIETA7.(none)')  
 ```  
 12. To remove this, add your email and username.(If you don't see anything like in step 11 then skip step 12 and 13)  
 To add your email, write the following command and press enter:  
 ```  
 git config --global user.email "you@example.com"  
 ```  
 13. To add your username, write the following command and press enter:  
 ```  
 git config --global user.name "Your Name"  
 ```  
 14. If you have encountered the error on step 11 and followed the step 12 and 13 then write the following command again:  
 Note: If you don't see anything like in step 11(or no error) then skip this step (step 14)
 ```  
 git commit -m "<Your name> added"  
 ```  
 15. Then push the file to github, write the following command and press enter:  
 ```  
 git push origin master  
 ```  
 16. Enter your github id and password  
 17. Go to your github account and then move to the repository (introduce-yourself)  
 18. Click on **new pull request** then click on **create pull request** and then add the title or leave as it is and click on **create pull request**    
 19. That's all, you have done your first commit on github.
