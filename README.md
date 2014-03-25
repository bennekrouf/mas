mas
===

Different scripts used for a project based on :
- Java/JBoss App
- MySQL
- SVN

... behind a proxy.


#### Tips : how to add ssh key for github, bitbucket and so on  ? (github procedure is not complete!)

  cd ~/.ssh
  
  ssh-keygen -t rsa -C "your_mail@blabla"
  
  eval `ssh-agent -s` # should display a pid
  
  ssh-add ~/.ssh/id_rsa 
  
   # should say something like "Identity added: /c/Users/bennekroufm/.ssh/id_rsa (/c/Users/bennekroufm/.ssh/id_rsa)"
   
Then upload your key on the server (github conf or bitbucket conf) 
