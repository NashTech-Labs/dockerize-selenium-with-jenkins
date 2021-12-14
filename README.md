# Dockerize-selenium-with-jenkins
Here, we are dockerizing our entire Selenium Project and running our scripts inside Docker Container.
And also integrating our repo with jenkins and docker
This repository contains a plug and play template for getting started with selenium 4.0.

This is a simple plug and play template that is configured for chrome and firefox.

Clone the repository on your local system.

Download the latest driver files from the links given below and place them in the DriverFiles folder.



Firefox driver file download : https://firefox-source-docs.mozilla.org/testing/geckodriver/Support.html

Chrome driver file download : https://sites.google.com/a/chromium.org/chromedriver/
Prerequiste Docker and Jenkins should preinstalled and running
Use "docker build app" command to build image 
Check image by docker images
Now use docker run in iterative mode :
you will be in docker container 
use mvn test
![Screenshot from 2021-12-14 13-08-19](https://user-images.githubusercontent.com/76486190/145954379-4530a6e6-d6b4-494a-9fe8-5d61f931d4a8.png)

To integrate with Jenkins
https://plugins.jenkins.io/workflow-scm-step/
![Screenshot from 2021-12-14 13-18-34](https://user-images.githubusercontent.com/76486190/145955187-36dada45-1c00-488a-98fc-1d7d1cc58fa2.png)
![Screenshot from 2021-12-14 13-19-27](https://user-images.githubusercontent.com/76486190/145955199-d37099ff-0c49-46e6-846f-b27767076e4e.png)
