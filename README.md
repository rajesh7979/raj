#!/bin/bash

echo "# raj" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/rajesh7979/raj.git
git push -u origin master

exit
