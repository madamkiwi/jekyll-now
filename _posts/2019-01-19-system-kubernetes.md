As companies are embracing Kubernetes, we are also thinking about the next step to move toward the space.  As a standard Pivotal Labs practice, we conduct a three-week discovery and framing on the topic of deploying system components to Kubernetes.

We are a team of two designers, two product managers, and three engineers setting out to explore through interviewing with stakeholders, gathering requirements, synthesizing after each interview, brainstorming on user journey, and solutionizing the MVP.

Ops Manager is the interface to administer the runtime and services within the Pivotal Cloud Foundry deployment.  It uses Ruby on Rails with a React front end, and supports deployment on AWS, Azure, GCP, OpenStack, and vSphere.  As part of the deployment, Ops Manager spins up a BOSH director and generate a BOSH manifest based on user input, and uses BOSH cli to interact with the director to configure and deploy.

What we will be focusing on is the installation, cluster requirements, and structure of an extensible solution so that other teams can integrate and build on top of the MVP.  We will also be evaluating existing packaging management within k8s and different ways to provision clusters.
