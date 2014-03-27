# Synchronizing Bitbucket -> Github

## Create a git repository on bitbucket

    mkdir myproject
    cd myproject
    git init
    git remote add origin https://scips@bitbucket.org/scips/test.git

Add some files (f.i.: README.md)

    git add README.md
    git push -u origin master

## Create an empty project on github and push the git in it

    git remote add github git@github.com:scips/test-from-bitbucket.git
    git push github master:master


