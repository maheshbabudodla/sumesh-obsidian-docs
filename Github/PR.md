- fork repo
- git clone the forked repo
- git remote add upstream "link of original project repo"
- git pull upstream master (pulls from original source to sync the forked/local code)

- make new branch `git branch temp` and git checkout temp
- do the changes
- git add .
- git commit -m "msg"
- git push origin temp (As we cant push to main/master branch on the origin, we will push to temp branch on origin) (here upstream is the opriginal repo and origin is the forked repo)
- go to github on yr forked repo and click on compare and pull request ()
- add title and comments for pr and create pr