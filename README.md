Defunct Website


## you can delete the forked repo after the changes have been merged..


##Why is the git push command rejected, and how do you deal with it?
#you have to "fetch first." Use the commands:
```sh
git fetch origin main
```

#And follow these steps to merge:

```sh
git pull origin main
```
```sh
git add .
```
```sh
git commit -m 'your commit message'
```
```sh
git push origin main
```
