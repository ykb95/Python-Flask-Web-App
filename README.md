# Python-Flask-Web-App

1. To push the app/code in github:
     
     * git add .
     * git commit -m "my-message"
     * git push

2. To Pull
    
    1. git pull
    
    2:-
    
     * git stash

     <!-- optional step -->
     <!-- * git stash pop -->
     <!-- * git commit -m "my-message"      -->
     
     * git pull

3. To pull the app/code in github
     * git pull
     If error: 

     (error: Your local changes to the following files would be overwritten by merge:
        flask_web_app.pyc
Please commit your changes or stash them before you merge.
Aborting
Updating a5d8e40..c71c8d9)

    then: 

    You can't merge with local modifications. Git protects you from losing potentially important changes.

You have three options:

Commit the change using

     * git commit -m "My message"
Stash it.
Stashing acts as a stack, where you can push changes, and you pop them in reverse order.

To stash, type

     * git stash
Do the merge, and then pull the stash:

     * git stash pop

then:
     * git pull

To run the app follow the below steps:
4. Windows
    run the app in cmd
    * set FLASK_APP=flask_web_app.py
    * flask run

5. Mac/Linux
    run the app in cmd
    * export FLASK_APP=flask_web_app.py
    * flask run

6. Creating new branch



reference link:
https://confluence.atlassian.com/bitbucket/branching-a-repository-223217999.html