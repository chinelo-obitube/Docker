## Docker

## Steps in creating and deploying an app using docker

1. I installed docker on my VM using the sudo apt-get install docker
2. Then also installed a web server -nginx
3. I used the nginx docker image from dockerhub for this project.
4. Created a directory called site-content and added an index. html file 
5. I ran this command to run my docker image  sudo docker run -it --rm -d -p 8080:80 --name web -v ~/site-content:/usr/share/nginx/html nginx
6. the port 8080 is the port I used to run my docker image(nginx)
7. The link to my web app(docker image) : http://35.176.236.107:8080/
