
Problem:
wget https://github.com/StartBootstrap/startbootstrap-clean-blog/archive/refs/tags/v5.0.10.zip10.zip
bash: wget: command not found

Resolve: curl
---- 

### Install Heroku within Gitpod:
- `npm install -g Heroku`


### Log In to Heroku:
- `heroku login -i`

  Error: Your account has MFA enabled; API requests using basic authentication with    
 »   email and password are not supported. Please generate an authorization token for API 
 »   access. 

 desabilité la opción Multi-Factor Authentication y me dejó. 
----
### View your Heroku Apps:
- `heroku apps`


### Rename a Heroku App:
- `heroku apps:rename NEW-NAME --app CURRENT-APP-NAME`


### Deployed Heroku App URL:
- `https://YOUR-APP-NAME.herokuapp.com`


### View Verbose Git Remotes:
- `git remote -v`


### Creating Heroku Git Remote:
- go to Heroku Settings Tab
- copy **Heroku Git URL** link
- `git remote add heroku https://git.heroku.com/YOUR-APP-NAME.git`


### Push Code to Heroku Remote:
- `git push -u heroku master`
