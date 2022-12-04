# ReadMe

Is important to configure a git repository where 
the file with the configurations is going to be stored

Installing Git and Creating Local Git Repository

+ go to a folder  in the console and:

git init

git add *

git commit -m "First commit"

Inside that location put the configuration file:

/git-localconfig-repo/limits-service.properties New

limits-service.minimum=4

limits-service.maximum=996

After that commit that file:

git add *

git commit -m "limits-service.properties"

# Access

http://localhost:8888/{file-name]}/default

http://localhost:8888/limits-service/default