# Lesson 5 Final Project: Deployment 14 points

# Directions
Now that you have completed the Deployment course, now is the time to put that knowledge to work. You will create a new AWS EC2 instance which will contain the starter-node-angular web app from GitHub. Then, you will fork that repository and connect it to Travis CI. Finally, you will configure Travis CI to automatically deploy the application to EC2 instance when the code in the repo is updated.

# Caution!
Do not submit your project until you have completed all requirements, as you will not be able to resubmit.

# Requirements
Complete and provide screenshots of the following:

Create a new EC2 instance. The student must create a new EC2 instance independent of the instance created in the earlier lessons.

SSH Login. The student must be able to login to the EC2 instance via SSH using the downloaded .pem file.

Fork and Clone Project. The student must fork and clone the starter-node-angular repo. This repo contains everything for a minimal web application. This will be used as the application to deploy:

Starter Node Angular Repo

Connect with Travis CI. Connect your forked repository with Travis CI.

Travis Config. Must create a .travis.yml file which contains the necessary configuration to build, test, and deploy the application to the EC2 instance.

Deploy Script. Must have a deploy.js and deploy.sh file to deploy the application to the EC2 instance. You are permitted to use the same deploy.js file from previous lessons as a template.

Configure Nginx. The student must set up and configure Nginx. Add sample files and be able to route traffic using Nginx as you did in Lesson 4.

# Caution!

Be sure to zip and submit your entire starter-node-angular directory along with all screenshots when finished!
# MEAN Stack Single Page Application Starter

This is a repo for a starter appliation for a Single Page MEAN Stack application. Just download and install and you have a good foundation for building application. 

## Installation
1. Download the repository
2. Install npm modules: `npm install`
3. Install bower dependencies `bower install`
4. Start up the server: `node server.js`
5. View in browser at http://localhost:8080

Use this starter kit to build any MEAN stack application you like.

If you have any questions or requests, email us at [chris@scotch.io](mailto:chris@scotch.io) and we'll keep updating this to make it perfect.

## Future Additions
- CRUD examples
- Development and Production Environments
- Link examples
- Single Page AngularJS Animations
