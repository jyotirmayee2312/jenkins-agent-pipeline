# jenkins-agent-pipeline

 Here is a brief overview of deploying a web app using Jenkins master and agent nodes, followed by a link to my blog post for step-by-step instructions:

Jenkins is a popular open source automation server that allows implementing continuous integration and deployment pipelines for software projects. A key feature of Jenkins is its distributed architecture - it supports a master/controller node along with multiple agent/worker nodes. 

This allows scaling Jenkins by distributing build workloads across multiple agents. It also enables deploying apps directly on remote infrastructure by running jobs on agents placed close to the deployment servers.

In this post, I demonstrate setting up a simple Jenkins pipeline to deploy a static web app page onto a remote EC2 instance configured as a Jenkins agent.

The key steps are:

- Launch EC2 instances for Jenkins master and agent 

- Configure SSH access between master and agent

- Add the agent node in the Jenkins master UI

- Create a sample pipeline job to copy and deploy the web app

- Run a build to see the deployment happen on the agent node

For the complete step-by-step instructions and screenshots, refer to my blog:

https://jyotirmayee.hashnode.dev/project-3-deploy-web-app-using-jenkins-master-and-worker-node

Let me know if you need any clarification or have additional questions!


