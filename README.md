### Linux-cmd
Just some linux terminal shortcuts

### Linux cmds
### For editing a project inside the folder /var/www


To make the folder editable inside /var/www type the following command...

```
sudo chown -R jugalkdas:www-data /var/www/"The folder you want" && chmod -R g+sw /var/www/"The folder you want"

```

### git cmds

### Start a repo from existing project

* Make a directory
* Add any file in the directory
* Open the directory in terminal
* Add cmds -

    0th - In case of if you want add .gitignore file.
```git add .gitignore```
    1st
```git init```
    2nd
```git add .```
    3rd
```git commit -m "whatever commit u want"```

* Connect it to github -
    
    * Login/signup.
    * Create new repo in case if you didn't create at the first time.
    * And more cmds -
```git remote add origin https://github.com/user-name/repo-name```
```git fetch```
```git checkout origin/branch-name -b branch-name```
