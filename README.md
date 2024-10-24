1. git clone https://github.com/TejasBhosale123/my-website.git
2. cd my-website
3. git branch
4. git checkout -b feature-improve-docs
5. git add .
6. git commit -m "Improved documentation for Docker getting started"
7. git push origin feature-improve-docs
8. git checkout main
9. git merge feature-improve-docs

DOCKER PUSH AND PULL IMAGE
1. logon to hub.docker.com
2. In cmd type command: docker images
3. then the repo name, tag, image id and size will be displayed
4.  repository name can be taken from that list and imageID
5. docker login
6. docker tag repository name:iamgeID newImageName/repository name (same previous repository name
7. again type docker images (check if the image is added or not)
8. docker push newImageName/repository name 
