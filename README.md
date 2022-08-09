# boo6
  Links:  
    https://www.w3schools.com/bootstrap5/bootstrap_get_started.php  
    
  Change branch name:  
    `>git branch -m master main`
  
  Github error: fatal: refusing to merge unrelated histories:  
    `>git pull origin master --allow-unrelated-histories`  
    
  Github set token (no need to change default user.name or user.email):  
    `>git remote set-url origin https://[user_name]:[user_token]@[user_repo]`  
    `>git remote set-url origin https://codeacade:2352352352352525@github.com/codeacade/boo6`  
	
  Github reset token (when 404 server response):  
    `git config --system --unset credential.helper`  
    
  Heroku:  
    `>heroku git:remote -a boo6`  
