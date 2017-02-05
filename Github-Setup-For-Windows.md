### Github setup for Windows

##### 1. Configuration in 2 ways
###### 1.1 Input your information after login in Github application
###### 1.2 Open Git Shell and input

>$ git config --global user.name “your username”
>$ git config --global user.email “your email address”

##### 2. Clone

Following command could be used in CMD or Git Shell. You can also use Git application

>$ git clone HTTPS_URL_OF_REPOSITORY

##### 3. Input your username and password on Github when prompted if your are cloning a private repository

##### 4. Work in your local repository

>$ cd DRIVE:/
>$ cd PATH_OF_FOLDER_NAME/

##### 5. Add your changes 

>$ git add .

##### 6.Commit

>$ git commit –m “added changes”

##### 7. Push you local repository to remote repository

>$ git push origin master