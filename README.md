# docker-assignment
1. Install all the npm packages by using npm install command.
 
2. Install and configure mysql server.
 
3. Install and configure mongodb server.
 
4. Configure credentials in config/default.json file.

5. Execute npm start command to start running the application.
 
6. Check in browser if the app is working fine by entering http://localhost:[port_number].
 
7. Create a file called Dockerfile to write instructions to bundle the application as a Docker Image inside the root directory.
 
8. Create docker file by writting set of instructions such as FROM, COPY, RUN, EXEC, CMD, etc.
 
9. Then run the command docker build -t assignmentapp .  => (to build the docker image and store in current directory)
 
10. If we wish we can also store our images into dockerhub.
 
11. Execute docker login command to enter dockerhub id and password to authenticate.
 
12. We can push the image to dockerhub using the syntax docker push [OPTIONS] NAME[:TAG].
 
13. Then create docker-compose.yml file at root location which is used for creating muktiple services at the same time.
 
14. Add 3 services Nodejs, Mongodb and Mysql inside docker-compose.yml with the image name and other related arguments.
 
15. Use depends_on with the value to control the flow of execution.

16. Add volumes with the parameters to persist the data even if the container restarts.
 
17. Use docker-compose up -d command to run the docker-compose file and create the services.

18. To add custom configuration to Nginx, it is an software used for web serving, reverse proxying, caching, load balancing.

19. All NGINX configuration files are located in the /etc/nginx/ directory, Amongst all the configuration files /etc/nginx/nginx.conf is the main file.

20. Now open the /etc/nginx/nginx.conf file to edit and add the configurations of http block.

21. Now create a file and open it in edit mode with your domain name.conf for example=> site.com.conf to add server block containing arguments with their values.

22. Finally we can use Let's Encrypt which is a non-profit certificate authority and provides certificates for localhost.
 
23. Using Let's Encrypt we will set up HTTPS on our local web server.

