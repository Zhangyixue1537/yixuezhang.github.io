
### Locate the working folder using git 
1. Open `git bash` under the `Git` folder in the Start menu
2. `cd /d`
3. ```cd download/git/projects/zhangyixue1537.github.io```

### Visually The Website Locally
1. Update the latest code in the github
```
git fetch origin
git merge origin/master
```
2. Create a local website
```
bundle exec jekyll serve
```

3. Visualize the website `http://127.0.0.1:4000/` in the browser 
