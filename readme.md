# Chaos Engineers Labs - Sandbox

## Steps/Hints to follow
-Download terraform. Make sure its in your path by creating a sym link for example ( without this, you will get an error for terraform not found )
    - ln -s ~/Downloads/terraform  /usr/bin/terraform 
    
-make init - Will generate an ssh folder to store outputs

-make plan - Generates infrastructure plan

-make apply - Applies the infrastructure plan

-make connect - connect to the EC2 instance

-make down - Destroys / tears down the infrastructure
