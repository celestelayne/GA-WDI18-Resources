### Pulling from UPSTREAM

>setup..
 
+ fork the main (god) repo
+ clone down your fork
+ run `git remote add upstream <url of god repo>`
 
>now you can..
 
+ git add .
+ git commit -m "pulling from upstream"
+ git pull upstream master    #pull from god
 
+ change the file (add stuff)
+ commit again
 
+ git push origin master      #push to your fork

----
### Updating gh-pages

git checkout gh-pages // go to the gh-pages branch
git rebase master // bring gh-pages up to date with master
git push origin gh-pages // commit the changes
git checkout master // return to the master branch

### Pushing to GitHub Repo


### RSpec
rspec --format documentation
