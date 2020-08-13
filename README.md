create a new repository on the command line

echo "# nodbranch" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/dhanjivpandey/nodbranch.git
git push -u origin master