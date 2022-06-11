- Create app.js with logic inside
- Create Dockerfile to start in the container

1. docker build -t <tag-name> .           <!--     . means current directory  ||  -t means tag    -->

<!-- this is to check image list. -->
2. Check if docker successfully build or not by code
-> docker image ls
or 
-> docker images

3. Run program by code 
-> docker run <repository-name>
or
-> docker run <tag-name>