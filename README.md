# reproducibleResearch
Templates and information concerning approaches and methods for reproducible research and open science

# Creating a github repository directly from the command line

The following generates a _public_ repository. One has to convert it to a
_private_ one on the github web interface after creation.

```
echo "# Repository Title" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:crouzet-o/repoTitle.git
git push -u origin master
```
