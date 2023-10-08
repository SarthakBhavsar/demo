# FSDLAB
## Git Commands 

### Creating a Local Repository:
```
Sarthak@Null MINGW64 ~/oneDrive/Desktop/ALLC (master) % git init
Reinitialized existing Git repository in Sarthak@Null MINGW64 ~/oneDrive/Desktop/ALLC (master)
```
### Adding and Commiting Changes:
```
Sarthak@Null MINGW64 ~/oneDrive/Desktop/ALLC (master) % git add .
Sarthak@Null MINGW64 ~/oneDrive/Desktop/ALLC (master) % git commit -m "first commit" 
[main (root-commit) 62327f8] first commit
 5 files changed, 206 insertions(+)
 create mode 100644 android-chrome-512x512.png
 create mode 100644 index.html
 create mode 100644 pexels-oleksandr-tiupa-192136.jpg
 create mode 100644 script.js
 create mode 100644 style.css
```
### Linked Local Repository to Remote Repository:
```
Sarthak@Null MINGW64 ~/oneDrive/Desktop/ALLC (master)% git branch -M main
Sarthak@Null MINGW64 ~/oneDrive/Desktop/ALLC (master) % git remote add origin https://github.com/SarthakBhavsar/demo.git
```
### Push Changes to Remote Repository:
```
Sarthak@Null MINGW64 ~/oneDrive/Desktop/ALLC (master) % git push -u origin main
Enumerating objects: 31, done.
Counting objects: 100% (31/31), done.
Delta compression using up to 8 threads
Compressing objects: 100% (31/31), done.
Writing objects: 100% (31/31), 9.81 MiB | 5.67 MiB/s, done.
Total 31 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/SarthakBhavsar/demo.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
```

### Pull Changes from Remote Repository:
```
git pull origin master
```
### Create and Manage Branches:
```
To create a new branch, use:
git checkout -b new-branch-name

To switch between branches:
git checkout branch-name
