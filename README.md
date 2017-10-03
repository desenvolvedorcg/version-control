# version-control

####  …or create a new repository on the command line

quando eu criar uma pasta no meu computador e quiser relacionar com um projeto do github

echo "# version-control" >> README.md  #criar arquivo
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/desenvolvedorcg/version-control.git
git push -u origin master

### …or push an existing repository from the command line

git remote add origin https://github.com/desenvolvedorcg/version-control.git
git push -u origin master

