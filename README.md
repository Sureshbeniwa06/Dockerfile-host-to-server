# Dockerfile-host-to-server
dockerfile-build-run-host on server
.............................................................................
Step 1: $ sudo su
        password ubuntu os
        
Step 2: check the folder mapping with the command ls

Step 3: cd dockerfile (to select dockerfile)

Step 4: cat dockerfile (to see the mapping source to destination)

Step 5: docker build . (to build a container)

Step 6 :docker images (images id ) to select you want run on web server

Step 7: docker run -d - p 80:80 <image id you want to use hosting a website)

---------------------------------------------------------------------------------------

Explanation of create a folder 


or create a new repository on the command line


echo "# Dockerfile-host-to-server" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/Sureshbeniwa06/Dockerfile-host-to-server.git

git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/Sureshbeniwa06/Dockerfile-host-to-server.git

git branch -M main

git push -u origin main
