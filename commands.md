# Commands 
    git add .
    git commit -m "Adding to the repository"
    git push

    git pull

    git branch

    git checkout -b branch1
    git push --set-upstream origin branch1

    git merge branch1 

    
    To set your global username/email configuration:
    
    git config --global user.name "FIRST_NAME LAST_NAME"
    git config --global user.email "MY_NAME@example.com"

    To set repository-specific username/email configuration:

    git config user.name "FIRST_NAME LAST_NAME"
    git config user.email "MY_NAME@example.com"

    Verify your configuration by displaying your configuration file:
    cat .git/config
