# jenkins-agent-pipeline

In this post, I demonstrate setting up a simple Jenkins pipeline to deploy a static web app page onto a remote EC2 instance configured as a Jenkins agent.

The key steps are:

Launch EC2 instances for Jenkins master and agent

Configure SSH access between master and agent

Add the agent node in the Jenkins master UI

Create a sample pipeline job to copy and deploy the web app

Run a build to see the deployment happen on the agent node

For the complete step-by-step instructions and screenshots, refer to my blog:

https://jyotirmayee.hashnode.dev/project-3-deploy-web-app-using-jenkins-master-and-worker-node
