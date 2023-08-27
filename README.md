As you see I am forked this repository. Follow these steps in Jenkins to create CI/CD pipeline-

  1- Create a new project in Jenkins.
  2- Add the GitHub URL of this project in the Source Code Management section.
  3- Add GitHub webhooks for this repository. See day24 task to add webhook. Click here https://avp23.hashnode.dev/day24-90daysofdevops
  4- Select 'GitHub hook trigger for GITScm polling' in 'Build Triggers' section.
  5- Add the build steps to start the container and save the project.
As we run contauner using Docker and Docker-Compose ref Day24 task, as both tasks added seperately.
  5- Access your deployed application

To add GitHub Webhook-Got to repository-settings-webhooks-add webhook-Content type should be "application/json" selected and enter URL as <http://IP:8080/github-webhook/> 
Here IP is your Instance IP on which Jenkins is running.
