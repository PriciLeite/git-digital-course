# Santander Coders 2023.2 | Back-End.
### Git-Digital-Course


### Comandos:
#### CMD
- git clone http\repository<br/>
- git init<br/>
modified / staged<br/>
- git status -> git diff<br/>
- git add .  -> git diff --staged<br/>
- git commit -m "description"<br/>
#### To Push
- git push -u origin master<br/>
#### To Pull
- git pull <br/>
- To check: git pull fetch -> git diff origin/master<br/>
#### Query Historic (Use log)
- git log<br/>
- git log --oneline --decorate<br/>
- git log --graph<br/>
- git log -- since "value"<br/>
- git log --author "value".<br/>
#### Restore
- To Modified: git restore .\directory<br/>
- To staged: git restore --staged .\directory<br/>
#### Create branch /Change branch
- git branch testing<br/>
- Verification: git log --oneline --decorate<br/>
- advance: git checkout name-branch (to commit and return to master using the same command);<br/>
#### Merging Branch
- Verification: git branch<br/>
- git checkout name-branch to merge<br/>
- git merge name-branch-bring<br/>