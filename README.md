In this project I used vagrant in a VB running Ubuntu 20.04 as part of the ALX project.

Commands i used after using the Github web UI to create this repo are:
```cd home/Desktop/jason```
```mkdir vagrant```
```cd vagrant```
```mkdir zero_day```
```cd zero_day```

Now I initialized git in the ```zero_day``` directory & added the remote origin.
```git init```
```git remote add origin <Copied Https link from repo>```

I then created this ```README.md``` file.

I added, commited & pushed it.
```git add README.md```
```git commit -m "My first commit" ```
```git push```


***** Reloving Logins and Issues *****
After the command ```git push```

this message came up
```css

fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

```

I resolved it by pushing to the command ``` git push --set-upstream origin master ``` to push the current branch to its updtream branch called `master`.
This command created an upstream tracking reference so that `git pull` and `git push` will work without any arguments.

It then prompted for Authentication
```css
Username for 'https://github.com': Jasiel-Stark8
```

```css
Password for 'https://Jasiel-Stark8@github.com': <Personal Access Token>
```
