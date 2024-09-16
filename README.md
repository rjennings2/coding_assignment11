Instructions on how to get the web application running on local host

1 create a Dockerfile and add the required content, this will include From node:18, WORKDIR /namehere, RUN different commands, EXPOSE 3000, and CMD ["npm", "start"]

2 once the Dockerfile is filled with the appropriate content for your web page, build the docker image by using the command: docker build -t lastName_firstName_coding_assignment11 .

3 now run the docker container using the command: docker run -p 7775:3000 lastName_firstName_coding_assignment11

4 you should now have a docker container up and running

5 to access the web application, open your browser and go to http://localhost:7775 (or your specific port number)

6 you should now be able to see your web application running on local host